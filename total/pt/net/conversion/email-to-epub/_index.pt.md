---
title: API C# para exportar EMAIL para EPUB
description: Converta EMAIL para EPUB sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL para EPUB via .NET" h2="API .NET para renderizar EMAIL para EPUB no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMAIL para EPUB dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMAIL em EPUB" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMAIL para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato EPUB usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Epub como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMAIL via .NET" %}}
Antes de converter EMAIL para EPUB, se você quiser ter certeza de que está convertendo o email correto, você pode carregar o documento EMAIL, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos EPUB via .NET" %}}
Ao salvar o documento de EMAIL para EPUB, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a EPUB mediante programación: casos de uso" %}}
Arquivos de e-mail são usados para armazenar mensagens textuais, tornando-os ideais para criar comunicações personalizadas e newsletters. No entanto, ao trabalhar com conteúdo multimídia, os formatos EPUB (Publicação Eletrônica) se tornam essenciais para a publicação digital e distribuição de livros.

A conversão de arquivos de e-mail em formatos EPUB é necessária para desbloquear o potencial pleno das suas capacidades de publicação digital. Essa conversão permite:

**Usos:**

*   **Notificações Personalizadas de E-Newsletter**: Converter os arquivos de e-mail para criar notificações personalizadas de e-newsletter, com nomes de assinantes e interesses.
*   **Publicação de Revistas Digitais**: Usar EPUB para publicar revistas digitais, jornais e periódicos em um formato fácil de ler em dispositivos variados.
*   **Publique Livros Eletrônicos Interativos**: Converter os arquivos de e-mail para criar livros eletrônicos interativos, completos com hyperlinks, imagens e conteúdo multimídia.
*   **Comunicação Corporativa**: Usar EPUB para distribuir relatórios da empresa, políticas e procedimentos em um formato acessível a funcionários e stakeholders.
*   **Distribuição de Conteúdo Digital**: Converter os arquivos de e-mail para publicar conteúdo digital, como postagens do blog, artigos e vídeos, em várias plataformas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}