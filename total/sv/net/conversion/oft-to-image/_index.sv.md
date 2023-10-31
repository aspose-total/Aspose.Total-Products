---
title: C# API för att exportera OFT till IMAGE
description: Konvertera OFT till IMAGE utan att använda Microsoft Word eller Outlook på .NET
url_ignore: /sv/net/conversion/oft-to-image/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: IMAGE
otherformats: TIFF DOTX DOC PDF ODT XPS MD GIF SVG PCL DOCM RTF DOCX PNG EPUB TEXT IMAGE DOTM DOT EMF JPEG FLATOPC OTT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera OFT till IMAGE via .NET" h2=".NET API för att rendera OFT till IMAGE på Windows, macOS och Linux utan att använda Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Om du är en .NET-utvecklare som vill lägga till OFT till IMAGE-konverteringsfunktioner i dina applikationer, är [Aspose.Total for .NET](https://products.aspose.com/total/net/) API:er för filformatsmanipulation vägen fram. Genom att använda [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), kan du konvertera OFT-filformat till HTML. Efter det, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera HTML till IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera OFT till IMAGE" %}}
1. Öppna OFT-filen med klassen [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konvertera OFT till HTML med metoden [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Spara dokumentet i IMAGE-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Image som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.oft");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera OFT-fil via .NET" %}}
Innan du konverterar OFT till IMAGE, om du vill vara säker på att du konverterar rätt e-post, kan du ladda OFT-dokumentet, analysera det och ta en titt på din önskade egenskap. Genom att använda [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klass av [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API kan du få information om avsändare och mottagare. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa IMAGE-dokumentredigering via .NET" %}}
När du sparar dokumentet från OFT till IMAGE kan du behöva skydda ditt utdatadokument. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan vara användbart för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, låter dig styra hur du begränsar innehållet med hjälp av [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) uppräkningsparameter. Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}