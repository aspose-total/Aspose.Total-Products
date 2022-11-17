---
title: Ekspor PPS ke ODT di Andorid melalui Java
description: Konversi PPS ke ODT di aplikasi seluler tanpa menginstal perangkat lunak apa pun

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: ODT
otherformats: DOTX DOTM TEXT RTF WORDML FLATOPC DOCM DOC WORD OTT DOCX DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PPS ke ODT di Andorid melalui Java" h2="API format file untuk mengonversi PPS ke ODT dalam aplikasi Android tanpa bergantung pada Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) memungkinkan manipulasi format file dalam aplikasi Android. Dengan menggunakan API yang disediakan dalam paket, Anda dapat mengotomatiskan proses konversi PowerPoint PPS ke Word ODT di aplikasi Anda.
Anda dapat mengonversi dokumen yang Anda berikan dalam dua langkah. Anda dapat menggunakan [Aspose.Slides untuk Andorid melalui Java](https://products.aspose.com/slides/android-java/) yang merupakan API PowerPoint untuk aplikasi Android untuk merender PPS ke HTML. Setelah itu dengan menggunakan API pemrosesan dokumen [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) Anda dapat mengonversi HTML ke ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Render PPS ke ODT di Android" %}}
1. Buka file PPS menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konversi PPS ke HTML dengan menggunakan [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metode dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi menggunakan kelas [Odtument](https://reference.aspose.com/words/java/com.aspose.words/Odtument)
4. Simpan dokumen ke format ODT menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Odtument#save(java.lang.String,int)) dan atur Odt sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Slides for Android via Java](https://odts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dan [Aspose.Words untuk Andorid melalui Java](https://odts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-Java-from-maven-repository) di aplikasi.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Odtument
Odtument odtument = new Odtument("htmlOutput.html");
// save odtument in ODT format
odtument.save("output.odt",SaveFormat.Odt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dotx/" name="PPS Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dotm/" name="PPS Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-text/" name="PPS Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-rtf/" name="PPS Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-wordml/" name="PPS Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-flatopc/" name="PPS Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-odtm/" name="PPS Ke ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-odt/" name="PPS Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-word/" name="PPS Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-ott/" name="PPS Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-odtx/" name="PPS Ke ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dot/" name="PPS Ke DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}