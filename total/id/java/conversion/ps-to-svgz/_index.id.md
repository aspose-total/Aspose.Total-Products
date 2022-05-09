---
title: Konversi PS ke SVGZ melalui Java
description: Ekspor file PS ke SVGZ di aplikasi Java Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/java/conversion/ps-to-svgz/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SVGZ
otherformats: DXF WMF IMAGE  SVGZ TGA WMZ JPEG2000 PSD EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi PS ke SVGZ melalui Java" h2="Ekspor file PS ke SVGZ dalam semua aplikasi Java J2SE, J2EE, J2ME tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi file ps ke gambar SVGZ di Java dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), Anda dapat mengekspor PS ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, Anda dapat merender JPEG ke SVGZ. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ekspor PS ke SVGZ melalui Java" %}}
1. Buka file PS menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inisialisasi objek kelas dan render PS ke JPEG dengan menggunakan [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Simpan dokumen ke format SVGZ menggunakan [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konversi PS ke SVGZ dalam Satu File melalui Java" %}}
API juga memungkinkan Anda mengekspor file PS ke SVGZ ke satu file. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen PS Anda ke satu file TIFF dan setelah itu, Anda dapat mengekspor file TIFF ke SVGZ. Anda dapat membuka file input menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan [proses](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metode kelas [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) dan menyimpannya ke format SVGZ menggunakan [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi PS ke SVGZ Dengan Tanda Air melalui Java" %}}
Menggunakan API, Anda juga dapat mengekspor file PS ke SVGZ dengan tanda air di dokumen SVGZ Anda. Untuk menambahkan tanda air, Anda dapat terlebih dahulu mengonversi PS ke JPEG dan menambahkan tanda air di dalamnya. Untuk menambahkan tanda air, muat file gambar menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), buat objek dari [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) dan inisialisasi dengan objek Image, buat [Matrix](https://apireference.aspose.com/imaging/java/ baru) com.aspose.imaging/Matrix) dan atur terjemahan dan transformasi ke sudut yang diinginkan dan tambahkan tanda air menggunakan [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Setelah menambahkan tanda air pada gambar Anda, Anda dapat menyimpan JPEG sebagai format SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar PS ke File SVGZ melalui Java" %}}
Menggunakan API, Anda juga dapat memutar gambar SVGZ keluaran sesuai kebutuhan Anda. Metode Image.rotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Pustaka menyediakan metode sederhana untuk melakukan operasi kompleks sambil merangkum semua detail jelek. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) dan memanggil Image. metode rotateFlip sambil menentukan [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-emz/" name="PS Ke EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-tga/" name="PS Ke TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-jpeg2000/" name="PS Ke JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-image/" name="PS Ke IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-psd/" name="PS Ke PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-wmz/" name="PS Ke WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-svgz/" name="PS Ke SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to/" name="PS Ke" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-wmf/" name="PS Ke WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-dxf/" name="PS Ke DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-dicom/" name="PS Ke DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}