---
title: Render OFT ke DOCM di Aplikasi Andorid
description: Ekspor OFT ke DOCM tanpa menggunakan Microsoft Word atau Outlook di aplikasi Android Anda

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOCM
otherformats: GIF DOC EMF DOCX DOTM OTT PS FLATOPC MD ODT DOT WORDML PCL EPUB TIFF RTF PDF XPS JPEG TEXT SVG BMP DOTX PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Ubah OFT menjadi DOCM di Aplikasi Andorid" h2="Mendesain aplikasi Andorid untuk mengekspor OFT ke DOCM dengan menggunakan Andorid melalui Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Aplikasi Andorid mudah digunakan untuk pengguna akhir setiap hari. Hari demi hari jumlah pengguna ponsel Android semakin meningkat. Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) perpustakaan Otomasi Format File yang kuat, Anda dapat mengembangkan aplikasi manipulasi dan konversi Oft. Anda dapat mengonversi OFT ke DOCM dengan kombinasi [Aspose.Oft for Android Java](https://products.aspose.com/oft/android-java/) & [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). Menggunakan API pertama Anda dapat mengonversi format file OFT ke HTML dan dengan menggunakan API kedua, Anda dapat merender HTML sebagai DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Mengonversi OFT ke DOCM di Andorid" %}}
1. Buka file OFT menggunakan kelas [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. Konversi OFT ke HTML dengan menggunakan [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions )) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format DOCM menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur DOCM sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal [Aspose.Oft untuk Android melalui Java](https://docs.aspose.com/oft/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCM
document.save("output.docm", SaveFormat.DOCM); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}