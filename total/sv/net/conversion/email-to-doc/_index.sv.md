---
title: C# API för att exportera EMAIL till DOC
description: Konvertera EMAIL till DOC utan att använda Microsoft Word eller Outlook på .NET
url_ignore: /sv/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportera EMAIL till DOC via .NET" h2=".NET API för att rendera EMAIL till DOC på Windows, macOS och Linux utan att använda Word eller Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Om du är en .NET-utvecklare som vill lägga till EMAIL till DOC-konverteringsfunktioner i dina applikationer, är [Aspose.Total for .NET](https://products.aspose.com/total/net/) API:er för filformatsmanipulation vägen fram. Genom att använda [Aspose.Email for .NET](https://products.aspose.com/email/net/), kan du konvertera EMAIL-filformat till HTML. Efter det, genom att använda [Aspose.Words for .NET](https://products.aspose.com/words/net/), kan du rendera HTML till DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API för att konvertera EMAIL till DOC" %}}
1. Öppna EMAIL-filen med klassen [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Konvertera EMAIL till HTML med metoden [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Spara dokumentet i DOC-format med metoden [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) och ställ in Doc som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysera EMAIL-fil via .NET" %}}
Innan du konverterar EMAIL till DOC, om du vill vara säker på att du konverterar rätt e-post, kan du ladda EMAIL-dokumentet, analysera det och ta en titt på din önskade egenskap. Genom att använda [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) klass av [Aspose.Email for .NET](https://products.aspose.com/email /net/) API kan du få information om avsändare och mottagare. Du kan till exempel söka efter en specifik avsändar-e-post för konverteringen genom att använda egenskapen [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Begränsa DOC-dokumentredigering via .NET" %}}
När du sparar dokumentet från EMAIL till DOC kan du behöva skydda ditt utdatadokument. Ibland kan du behöva begränsa möjligheten att redigera ett dokument och endast tillåta vissa åtgärder med det. Detta kan vara användbart för att förhindra andra från att redigera känslig och konfidentiell information i ditt dokument. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, låter dig styra hur du begränsar innehållet med hjälp av [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) uppräkningsparameter. Du kan ställa in ditt dokument på skrivskyddat genom att använda följande kodrader. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}