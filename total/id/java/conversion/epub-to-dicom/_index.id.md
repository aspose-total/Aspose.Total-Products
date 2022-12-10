---
title: Konversi EPUB ke DICOM melalui Java
description: Ekspor file EPUB ke DICOM di aplikasi Java Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/java/conversion/epub-to-dicom/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DICOM
otherformats: PSD WMF TGA WMZ DXF JPEG2000 DICOM IMAGE SVGZ EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi EPUB ke DICOM melalui Java" h2="Ekspor file EPUB ke DICOM dalam semua aplikasi Java J2SE, J2EE, J2ME tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi file epub ke gambar DICOM di Java dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), Anda dapat mengekspor EPUB ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, Anda dapat merender JPEG ke DICOM. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ekspor EPUB ke DICOM melalui Java" %}}
1. Buka file EPUB menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inisialisasi objek kelas dan render EPUB ke JPEG dengan menggunakan [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Simpan dokumen ke format DICOM menggunakan [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konversi EPUB ke DICOM dalam Satu File melalui Java" %}}
API juga memungkinkan Anda mengekspor file EPUB ke DICOM ke satu file. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen EPUB Anda ke satu file TIFF dan setelah itu, Anda dapat mengekspor file TIFF ke DICOM. Anda dapat membuka file input menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan [proses](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metode kelas [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) dan menyimpannya ke format DICOM menggunakan [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi EPUB ke DICOM Dengan Tanda Air melalui Java" %}}
Menggunakan API, Anda juga dapat mengekspor file EPUB ke DICOM dengan tanda air di dokumen DICOM Anda. Untuk menambahkan tanda air, Anda dapat terlebih dahulu mengonversi EPUB ke JPEG dan menambahkan tanda air di dalamnya. Untuk menambahkan tanda air, muat file gambar menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), buat objek dari [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) dan inisialisasi dengan objek Image, buat [Matrix](https://reference.aspose.com/imaging/java/ baru) com.aspose.imaging/Matrix) dan atur terjemahan dan transformasi ke sudut yang diinginkan dan tambahkan tanda air menggunakan [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Setelah menambahkan tanda air pada gambar Anda, Anda dapat menyimpan JPEG sebagai format DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar EPUB ke File DICOM melalui Java" %}}
Menggunakan API, Anda juga dapat memutar gambar DICOM keluaran sesuai kebutuhan Anda. Metode Image.rotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Pustaka menyediakan metode sederhana untuk melakukan operasi kompleks sambil merangkum semua detail jelek. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) dan memanggil Image. metode rotateFlip sambil menentukan [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-emz/" name="EPUB Ke EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-tga/" name="EPUB Ke TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-jpeg2000/" name="EPUB Ke JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-image/" name="EPUB Ke IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-psd/" name="EPUB Ke PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-wmz/" name="EPUB Ke WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-svgz/" name="EPUB Ke SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to/" name="EPUB Ke" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-wmf/" name="EPUB Ke WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-dxf/" name="EPUB Ke DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-dicom/" name="EPUB Ke DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}