---
title: API C# para exportar MSG para DOTM
description: Converta MSG para DOTM sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/msg-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOTM
otherformats: DOC OTT EPUB JPEG WORDML FLATOPC PDF EMF TIFF DOT ODT DOCM GIF XPS TEXT PNG DOCX PS PCL DOTX DOTM MD SVG RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MSG para DOTM via .NET" h2="API .NET para renderizar MSG para DOTM no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de MSG para DOTM dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email para .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo MSG para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter MSG em DOTM" %}}
1. Abra o arquivo MSG usando a classe [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Converta MSG para HTML usando o método [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato DOTM usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Dotm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.dotm", SaveFormat.Dotm); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo MSG via .NET" %}}
Antes de converter MSG para DOTM, se você quiser ter certeza de que está convertendo o msg correto, você pode carregar o documento MSG, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos DOTM via .NET" %}}
Ao salvar o documento de MSG para DOTM, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras opções de conversão" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-pcl/" name="MSG PARA PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-pdf/" name="MSG PARA PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-dot/" name="MSG PARA PONTO" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-flatopc/" name="MSG PARA FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-jpeg/" name="MSG PARA JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-png/" name="MSG PARA PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-rtf/" name="MSG PARA RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-tiff/" name="MSG PARA TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-docm/" name="MSG PARA DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-ps/" name="MSG PARA PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-gif/" name="MSG PARA GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-xps/" name="MSG PARA XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-odt/" name="MSG PARA ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-docx/" name="MSG PARA DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-doc/" name="MSG PARA DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-wordml/" name="MSG PARA WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-svg/" name="MSG PARA SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-epub/" name="MSG PARA EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-md/" name="MSG PARA MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-emf/" name="MSG PARA EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-dotm/" name="MSG PARA DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-ott/" name="MSG PARA OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-dotx/" name="MSG PARA DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/net/conversion/msg-to-text/" name="MSG PARA TEXTO" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}