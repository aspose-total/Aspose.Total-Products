---
title: Ekspor XSLFO ke PPS di Android
description: Android API untuk Mengonversi XSLFO ke PPS tanpa menggunakan Microsoft Word
url: /id/android-java/conversion/xslfo-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: PPS
otherformats: POTM POTX SWF PPSM POT PPT OTP POWERPOINT PPTM PPSX ODP XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi XSLFO ke PPS di Android melalui Java" h2="Ubah XSLFO menjadi PPS dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi XSLFO ke PPS di dalam aplikasi Android Anda dengan menggunakan dua langkah sederhana. Pada langkah pertama Anda dapat mengekspor XSLFO ke PPTX dengan menggunakan [Aspose.PDF untuk Android melalui Java](https://products.aspose.com/pdf/android-java/). Setelah itu, dengan menggunakan [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), Anda dapat mengonversi PPTX ke PPS. Kedua API berada di bawah paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor XSLFO ke PPS" %}}
1. Buka file XSLFO menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi XSLFO ke PPTX dengan menggunakan metode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Simpan dokumen ke format PPS menggunakan metode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) dan set ` Pps` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Android melalui Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF untuk Android melalui Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Slides untuk Android melalui Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Buka File XSLFO yang Dilindungi Kata Sandi di Android melalui Java" %}}
Saat memuat format file XSLFO, dokumen Anda mungkin dilindungi kata sandi. [Aspose.PDF untuk Android melalui Java](https://products.aspose.com/pdf/android-java/) memungkinkan Anda membuka dokumen terenkripsi juga. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) dan berikan nama file dan kata sandi sebagai argumen.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat Gambar Thumbnail File PPS di Aplikasi Android" %}}
Setelah mengonversi XSLFO ke PPS, Anda juga dapat membuat gambar mini dari dokumen keluaran Anda. Dengan menggunakan fitur yang kaya [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) Anda dapat membuat gambar mini slide dengan membuat dan instance dari [Presentation]( https://reference.aspose.com/slides/Java/com.aspose.slides/Presentation) kelas. Setelah itu, Anda dapat memperoleh referensi slide yang diinginkan dengan menggunakan ID atau indeksnya dan mendapatkan gambar mini dari slide yang direferensikan pada skala tertentu.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("output.pps");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-potm/" name="XSLFO Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-potx/" name="XSLFO Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-swf/" name="XSLFO Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-ppsm/" name="XSLFO Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-pot/" name="XSLFO Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-ppt/" name="XSLFO Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-otp/" name="XSLFO Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-powerpoint/" name="XSLFO Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-pptm/" name="XSLFO Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-ppsx/" name="XSLFO Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-pps/" name="XSLFO Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xslfo-to-xaml/" name="XSLFO Ke XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}