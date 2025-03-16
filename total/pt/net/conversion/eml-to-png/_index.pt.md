---
title: API C# para exportar EML para PNG
description: Converta EML para PNG sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-png/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EPUB TIFF MD EMF ODT PDF DOTX JPEG PCL DOCX FLATOPC PS DOT DOCM TEXT WORDML OTT RTF GIF SVG XPS DOC DOTM PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para PNG via .NET" h2="API .NET para renderizar EML para PNG no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para PNG dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em PNG" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato PNG usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Png como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via .NET" %}}
Antes de converter EML para PNG, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos PNG via .NET" %}}
Ao salvar o documento de EML para PNG, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a PNG mediante programación: casos de uso" %}}
Arquivos de EML (Electronic Mail) são usados para armazenar informações de e-mail textuais, tornando-os ideais para enviar e receber mensagens. No entanto, ao trabalhar com conteúdo visual, imagens como PNG se tornam essenciais para exibir gráficos e ilustrações.

A conversão de arquivos EML para formatos PNG é necessária para desbloquear a potencial completa da sua capacidade de exibição de conteúdo visual. Essa conversão permite que você:

**Cenários de Uso:**

*   **Gráficos de Redes Sociais**: Converter arquivos EML para criar gráficos visuais atraentes de redes sociais, anúncios e materiais promocionais.
*   **Campanhas de E-mail de Marketing**: Usar PNG para visualizar campanhas de e-mail de marketing, otimizar projetos de design e medir métricas de engajamento.
*   **Gráficos da Web interativos**: Converter arquivos EML para criar gráficos da web interativos, simular experiências de usuário e validar conceitos de design.
*   **Ilustrações de Postagens do Blog**: Usar PNG para visualizar ilustrações de postagens do blog, criando conteúdo atraente para os leitores.
*   **Materiais de Apresentação Profissionais**: Converter arquivos EML para criar materiais de apresentação profissionais, exibindo visualizações de dados, gráficos e diagramas eficazmente.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}