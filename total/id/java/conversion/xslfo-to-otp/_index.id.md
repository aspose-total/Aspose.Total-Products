---
title: Konversi XSLFO ke OTP melalui Java API
description: Java API untuk Mengonversi XSLFO ke OTP tanpa menggunakan Microsoft Word
url: /id/java/conversion/xslfo-to-otp/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: OTP
otherformats: POTX POTM PPTM SWF OTP XAML POT PPSX PPS POWERPOINT PPT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Mengekspor XSLFO ke OTP" h2="Ekspor XSLFO ke OTP melalui Java API lokal tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for Java](https://products.aspose.com/total/java/) Anda dapat dengan mudah mengonversi XSLFO ke OTP dalam aplikasi Java J2SE, J2EE, J2ME. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), Anda dapat mengekspor XSLFO ke PPTX. Setelah itu, dengan menggunakan [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API, Anda dapat mengonversi PPTX ke OTP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API untuk Mengonversi XSLFO ke OTP" %}}
1. Buka file XSLFO menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi XSLFO ke PPTX dengan menggunakan metode [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Simpan dokumen ke format OTP menggunakan metode [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) dan set ` Otp` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan [Aspose.PDF untuk Java](https://docs.aspose.com/pdf/java/installation/) dan [Aspose.Slides untuk Java](https://docs.aspose.com/slides/java/ instalasi/) di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XSLFO file with an instance of Document class
Document document = new Document("template.xslfo");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}Document#Document-java.lang.String-java.lang.String-
Saat memuat format file XSLFO, dokumen Anda mungkin dilindungi kata sandi. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) memungkinkan Anda membuka dokumen terenkripsi juga. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) dan berikan nama file dan kata sandi sebagai argumen.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XSLFO document
Document doc = new Document("input.xslfo", "Your@Password");
// save XSLFO as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Buka File XSLFO Terenkripsi melalui Java" %}}
Setelah mengonversi XSLFO ke OTP, Anda juga dapat menambahkan tipe tampilan standar untuk presentasi Anda. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) menyediakan fasilitas untuk mengatur jenis tampilan untuk presentasi yang dihasilkan ketika dibuka di PowerPoint melalui [ViewProperties](https://apireference.aspose.com/slides/Java/com.aspose.slides/ViewProperties). Properti [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) digunakan untuk menyetel jenis tampilan dengan menggunakan [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) pencacah. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-pps/" name="XSLFO Ke PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-swf/" name="XSLFO Ke SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-potx/" name="XSLFO Ke POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-ppsx/" name="XSLFO Ke PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-potm/" name="XSLFO Ke POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-ppt/" name="XSLFO Ke PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-ppsm/" name="XSLFO Ke PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-xaml/" name="XSLFO Ke XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-otp/" name="XSLFO Ke OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-pptm/" name="XSLFO Ke PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-pot/" name="XSLFO Ke POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-powerpoint/" name="XSLFO Ke POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}