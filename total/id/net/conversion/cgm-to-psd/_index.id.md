---
title: Konversi CGM ke PSD melalui C# API
description: Ekspor CGM ke PSD di aplikasi .NET Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan file CGM ke PSD melalui C#" h2="Ekspor CGM ke PSD dalam aplikasi .NET tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader atau aplikasi pihak ketiga lainnya" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengekspor gambar CGM ke PSD dalam aplikasi .NET apa pun dalam dua langkah sederhana. Pertama-tama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor CGM ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, Anda dapat mengonversi JPEG ke PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan file CGM ke PSD melalui .NET" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inisialisasi objek kelas [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) dan render CGM ke JPEG menggunakan [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Simpan dokumen ke format PSD menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File CGM ke PSD dalam Satu File melalui C#" %}}
Menggunakan API, Anda juga dapat mengonversi file CGM ke PSD menjadi satu file gambar. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen CGM Anda ke satu file TIFF dan setelah itu Anda dapat mengekspor file TIFF ke PSD. Anda dapat membuka file input menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan metode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) dari [TiffDevice](https:// kelas apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
dan simpan ke format PSD menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar File CGM ke PSD melalui C#" %}}
Menggunakan API, Anda juga dapat memutar gambar PSD keluaran sesuai kebutuhan Anda. Metode Image.RotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan metode pabrik yang diekspos oleh kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) dan memanggil Image Metode .RotateFlip sambil menentukan [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke PSD Secara Terprogram : Contoh Penggunaan" %}}
Berkas CGM (Computer Graphics Metafile) digunakan untuk menyimpan informasi grafik vektor, sehingga menjadi ideal untuk membuat grafik statis dan ilustrasi. Namun, ketika bekerja dengan data dinamis, penyunting gambar raster seperti Photoshop diperlukan untuk visualisasi dan penyuntingan gambar.

Konversi berkas CGM ke format PSD diperlukan untuk mengaktifkan potensi desain grafik Anda secara penuh. Konversi ini memungkinkan Anda:

**Aplikasi:**

*   **Desain Logo**: Mengkonversi berkas CGM menjadi logo vektor skala yang dapat digunakan di berbagai medium, termasuk kartu bisnis, billboard, dan website.
*   **Merek dan Identitas**: Menggunakan PSD untuk mengvisualisasikan pedoman merek, membuat identitas visual konsisten, dan mempertahankan konsistensi merek di semua bahan pemasaran.
*   **Ilustrasi dan Karya Seni**: Mengkonversi CGM menjadi ilustrasi yang rumit, menyunting grafik vektor, dan memperbaiki konsep desain.
*   **Desain Cetak**: Menggunakan PSD untuk mengvisualisasikan desain cetak, mengoptimalisasi layout, dan memastikan output gambar berkualitas tinggi untuk berbagai aplikasi cetak.
*   **Aset Desain Grafik**: Mengkonversi CGM menjadi aset desain grafik yang dapat di-edit dan digunakan kembali di proyek lainnya, sehingga menghemat waktu dan usaha.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}