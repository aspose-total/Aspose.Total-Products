---
title: Render EML ke EPUB di Aplikasi Andorid
description: Ekspor EML ke EPUB tanpa menggunakan Microsoft Word atau Outlook di aplikasi Android Anda
url: /id/android-java/conversion/eml-to-epub/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: EPUB
otherformats: PS DOCM DOCX DOC BMP OTT FLATOPC TEXT DOTM RTF JPEG PDF SVG ODT PCL XPS DOT GIF DOTX WORDML EMF PNG MD TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ubah EML menjadi EPUB di Aplikasi Andorid" h2="Mendesain aplikasi Andorid untuk mengekspor EML ke EPUB dengan menggunakan Andorid melalui Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikasi Andorid mudah digunakan untuk pengguna akhir setiap hari. Hari demi hari jumlah pengguna ponsel Android semakin meningkat. Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) perpustakaan Otomasi Format File yang kuat, Anda dapat mengembangkan aplikasi manipulasi dan konversi Eml. Anda dapat mengonversi EML ke EPUB dengan kombinasi [Aspose.Eml for Android Java](https://products.aspose.com/eml/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Menggunakan API pertama Anda dapat mengonversi format file EML ke HTML dan dengan menggunakan API kedua, Anda dapat merender HTML sebagai EPUB. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Mengonversi EML ke EPUB di Andorid" %}}
1. Buka file EML menggunakan kelas [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Konversi EML ke HTML dengan menggunakan [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions )) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format EPUB menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur EPUB sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Eml untuk Android melalui Java](https://docs.aspose.com/eml/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EPUB
document.save("output.epub", SaveFormat.EPUB); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-ps/" name="EML Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-docm/" name="EML Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-docx/" name="EML Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-doc/" name="EML Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-epub/" name="EML Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-ott/" name="EML Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-flatopc/" name="EML Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-text/" name="EML Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-dotm/" name="EML Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-rtf/" name="EML Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-jpeg/" name="EML Ke JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-pdf/" name="EML Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-svg/" name="EML Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-odt/" name="EML Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-pcl/" name="EML Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-xps/" name="EML Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-dot/" name="EML Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-gif/" name="EML Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-dotx/" name="EML Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-wordml/" name="EML Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-emf/" name="EML Ke EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-png/" name="EML Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-md/" name="EML Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/eml-to-tiff/" name="EML Ke TIFF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}