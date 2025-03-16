---
title: API C# para exportar EML para PCL
description: Converta EML para PCL sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PCL
otherformats: MD DOCX RTF WORDML ODT PCL SVG DOT DOC XPS DOTM JPEG OTT PDF EPUB PS TIFF GIF TEXT PNG DOTX DOCM FLATOPC EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para PCL via .NET" h2="API .NET para renderizar EML para PCL no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para PCL dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em PCL" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato PCL usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Pcl como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.pcl", SaveFormat.Pcl); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via .NET" %}}
Antes de converter EML para PCL, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos PCL via .NET" %}}
Ao salvar o documento de EML para PCL, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a PCL mediante programación: casos de uso" %}}
Arquivos de EML (Electronic Mail) são usados para armazenar mensagens textuais, tornando-os ideais para comunicação pessoal e colaboração. No entanto, ao trabalhar com dados de gráficos vetoriais, arquivos PCL (Linguagem de Controle de Impressão) se tornam essenciais para impressões precisas e saídas.

A conversão de arquivos EML para formatos PCL é necessária para desbloquear a potencial completa das suas capacidades de impressão. Essa conversão permite que você:

*   **Uso Caso:** 
    *   **Printar Logotipos Personalizados**: Converter arquivos EML para criar logotipos personalizados, gráficos e imagens.
    *   **Documentação Técnica e Planilhas**: Usar PCL para imprimir planilhas técnicas, esboços azuis e documentos com precisão e detalhes.
    *   **Design Gráfico e Arte**: Converter arquivos EML para criar projetos de design intrincados, ilustrações e arte para impressão ou visualização digital.
    *   **Impressão de Códigos Bárbaros e Etiquetas**: Usar PCL para imprimir códigos bárbaros, etiquetas e etiquetas com precisão e velocidade, ideais para gerenciamento de estoque e rastreamento de cadeia de fornecimento.
    *   **Revisão e Edição de Texto**: Converter arquivos EML para revisar e editar documentos textuais com controle preciso sobre estilos de fonte, tamanhos e formatação.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}