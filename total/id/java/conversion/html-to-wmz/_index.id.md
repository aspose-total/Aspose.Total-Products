---
title: Konversi HTML ke WMZ melalui Java
description: Ekspor file HTML ke WMZ di aplikasi Java Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/java/conversion/html-to-wmz/
family: total
platformtag: net
feature: conversion
informat: HTML
outformat: WMZ
otherformats: TGA PSD WMZ IMAGE EMZ JPEG2000 WMF SVGZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi HTML ke WMZ melalui Java" h2="Ekspor file HTML ke WMZ dalam semua aplikasi Java J2SE, J2EE, J2ME tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi file html ke gambar WMZ di Java dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), Anda dapat mengekspor HTML ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) Image Processing API, Anda dapat merender JPEG ke WMZ. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Ekspor HTML ke WMZ melalui Java" %}}
1. Buka file HTML menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inisialisasi objek kelas dan render HTML ke JPEG dengan menggunakan [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Simpan dokumen ke format WMZ menggunakan [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Konversi HTML ke WMZ dalam Satu File melalui Java" %}}
API juga memungkinkan Anda mengekspor file HTML ke WMZ ke satu file. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen HTML Anda ke satu file TIFF dan setelah itu, Anda dapat mengekspor file TIFF ke WMZ. Anda dapat membuka file input menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan [proses](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metode kelas [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) dan menyimpannya ke format WMZ menggunakan [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi HTML ke WMZ Dengan Tanda Air melalui Java" %}}
Menggunakan API, Anda juga dapat mengekspor file HTML ke WMZ dengan tanda air di dokumen WMZ Anda. Untuk menambahkan tanda air, Anda dapat terlebih dahulu mengonversi HTML ke JPEG dan menambahkan tanda air di dalamnya. Untuk menambahkan tanda air, muat file gambar menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), buat objek dari [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) dan inisialisasi dengan objek Image, buat [Matrix](https://reference.aspose.com/imaging/java/ baru) com.aspose.imaging/Matrix) dan atur terjemahan dan transformasi ke sudut yang diinginkan dan tambahkan tanda air menggunakan [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Setelah menambahkan tanda air pada gambar Anda, Anda dapat menyimpan JPEG sebagai format WMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar HTML ke File WMZ melalui Java" %}}
Menggunakan API, Anda juga dapat memutar gambar WMZ keluaran sesuai kebutuhan Anda. Metode Image.rotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Pustaka menyediakan metode sederhana untuk melakukan operasi kompleks sambil merangkum semua detail jelek. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan kelas [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) dan memanggil Image. metode rotateFlip sambil menentukan [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Mengonversi **HTML ke WMZ (Compressed Windows Metafile)** sangat penting untuk menghasilkan **grafik vektor yang terkompresi** dari halaman web. WMZ mempertahankan skalabilitas dan kemampuan untuk diedit dari grafik vektor sambil secara signifikan mengurangi ukuran file, menjadikannya ideal untuk publikasi ringan, penyimpanan arsip, dan berbagi lintas platform. Dengan mengubah HTML menjadi WMZ, organisasi dapat mengoptimalkan kinerja, menyederhanakan distribusi, dan mempertahankan visual berkualitas tinggi dalam format yang kompak.

{{% blocks/products/pf/agp/feature-section-col title="Kasus Penggunaan Utama" %}}

* **Publikasi ringan** – Sampaikan grafik vektor yang dapat diskalakan dengan ukuran file yang lebih kecil untuk publikasi digital.
* **Kompresi arsip** – Menjaga konten web historis secara efisien tanpa mengorbankan kejelasan visual.
* **Diagram lintas platform** – Bagikan grafik vektor dengan mudah di Windows dan aplikasi yang kompatibel.
* **Visual edukatif** – Buat grafik berkualitas tinggi yang kompak untuk eLearning dan materi instruksional.
* **Alur kerja pelaporan** – Integrasikan diagram dan grafik yang presisi ke dalam laporan bisnis sambil meminimalkan penyimpanan.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skenario Otomatisasi" %}}

* **Pipa kerja HTML ke WMZ** – Otomatis konversi halaman web menjadi grafik vektor yang terkompresi.
* **Kompresi metafile otomatis** – Hasilkan file WMZ yang dioptimalkan secara konsisten di seluruh proyek.
* **Publikasi diagram massal** – Proses beberapa halaman web atau diagram secara bersamaan untuk alur kerja berskala besar.
* **Alur kerja ringan tingkat perusahaan** – Integrasikan generasi WMZ ke dalam sistem publikasi dan arsip organisasi.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}