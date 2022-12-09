---
title: Render EMLX ke BMP di Aplikasi Andorid
description: Ekspor EMLX ke BMP tanpa menggunakan Microsoft Word atau Outlook di aplikasi Android Anda

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: BMP
otherformats: JPEG DOC EPUB GIF PS TIFF RTF PCL XPS MD DOT OTT DOCM DOTX SVG ODT PNG DOCX DOTM WORDML FLATOPC PDF TEXT EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ubah EMLX menjadi BMP di Aplikasi Andorid" h2="Mendesain aplikasi Andorid untuk mengekspor EMLX ke BMP dengan menggunakan Andorid melalui Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikasi Andorid mudah digunakan untuk pengguna akhir setiap hari. Hari demi hari jumlah pengguna ponsel Android semakin meningkat. Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) perpustakaan Otomasi Format File yang kuat, Anda dapat mengembangkan aplikasi manipulasi dan konversi Emlx. Anda dapat mengonversi EMLX ke BMP dengan kombinasi [Aspose.Emlx for Android Java](https://products.aspose.com/emlx/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Menggunakan API pertama Anda dapat mengonversi format file EMLX ke HTML dan dengan menggunakan API kedua, Anda dapat merender HTML sebagai BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Mengonversi EMLX ke BMP di Andorid" %}}
1. Buka file EMLX menggunakan kelas [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. Konversi EMLX ke HTML dengan menggunakan [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions )) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format BMP menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur BMP sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Emlx untuk Android melalui Java](https://docs.aspose.com/emlx/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-jpeg/" name="EMLX Ke JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-doc/" name="EMLX Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-epub/" name="EMLX Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-gif/" name="EMLX Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-ps/" name="EMLX Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-tiff/" name="EMLX Ke TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-rtf/" name="EMLX Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-pcl/" name="EMLX Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-xps/" name="EMLX Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-md/" name="EMLX Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-dot/" name="EMLX Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-ott/" name="EMLX Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-docm/" name="EMLX Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-dotx/" name="EMLX Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-svg/" name="EMLX Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-odt/" name="EMLX Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-png/" name="EMLX Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-docx/" name="EMLX Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-dotm/" name="EMLX Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-wordml/" name="EMLX Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-flatopc/" name="EMLX Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-pdf/" name="EMLX Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-text/" name="EMLX Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/emlx-to-emf/" name="EMLX Ke EMF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}