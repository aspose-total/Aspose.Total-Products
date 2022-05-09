---
title: Konversi MHTML ke EMZ melalui Java
description: Ekspor file MHTML ke EMZ di aplikasi Java Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/java/conversion/mhtml-to-emz/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: EMZ
otherformats: IMAGE WMF SVGZ JPEG2000 EMZ TGA DXF WMZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi MHTML ke EMZ melalui Java" h2="Ekspor file MHTML ke EMZ dalam semua aplikasi Java J2SE, J2EE, J2ME tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi file mhtml ke gambar EMZ di Java dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), Anda dapat mengekspor MHTML ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, Anda dapat merender JPEG ke EMZ. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ekspor MHTML ke EMZ melalui Java" %}}
1. Buka file MHTML menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inisialisasi objek kelas dan render MHTML ke JPEG dengan menggunakan [Process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Simpan dokumen ke format EMZ menggunakan [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konversi MHTML ke EMZ dalam Satu File melalui Java" %}}
API juga memungkinkan Anda mengekspor file MHTML ke EMZ ke satu file. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen MHTML Anda ke satu file TIFF dan setelah itu, Anda dapat mengekspor file TIFF ke EMZ. Anda dapat membuka file input menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan [proses](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metode kelas [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) dan menyimpannya ke format EMZ menggunakan [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi MHTML ke EMZ Dengan Tanda Air melalui Java" %}}
Menggunakan API, Anda juga dapat mengekspor file MHTML ke EMZ dengan tanda air di dokumen EMZ Anda. Untuk menambahkan tanda air, Anda dapat terlebih dahulu mengonversi MHTML ke JPEG dan menambahkan tanda air di dalamnya. Untuk menambahkan tanda air, muat file gambar menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), buat objek dari [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) dan inisialisasi dengan objek Image, buat [Matrix](https://apireference.aspose.com/imaging/java/ baru) com.aspose.imaging/Matrix) dan atur terjemahan dan transformasi ke sudut yang diinginkan dan tambahkan tanda air menggunakan [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Setelah menambahkan tanda air pada gambar Anda, Anda dapat menyimpan JPEG sebagai format EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar MHTML ke File EMZ melalui Java" %}}
Menggunakan API, Anda juga dapat memutar gambar EMZ keluaran sesuai kebutuhan Anda. Metode Image.rotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Pustaka menyediakan metode sederhana untuk melakukan operasi kompleks sambil merangkum semua detail jelek. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan kelas [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) dan memanggil Image. metode rotateFlip sambil menentukan [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-emz/" name="MHTML Ke EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-tga/" name="MHTML Ke TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-jpeg2000/" name="MHTML Ke JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-image/" name="MHTML Ke IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-psd/" name="MHTML Ke PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-wmz/" name="MHTML Ke WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-svgz/" name="MHTML Ke SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to/" name="MHTML Ke" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-wmf/" name="MHTML Ke WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-dxf/" name="MHTML Ke DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/mhtml-to-dicom/" name="MHTML Ke DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}