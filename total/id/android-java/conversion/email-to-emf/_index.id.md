---
title: Render EMAIL ke EMF di Aplikasi Andorid
description: Ekspor EMAIL ke EMF tanpa menggunakan Microsoft Word atau Outlook di aplikasi Android Anda

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: EMF
otherformats: JPEG DOC EPUB RTF TIFF ODT DOTM DOCM DOCX BMP FLATOPC PNG GIF DOT PCL WORDML DOTX MD PDF SVG PS TEXT XPS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ubah EMAIL menjadi EMF di Aplikasi Andorid" h2="Mendesain aplikasi Andorid untuk mengekspor EMAIL ke EMF dengan menggunakan Andorid melalui Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikasi Andorid mudah digunakan untuk pengguna akhir setiap hari. Hari demi hari jumlah pengguna ponsel Android semakin meningkat. Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) perpustakaan Otomasi Format File yang kuat, Anda dapat mengembangkan aplikasi manipulasi dan konversi Email. Anda dapat mengonversi EMAIL ke EMF dengan kombinasi [Aspose.Email for Android Java](https://products.aspose.com/email/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Menggunakan API pertama Anda dapat mengonversi format file EMAIL ke HTML dan dengan menggunakan API kedua, Anda dapat merender HTML sebagai EMF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Mengonversi EMAIL ke EMF di Andorid" %}}
1. Buka file EMAIL menggunakan kelas [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konversi EMAIL ke HTML dengan menggunakan [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format EMF menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur EMF sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Email for Android via Java](https://docs.aspose.com/email/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.EMF
document.save("output.emf", SaveFormat.EMF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-jpeg/" name="MSG Ke JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-doc/" name="MSG Ke DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-epub/" name="MSG Ke EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-rtf/" name="MSG Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-tiff/" name="MSG Ke TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-odt/" name="MSG Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-dotm/" name="MSG Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-docm/" name="MSG Ke DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-docx/" name="MSG Ke DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-emf/" name="MSG Ke EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-flatopc/" name="MSG Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-png/" name="MSG Ke PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-gif/" name="MSG Ke GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-dot/" name="MSG Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-pcl/" name="MSG Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-wordml/" name="MSG Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-dotx/" name="MSG Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-md/" name="MSG Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-pdf/" name="MSG Ke PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-svg/" name="MSG Ke SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-ps/" name="MSG Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-text/" name="MSG Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-xps/" name="MSG Ke XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/msg-to-ott/" name="MSG Ke OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}