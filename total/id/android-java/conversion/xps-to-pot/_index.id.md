---
title: Ekspor XPS ke POT di Android
description: Android API untuk Mengonversi XPS ke POT tanpa menggunakan Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: POT
otherformats: PPSM OTP PPS PPTM PPT POTM POWERPOINT XAML ODP POTX SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi XPS ke POT di Android melalui Java" h2="Ubah XPS menjadi POT dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi XPS ke POT di dalam aplikasi Android Anda dengan menggunakan dua langkah sederhana. Pada langkah pertama Anda dapat mengekspor XPS ke PPTX dengan menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Setelah itu, dengan menggunakan [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), Anda dapat mengonversi PPTX ke POT. Kedua API berada di bawah paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor XPS ke POT" %}}
1. Buka file XPS menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi XPS ke PPTX dengan menggunakan metode [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Simpan dokumen ke format POT menggunakan metode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) dan set ` Pot` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Slides for Android via Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Buka File XPS yang Dilindungi Kata Sandi di Android melalui Java" %}}
Saat memuat format file XPS, dokumen Anda mungkin dilindungi kata sandi. [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) memungkinkan Anda membuka dokumen terenkripsi juga. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) dan berikan nama file dan kata sandi sebagai argumen.
{{% blocks/products/pf/feature-page-code %}}

```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Buat Gambar Thumbnail File POT di Aplikasi Android" %}}
Setelah mengonversi XPS ke POT, Anda juga dapat membuat gambar mini dari dokumen keluaran Anda. Dengan menggunakan fitur yang kaya [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) Anda dapat membuat gambar mini slide dengan membuat dan instance dari [Presentationreference.aspose.com/slides/Java/com.aspose.slides/Presentation) kelas. Setelah itu, Anda dapat memperoleh referensi slide yang diinginkan dengan menggunakan ID atau indeksnya dan mendapatkan gambar mini dari slide yang direferensikan pada skala tertentu.
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("output.pot");
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}