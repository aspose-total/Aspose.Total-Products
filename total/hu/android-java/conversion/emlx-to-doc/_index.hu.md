---
title: Rendelje meg az EMLX-t DOC-nek az Andorid alkalmazásban
description: Exportálja az EMLX-t DOC-be Microsoft Word vagy Outlook használata nélkül az Andorid-alkalmazásokban

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOC
otherformats: PCL ODT RTF TEXT PS BMP OTT WORDML XPS DOCM DOT TIFF JPEG EMF EPUB FLATOPC PDF DOTX MD DOTM GIF PNG SVG DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Alakítsa át az EMLX-t DOC-vé az Andorid Apps-ben" h2="Andorid alkalmazások tervezése EMLX DOC-be exportálásához Andorid használatával Java API-n keresztül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az Andorid Apps a végfelhasználók számára napi szinten könnyen használható. Napról napra nő az Andorid telefonokat használók száma. A hatékony [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) fájlformátum-automatizálási könyvtárak segítségével e-mail-kezelési és -konvertáló alkalmazásokat fejleszthet. Az EMLX-t DOC-vé konvertálhatja az [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) és az [Aspose.Words for Andorid Java](https://) kombinációjával products.aspose.com/words/android-java/). Az első API-val konvertálhatja az EMLX fájlformátumot HTML-re, a második API-val pedig a HTML-t DOC-ként jelenítheti meg. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Az EMLX konvertálása DOC-re az Andoridban" %}}
1. Nyissa meg az EMLX fájlt a [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage) osztály használatával
2. Alakítsa át az EMLX-címet HTML-vé a [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) segítségével )) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot DOC formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével metódust, és állítsa be a DOC-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.Emlx for Android via Java](https://docs.aspose.com/emlx/androidjava/installation/) és az [Aspose.Words for Andorid via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOC
document.save("output.doc", SaveFormat.DOC); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-pcl/" name="EMLX Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-odt/" name="EMLX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-rtf/" name="EMLX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-text/" name="EMLX Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-ps/" name="EMLX Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-doc/" name="EMLX Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-ott/" name="EMLX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-wordml/" name="EMLX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-xps/" name="EMLX Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-docm/" name="EMLX Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-dot/" name="EMLX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-tiff/" name="EMLX Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-jpeg/" name="EMLX Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-emf/" name="EMLX Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-epub/" name="EMLX Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-flatopc/" name="EMLX Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-pdf/" name="EMLX Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-dotx/" name="EMLX Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-md/" name="EMLX Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-dotm/" name="EMLX Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-gif/" name="EMLX Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-png/" name="EMLX Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-svg/" name="EMLX Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/emlx-to-docx/" name="EMLX Nak nek DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}