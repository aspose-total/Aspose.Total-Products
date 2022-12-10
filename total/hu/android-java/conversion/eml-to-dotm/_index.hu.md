---
title: Rendelje meg az EML-t DOTM-nek az Andorid alkalmazásban
description: Exportálja az EML-t DOTM-be Microsoft Word vagy Outlook használata nélkül az Andorid-alkalmazásokban

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOTM
otherformats: PNG TEXT JPEG DOCM EMF GIF OTT PCL PDF WORDML DOCX DOT ODT DOC PS EPUB FLATOPC DOTX RTF MD XPS SVG TIFF BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Alakítsa át az EML-t DOTM-vé az Andorid Apps-ben" h2="Andorid alkalmazások tervezése EML DOTM-be exportálásához Andorid használatával Java API-n keresztül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az Andorid Apps a végfelhasználók számára napi szinten könnyen használható. Napról napra nő az Andorid telefonokat használók száma. A hatékony [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) fájlformátum-automatizálási könyvtárak segítségével e-mail-kezelési és -konvertáló alkalmazásokat fejleszthet. Az EML-t DOTM-vé konvertálhatja az [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) és az [Aspose.Words for Andorid Java](https://) kombinációjával products.aspose.com/words/android-java/). Az első API-val konvertálhatja az EML fájlformátumot HTML-re, a második API-val pedig a HTML-t DOTM-ként jelenítheti meg. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Az EML konvertálása DOTM-re az Andoridban" %}}
1. Nyissa meg az EML fájlt a [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) osztály használatával
2. Alakítsa át az EML-címet HTML-vé a [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) segítségével )) módszer
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) osztály használatával
4. Mentse a dokumentumot DOTM formátumba a [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) segítségével metódust, és állítsa be a DOTM-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Könnyedén használhatja az Aspose.Total for Android rendszert Java-n keresztül közvetlenül a [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) webhelyről és telepítse az [Aspose.Eml for Android via Java](https://docs.aspose.com/eml/androidjava/installation/) és az [Aspose.Words for Andorid via Java](https://docs.aspose.com/words) /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) alkalmazásaiban.

Másik megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/androidjava) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOTM
document.save("output.dotm", SaveFormat.DOTM); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-png/" name="EML Nak nek PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-text/" name="EML Nak nek TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-jpeg/" name="EML Nak nek JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-docm/" name="EML Nak nek DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-emf/" name="EML Nak nek EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-gif/" name="EML Nak nek GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-ott/" name="EML Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-pcl/" name="EML Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-pdf/" name="EML Nak nek PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-wordml/" name="EML Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-docx/" name="EML Nak nek DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-dot/" name="EML Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-odt/" name="EML Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-doc/" name="EML Nak nek DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-ps/" name="EML Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-epub/" name="EML Nak nek EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-flatopc/" name="EML Nak nek FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-dotx/" name="EML Nak nek DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-rtf/" name="EML Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-md/" name="EML Nak nek MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-xps/" name="EML Nak nek XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-svg/" name="EML Nak nek SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-tiff/" name="EML Nak nek TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/android-java/conversion/eml-to-dotm/" name="EML Nak nek DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}