---
title: Skicka EMLX till MD i Andorid-appen
description: Exportera EMLX till MD utan att använda Microsoft Word eller Outlook i dina Andorid-program

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: MD
otherformats: DOTX OTT DOCX PDF JPEG EMF PS DOT EPUB XPS ODT DOC GIF PNG PCL TEXT TIFF DOCM DOTM FLATOPC SVG BMP RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Förvandla EMLX till MD i Andorid Apps" h2="Utformar Andorid-applikationer för att exportera EMLX till MD genom att använda Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps är enkla att använda för slutanvändare dagligen. Dag för dag ökar antalet användare av Andorid-telefoner. Genom att använda de kraftfulla [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) filformatsautomatiseringsbibliotek kan du utveckla applikationer för e-postmanipulation och -konvertering. Du kan konvertera EMLX till MD genom att kombinera [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) och [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Med det första API:et kan du konvertera EMLX-filformatet till HTML och genom att använda det andra API:et kan du rendera HTML som MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera EMLX till MD i Andorid" %}}
1. Öppna EMLX-filen med klassen [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Konvertera EMLX till HTML genom att använda [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) metod
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i MD-format med [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) och ställ in MD som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Emlx för Android via Java](https://docs.aspose.com/emlx/androidjava/installation/) och [Aspose.Words för Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.MD
document.save("output.md", SaveFormat.MD); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-dotx/" name="EMLX Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-ott/" name="EMLX Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-docx/" name="EMLX Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-pdf/" name="EMLX Till PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-jpeg/" name="EMLX Till JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-emf/" name="EMLX Till EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-ps/" name="EMLX Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-dot/" name="EMLX Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-epub/" name="EMLX Till EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-xps/" name="EMLX Till XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-odt/" name="EMLX Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-doc/" name="EMLX Till DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-gif/" name="EMLX Till GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-png/" name="EMLX Till PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-pcl/" name="EMLX Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-text/" name="EMLX Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-tiff/" name="EMLX Till TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-docm/" name="EMLX Till DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-dotm/" name="EMLX Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-flatopc/" name="EMLX Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-svg/" name="EMLX Till SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-md/" name="EMLX Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-rtf/" name="EMLX Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/emlx-to-wordml/" name="EMLX Till WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}