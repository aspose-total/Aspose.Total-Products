---
title: API C# para exportar EML para EPUB
description: Converta EML para EPUB sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-epub/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOCM PCL PNG JPEG TIFF FLATOPC MD DOTM PS DOT DOCX EMF DOC WORDML ODT TEXT EPUB SVG OTT DOTX GIF RTF PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para EPUB via .NET" h2="API .NET para renderizar EML para EPUB no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para EPUB dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em EPUB" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato EPUB usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Epub como SaveFormat
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via .NET" %}}
Antes de converter EML para EPUB, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos EPUB via .NET" %}}
Ao salvar o documento de EML para EPUB, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a EPUB mediante programación: casos de uso" %}}
Arquivos de e-mail (EML) são usados para armazenar informações textuais, tornando-os ideais para correspondência pessoal e colaboração. No entanto, quando se trabalha com dados estruturados e conteúdo multimídia, formatos EPUB (Publicação Elétrica) se tornam essenciais para publicação digital e distribuição.

A conversão de arquivos EML em formatos EPUB é necessária para desbloquear o potencial completo do seu conteúdo digital e capacidades de publicação. Essa conversão permite que você:

**Uso Caso:**

*   **Publicação Digital**: Converter arquivos EML para criar publicações digitais interativas, revistas e newsletters, tornando-as acessíveis em vários dispositivos.
*   **Criar Livros Eletrônicos**: Usar EPUB para converter arquivos EML em livros eletrônicos, adequados para leitura em lectores, tablets e smartphones.
*   **Publicação de Posts do Blog**: Converter arquivos EML para publicar posts de blog em um formato estruturado, melhorando a descoberta e acessibilidade.
*   **Artigos de Pesquisa**: Usar EPUB para converter arquivos EML em artigos de pesquisa, tornando-os facilmente compartilháveis e citados.
*   **Colaboração de Documentos**: Converter arquivos EML para criar documentos editáveis que podem ser compartilhados com outros, facilitando a colaboração e o feedback."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}