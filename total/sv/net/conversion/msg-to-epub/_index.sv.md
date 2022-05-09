---
title: C# API för att exportera MSG till EPUB
description: Konvertera MSG till EPUB utan att använda Microsoft Word eller Outlook på .NET
url_ignore: /sv/net/conversion/msg-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: PDF DOT DOTM DOCM GIF SVG OTT XPS PS TEXT RTF PCL ODT EPUB DOC TIFF FLATOPC WORDML PNG EMF MD JPEG DOTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera MSG till EPUB via .NET" h2=".NET API för att rendera MSG till EPUB på Windows, macOS och Linux utan att använda Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Om du är en .NET-utvecklare som vill lägga till MSG till EPUB-konverteringsfunktioner i dina applikationer, är [Aspose.Total for .NET](https://products.aspose.com/total/net/) API:er för filformatsmanipulation vägen fram. Genom att använda [Aspose.Email for .NET](https://products.aspose.com/email/net/), kan du konvertera MSG-filformat till HTML. Efter det, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera HTML till EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera MSG till EPUB" %}}
1. Öppna MSG-filen med klassen [MailMessage](https://apireference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Konvertera MSG till HTML med metoden [Save](https://apireference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Ladda HTML genom att använda klassen [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Spara dokumentet i EPUB-format med metoden [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Epub som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/net).
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

{{% blocks/products/pf/feature-page-section  h2="Analysera MSG-fil via .NET" %}}
Innan du konverterar MSG till EPUB, om du vill vara säker på att du konverterar rätt e-post, kan du ladda MSG-dokumentet, analysera det och ta en titt på din önskade egenskap. Genom att använda [MapiMessage](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) klass av [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API kan du få information om avsändare och mottagare. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen [SenderName](https://apireference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Begränsa EPUB-dokumentredigering via .NET" %}}
När du sparar dokumentet från MSG till EPUB kan du behöva skydda ditt utdatadokument. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan vara användbart för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, låter dig styra hur du begränsar innehållet med hjälp av [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) uppräkningsparameter. Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra konverteringsalternativ" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-pcl/" name="MSG TILL PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-pdf/" name="MSG TILL PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-dot/" name="MSG TO PUNKT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-flatopc/" name="MSG TILL FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-jpeg/" name="MSG TILL JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-png/" name="MSG TILL PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-rtf/" name="MSG TILL RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-tiff/" name="MSG TILL TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-docm/" name="MSG TILL DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-ps/" name="MSG TILL PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-gif/" name="MSG TILL GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-xps/" name="MSG TILL XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-odt/" name="MSG TILL ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-docx/" name="MSG TILL DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-doc/" name="MSG TILL DOK" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-wordml/" name="MSG TILL WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-svg/" name="MSG TILL SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-epub/" name="MSG TILL EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-md/" name="MSG TILL MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-emf/" name="MSG TILL EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-dotm/" name="MSG TILL DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-ott/" name="MSG TILL OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-dotx/" name="MSG TILL DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/net/conversion/msg-to-text/" name="MSG TILL TEXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}