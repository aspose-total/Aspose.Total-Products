---
title: Skicka MSG till PNG i Andorid-appen
description: Exportera MSG till PNG utan att använda Microsoft Word eller Outlook i dina Andorid-program
url: /sv/android-java/conversion/msg-to-png/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOC DOCM GIF TIFF WORDML XPS ODT FLATOPC EMF RTF PS EPUB DOT BMP PCL MD DOTM DOCX DOTX TEXT JPEG OTT PDF SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Förvandla MSG till PNG i Andorid Apps" h2="Utformar Andorid-applikationer för att exportera MSG till PNG genom att använda Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps är enkla att använda för slutanvändare dagligen. Dag för dag ökar antalet användare av Andorid-telefoner. Genom att använda de kraftfulla [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) filformatsautomatiseringsbibliotek kan du utveckla applikationer för e-postmanipulation och -konvertering. Du kan konvertera MSG till PNG genom att kombinera [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) och [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Med det första API:et kan du konvertera MSG-filformatet till HTML och genom att använda det andra API:et kan du rendera HTML som PNG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera MSG till PNG i Andorid" %}}
1. Öppna MSG-filen med klassen [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. Konvertera MSG till HTML genom att använda [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions )) metod
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i PNG-format med [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) och ställ in PNG som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total for Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Msg för Android via Java](https://docs.aspose.com/msg/androidjava/installation/) och [Aspose.Words för Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-doc/" name="MSG Till DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-docm/" name="MSG Till DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-gif/" name="MSG Till GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-tiff/" name="MSG Till TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-wordml/" name="MSG Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-xps/" name="MSG Till XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-odt/" name="MSG Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-flatopc/" name="MSG Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-emf/" name="MSG Till EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-rtf/" name="MSG Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-ps/" name="MSG Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-epub/" name="MSG Till EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-dot/" name="MSG Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-png/" name="MSG Till PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-pcl/" name="MSG Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-md/" name="MSG Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-dotm/" name="MSG Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-docx/" name="MSG Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-dotx/" name="MSG Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-text/" name="MSG Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-jpeg/" name="MSG Till JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-ott/" name="MSG Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-pdf/" name="MSG Till PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/msg-to-svg/" name="MSG Till SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}