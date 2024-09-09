---
title: C# API för att exportera EMLX till GIF
description: Konvertera EMLX till GIF utan att använda Microsoft Word eller Outlook på .NET
url_ignore: /sv/net/conversion/emlx-to-gif/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: GIF
otherformats: DOTM DOC DOT PS EPUB JPEG PNG FLATOPC EMF OTT DOCX MD PCL TIFF XPS GIF ODT DOCM WORDML DOTX RTF TEXT SVG PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera EMLX till GIF via .NET" h2=".NET API för att rendera EMLX till GIF på Windows, macOS och Linux utan att använda Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Om du är en .NET-utvecklare som vill lägga till EMLX till GIF-konverteringsfunktioner i dina applikationer, är [Aspose.Total for .NET](https://products.aspose.com/total/net/) API:er för filformatsmanipulation vägen fram. Genom att använda [Aspose.Email for .NET](https://products.aspose.com/email/net/), kan du konvertera EMLX-filformat till HTML. Efter det, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera HTML till GIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera EMLX till GIF" %}}
1. Öppna EMLX-filen med klassen [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konvertera EMLX till HTML med metoden [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Spara dokumentet i GIF-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Gif som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera EMLX-fil via .NET" %}}
Innan du konverterar EMLX till GIF, om du vill vara säker på att du konverterar rätt e-post, kan du ladda EMLX-dokumentet, analysera det och ta en titt på din önskade egenskap. Genom att använda [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klass av [Aspose.Email for .NET](https://products.aspose.com/email /net/) API kan du få information om avsändare och mottagare. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa GIF-dokumentredigering via .NET" %}}
När du sparar dokumentet från EMLX till GIF kan du behöva skydda ditt utdatadokument. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan vara användbart för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, låter dig styra hur du begränsar innehållet med hjälp av [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) uppräkningsparameter. Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}