---
title: Rendelje meg az MSG-t EMF-nek az Andorid alkalmazásban
description: Exportálja az MSG-t EMF-be Microsoft Word vagy Outlook használata nélkül az Andorid-alkalmazásokban
url: /hu/android-java/conversion/msg-to-emf/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: EMF
otherformats: FLATOPC DOCX DOTM OTT BMP EPUB TIFF TEXT PCL JPEG SVG DOT RTF MD DOTX PNG DOC XPS GIF WORDML PDF PS DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Alakítsa át az MSG-t EMF-vé az Andorid Apps-ben" h2="Andorid alkalmazások tervezése MSG EMF-be exportálásához Andorid használatával Java API-n keresztül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az Andorid Apps a végfelhasználók számára napi szinten könnyen használható. Napról napra nő az Andorid telefonokat használók száma. A hatékony [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) fájlformátum-automatizálási könyvtárak segítségével e-mail-kezelési és -konvertáló alkalmazásokat fejleszthet. Az MSG-t EMF-vé konvertálhatja az [Aspose.Msg for Android Java](https://products.aspose.com/msg/android-java/) és az [Aspose.Words for Andorid Java](https://) kombinációjával products.aspose.com/words/android-java/). Az első API-val konvertálhatja az MSG fájlformátumot HTML-re, a második API-val pedig a HTML-t EMF-ként jelenítheti meg. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Az MSG konvertálása EMF-re az Andoridban" %}}
1. Nyissa meg az MSG fájlt a [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage) osztály használatával
2. Alakítsa át az MSG-címet HTML-vé a [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) segítségével )) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot EMF formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével metódust, és állítsa be a EMF-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.Msg for Android via Java](https://docs.aspose.com/msg/androidjava/installation/) és az [Aspose.Words for Andorid via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://downloads.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EMF
document.save("output.emf", SaveFormat.EMF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-flatopc/" name="MSG Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-docx/" name="MSG Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-dotm/" name="MSG Nak nek DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-ott/" name="MSG Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-emf/" name="MSG Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-epub/" name="MSG Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-tiff/" name="MSG Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-text/" name="MSG Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-pcl/" name="MSG Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-jpeg/" name="MSG Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-svg/" name="MSG Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-dot/" name="MSG Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-rtf/" name="MSG Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-md/" name="MSG Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-dotx/" name="MSG Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-png/" name="MSG Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-doc/" name="MSG Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-xps/" name="MSG Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-gif/" name="MSG Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-wordml/" name="MSG Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-pdf/" name="MSG Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-ps/" name="MSG Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-docm/" name="MSG Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/msg-to-odt/" name="MSG Nak nek ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}