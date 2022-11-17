---
title: Render OFT ke TEXT di Aplikasi Andorid
description: Ekspor OFT ke TEXT tanpa menggunakan Microsoft Word atau Outlook di aplikasi Android Anda

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: TEXT
otherformats: DOT ODT DOC SVG XPS BMP PNG TIFF OTT RTF PCL EMF MD WORDML DOCX GIF FLATOPC DOCM DOTX PDF EPUB DOTM PS JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ubah OFT menjadi TEXT di Aplikasi Andorid" h2="Mendesain aplikasi Andorid untuk mengekspor OFT ke TEXT dengan menggunakan Andorid melalui Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikasi Andorid mudah digunakan untuk pengguna akhir setiap hari. Hari demi hari jumlah pengguna ponsel Android semakin meningkat. Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) perpustakaan Otomasi Format File yang kuat, Anda dapat mengembangkan aplikasi manipulasi dan konversi Oft. Anda dapat mengonversi OFT ke TEXT dengan kombinasi [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Menggunakan API pertama Anda dapat mengonversi format file OFT ke HTML dan dengan menggunakan API kedua, Anda dapat merender HTML sebagai TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Mengonversi OFT ke TEXT di Andorid" %}}
1. Buka file OFT menggunakan kelas [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Konversi OFT ke HTML dengan menggunakan [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format TEXT menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur TEXT sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Oft untuk Android melalui Java](https://docs.aspose.com/oft/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-dot/" name="OFT Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-odt/" name="OFT Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-doc/" name="OFT Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-svg/" name="OFT Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-xps/" name="OFT Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-text/" name="OFT Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-png/" name="OFT Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-tiff/" name="OFT Ke TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-ott/" name="OFT Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-rtf/" name="OFT Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-pcl/" name="OFT Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-emf/" name="OFT Ke EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-md/" name="OFT Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-wordml/" name="OFT Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-docx/" name="OFT Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-gif/" name="OFT Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-flatopc/" name="OFT Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-docm/" name="OFT Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-dotx/" name="OFT Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-pdf/" name="OFT Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-epub/" name="OFT Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-dotm/" name="OFT Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-ps/" name="OFT Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/oft-to-jpeg/" name="OFT Ke JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}