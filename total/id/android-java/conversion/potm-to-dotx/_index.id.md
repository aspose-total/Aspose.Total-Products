---
title: Ekspor POTM ke DOTX di Andorid melalui Java
description: Konversi POTM ke DOTX di aplikasi seluler tanpa menginstal perangkat lunak apa pun

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOTX
otherformats: DOTM ODT DOCX OTT FLATOPC RTF DOCM TEXT WORD WORDML DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render POTM ke DOTX di Andorid melalui Java" h2="API format file untuk mengonversi POTM ke DOTX dalam aplikasi Android tanpa bergantung pada Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) memungkinkan manipulasi format file dalam aplikasi Android. Dengan menggunakan API yang disediakan dalam paket, Anda dapat mengotomatiskan proses konversi PowerPoint POTM ke Word DOTX di aplikasi Anda.
Anda dapat mengonversi dokumen yang Anda berikan dalam dua langkah. Anda dapat menggunakan [Aspose.Slides untuk Andorid melalui Java](https://products.aspose.com/slides/android-java/) yang merupakan API PowerPoint untuk aplikasi Android untuk merender POTM ke HTML. Setelah itu dengan menggunakan API pemrosesan dokumen [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) Anda dapat mengonversi HTML ke DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Render POTM ke DOTX di Android" %}}
1. Buka file POTM menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konversi POTM ke HTML dengan menggunakan [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metode dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi menggunakan kelas [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument)
4. Simpan dokumen ke format DOTX menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) dan atur Dotx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Slides for Android via Java](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dan [Aspose.Words untuk Andorid melalui Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-Java-from-maven-repository) di aplikasi.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-dotm/" name="POTM Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-odt/" name="POTM Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-dotxx/" name="POTM Ke DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-ott/" name="POTM Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-flatopc/" name="POTM Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-rtf/" name="POTM Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-dotxm/" name="POTM Ke DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-text/" name="POTM Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-word/" name="POTM Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-wordml/" name="POTM Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-dotx/" name="POTM Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/potm-to-dot/" name="POTM Ke DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}