---
title: Ekspor PPS ke WORD di Andorid melalui Java
description: Konversi PPS ke WORD di aplikasi seluler tanpa menginstal perangkat lunak apa pun
url: /id/android-java/conversion/pps-to-word/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCX
otherformats: FLATOPC ODT DOCM TEXT DOTM DOTX DOCX DOT RTF WORDML DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PPS ke WORD di Andorid melalui Java" h2="API format file untuk mengonversi PPS ke WORD dalam aplikasi Android tanpa bergantung pada Microsoft PowerPoint atau Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total untuk Android melalui Java](https://products.aspose.com/total/android-java/) memungkinkan manipulasi format file dalam aplikasi Android. Dengan menggunakan API yang disediakan dalam paket, Anda dapat mengotomatiskan proses konversi PowerPoint PPS ke Word WORD di aplikasi Anda.
Anda dapat mengonversi dokumen yang Anda berikan dalam dua langkah. Anda dapat menggunakan [Aspose.Slides untuk Andorid melalui Java](https://products.aspose.com/slides/android-java/) yang merupakan API PowerPoint untuk aplikasi Android untuk merender PPS ke HTML. Setelah itu dengan menggunakan API pemrosesan dokumen [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) Anda dapat mengonversi HTML ke WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Render PPS ke WORD di Android" %}}
1. Buka file PPS menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Konversi PPS ke HTML dengan menggunakan [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metode dan atur Html sebagai SaveFormat
3. Muat file HTML yang dikonversi menggunakan kelas [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
4. Simpan dokumen ke format WORD menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,int)) dan atur Word sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Android melalui Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Slides untuk Android melalui Java](https://words.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) dan [Aspose.Words untuk Andorid melalui Java](https://words.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-Java-from-maven-repository) di aplikasi.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Wordument
Wordument wordument = new Wordument("htmlOutput.html");
// save wordument in WORDX format
wordument.save("output.wordx",SaveFormat.Wordx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-flatopc/" name="PPS Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-odt/" name="PPS Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-wordm/" name="PPS Ke WORDM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-text/" name="PPS Ke TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dotm/" name="PPS Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dotx/" name="PPS Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-wordx/" name="PPS Ke WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-dot/" name="PPS Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-rtf/" name="PPS Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-wordml/" name="PPS Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-word/" name="PPS Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pps-to-ott/" name="PPS Ke OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}