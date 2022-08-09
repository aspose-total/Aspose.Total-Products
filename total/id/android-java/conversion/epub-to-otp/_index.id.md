---
title: Ekspor EPUB ke OTP di Android
description: Android API untuk Mengonversi EPUB ke OTP tanpa menggunakan Microsoft Word
url: /id/android-java/conversion/epub-to-otp/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: OTP
otherformats: PPSM PPT PPS POTM POT POWERPOINT POTX PPTM SWF ODP PPSX XAML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi EPUB ke OTP di Android melalui Java" h2="Ubah EPUB menjadi OTP dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi EPUB ke OTP di dalam aplikasi Android Anda dengan menggunakan dua langkah sederhana. Pada langkah pertama Anda dapat mengekspor EPUB ke PPTX dengan menggunakan [Aspose.PDF untuk Android melalui Java](https://products.aspose.com/pdf/android-java/). Setelah itu, dengan menggunakan [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), Anda dapat mengonversi PPTX ke OTP. Kedua API berada di bawah paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor EPUB ke OTP" %}}
1. Buka file EPUB menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi EPUB ke PPTX dengan menggunakan metode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Simpan dokumen ke format OTP menggunakan metode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) dan set ` Otp` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Android melalui Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF untuk Android melalui Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Slides untuk Android melalui Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Buka File EPUB yang Dilindungi Kata Sandi di Android melalui Java" %}}
Saat memuat format file EPUB, dokumen Anda mungkin dilindungi kata sandi. [Aspose.PDF untuk Android melalui Java](https://products.aspose.com/pdf/android-java/) memungkinkan Anda membuka dokumen terenkripsi juga. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) dan berikan nama file dan kata sandi sebagai argumen.
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Buat Gambar Thumbnail File OTP di Aplikasi Android" %}}
Setelah mengonversi EPUB ke OTP, Anda juga dapat membuat gambar mini dari dokumen keluaran Anda. Dengan menggunakan fitur yang kaya [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) Anda dapat membuat gambar mini slide dengan membuat dan instance dari [Presentation]( https://reference.aspose.com/slides/Java/com.aspose.slides/Presentation) kelas. Setelah itu, Anda dapat memperoleh referensi slide yang diinginkan dengan menggunakan ID atau indeksnya dan mendapatkan gambar mini dari slide yang direferensikan pada skala tertentu.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a OTP file
Presentation presentation = new Presentation("output.otp");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-ppsm/" name="EPUB Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-ppt/" name="EPUB Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-pps/" name="EPUB Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-potm/" name="EPUB Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-pot/" name="EPUB Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-powerpoint/" name="EPUB Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-potx/" name="EPUB Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-pptm/" name="EPUB Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-swf/" name="EPUB Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-otp/" name="EPUB Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-ppsx/" name="EPUB Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-xaml/" name="EPUB Ke XAML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}