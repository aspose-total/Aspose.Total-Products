---
title: Konversi CGM ke JPEG2000 melalui C# API
description: Ekspor CGM ke JPEG2000 di aplikasi .NET Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan file CGM ke JPEG2000 melalui C#" h2="Ekspor CGM ke JPEG2000 dalam aplikasi .NET tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader atau aplikasi pihak ketiga lainnya" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengekspor gambar CGM ke JPEG2000 dalam aplikasi .NET apa pun dalam dua langkah sederhana. Pertama-tama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor CGM ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, Anda dapat mengonversi JPEG ke JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan file CGM ke JPEG2000 melalui .NET" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inisialisasi objek kelas [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) dan render CGM ke JPEG menggunakan [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Simpan dokumen ke format JPEG2000 menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File CGM ke JPEG2000 dalam Satu File melalui C#" %}}
Menggunakan API, Anda juga dapat mengonversi file CGM ke JPEG2000 menjadi satu file gambar. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen CGM Anda ke satu file TIFF dan setelah itu Anda dapat mengekspor file TIFF ke JPEG2000. Anda dapat membuka file input menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan metode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) dari [TiffDevice](https:// kelas apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
dan simpan ke format JPEG2000 menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar File CGM ke JPEG2000 melalui C#" %}}
Menggunakan API, Anda juga dapat memutar gambar JPEG2000 keluaran sesuai kebutuhan Anda. Metode Image.RotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan metode pabrik yang diekspos oleh kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) dan memanggil Image Metode .RotateFlip sambil menentukan [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke JPEG2000 Secara Terprogram : Contoh Penggunaan" %}}
CGM (Computer Graphics Metafile) adalah file yang digunakan untuk menyimpan informasi tentang grafik vektor, sehingga ideal untuk membuat grafik statis dan ilustrasi. Namun, ketika bekerja dengan data dinamis, gambar JPEG 2000 menjadi penting karena memberikan kompresi optimal dan kualitas yang terbaik.

Konversi file CGM ke format JPEG 2000 memungkinkan penggunaan maksimal kemampuan kompresi dan kualitas gambar Anda. Ini memungkinkan Anda untuk menggunakan format gambar yang lebih efisien, baik untuk mengoptimalkan grafik web maupun memastikan konsistensi branding di semua bahan marketing.

Berikut adalah beberapa aplikasi yang dapat dilakukan dengan mengkonversi file CGM ke JPEG 2000:

1. **Edit Gambar dengan Kualitas Tinggi**: Convert CGM files to create high-quality images, optimize graphics for web use, and ensure consistent branding across all marketing materials.
2. **Aplikasi Arsip dan Penjagaan**: Use JPEG 2000 to compress and store large image datasets, ensuring long-term preservation and accessibility of valuable visual content.
3. **Imaging Medis dan Diagnostika**: Convert CGM files to create detailed, high-quality medical images for diagnostic purposes, reducing errors and improving patient outcomes.
4. **Penelitian Ilmiah dan Publikasi**: Use JPEG 2000 to compress and publish large datasets of scientific images, facilitating global collaboration and knowledge sharing.
5. **Perpustakaan Digital dan Arsip**: Convert CGM files to create scalable, high-quality digital libraries, preserving cultural heritage and historical artifacts for future generations.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}