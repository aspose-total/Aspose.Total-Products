---
title: Skicka EML till ODT i Andorid-appen
description: Exportera EML till ODT utan att använda Microsoft Word eller Outlook i dina Andorid-program
url: /sv/android-java/conversion/eml-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: ODT
otherformats: DOT EMF PS WORDML FLATOPC RTF TIFF BMP MD DOCX OTT EPUB SVG DOCM GIF PCL DOTM JPEG DOC PNG DOTX XPS TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Förvandla EML till ODT i Andorid Apps" h2="Utformar Andorid-applikationer för att exportera EML till ODT genom att använda Andorid via Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid Apps är enkla att använda för slutanvändare dagligen. Dag för dag ökar antalet användare av Andorid-telefoner. Genom att använda de kraftfulla [Aspose.Total för Android via Java](https://products.aspose.com/total/android-java/) filformatsautomatiseringsbibliotek kan du utveckla applikationer för e-postmanipulation och -konvertering. Du kan konvertera EML till ODT genom att kombinera [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) och [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Med det första API:et kan du konvertera EML-filformatet till HTML och genom att använda det andra API:et kan du rendera HTML som ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera EML till ODT i Andorid" %}}
1. Öppna EML-filen med klassen [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Konvertera EML till HTML genom att använda [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) metod
3. Ladda HTML genom att använda klassen [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Spara dokumentet i ODT-format med [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) och ställ in ODT som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Du kan enkelt använda Aspose.Total för Android via Java direkt från [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) och installera [Aspose.Eml för Android via Java](https://docs.aspose.com/eml/androidjava/installation/) och [Aspose.Words för Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) i dina applikationer.

Alternativt kan du få en ZIP-fil från [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-dot/" name="EML Till DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-emf/" name="EML Till EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-ps/" name="EML Till PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-wordml/" name="EML Till WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-flatopc/" name="EML Till FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-rtf/" name="EML Till RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-tiff/" name="EML Till TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-odt/" name="EML Till ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-md/" name="EML Till MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-docx/" name="EML Till DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-ott/" name="EML Till OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-epub/" name="EML Till EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-svg/" name="EML Till SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-docm/" name="EML Till DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-gif/" name="EML Till GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-pcl/" name="EML Till PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-dotm/" name="EML Till DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-jpeg/" name="EML Till JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-doc/" name="EML Till DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-png/" name="EML Till PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-dotx/" name="EML Till DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-xps/" name="EML Till XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-text/" name="EML Till TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/android-java/conversion/eml-to-pdf/" name="EML Till PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}