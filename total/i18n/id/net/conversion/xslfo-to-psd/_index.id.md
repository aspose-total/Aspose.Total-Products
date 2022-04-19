---
title: Konversi XSLFO ke PSD melalui C# API
description: Ekspor XSLFO ke PSD di aplikasi .NET Anda tanpa menggunakan aplikasi pihak ketiga
url: /id/net/conversion/xslfo-to-psd/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: PSD
otherformats: PSD EMZ DXF JPEG2000 WMZ TGA SVGZ IMAGE  WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan file XSLFO ke PSD melalui C#" h2="Ekspor XSLFO ke PSD dalam aplikasi .NET tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader atau aplikasi pihak ketiga lainnya" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengekspor gambar XSLFO ke PSD dalam aplikasi .NET apa pun dalam dua langkah sederhana. Pertama-tama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor XSLFO ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, Anda dapat mengonversi JPEG ke PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan file XSLFO ke PSD melalui .NET" %}}
1. Buka file XSLFO menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. Inisialisasi objek kelas [JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) dan render XSLFO ke JPEG menggunakan [Process](https://apireference.aspose. com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. Simpan dokumen ke format PSD menggunakan metode [Simpan](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File XSLFO ke PSD dalam Satu File melalui C#" %}}
Menggunakan API, Anda juga dapat mengonversi file XSLFO ke PSD menjadi satu file gambar. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen XSLFO Anda ke satu file TIFF dan setelah itu Anda dapat mengekspor file TIFF ke PSD. Anda dapat membuka file input menggunakan kelas [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan metode [Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) dari [TiffDevice](https:// kelas apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
dan simpan ke format PSD menggunakan metode [Simpan](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar File XSLFO ke PSD melalui C#" %}}
Menggunakan API, Anda juga dapat memutar gambar PSD keluaran sesuai kebutuhan Anda. Metode Image.RotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan metode pabrik yang diekspos oleh kelas [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) dan memanggil Image Metode .RotateFlip sambil menentukan [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-emz/" name="XSLFO Ke EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-tga/" name="XSLFO Ke TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-jpeg2000/" name="XSLFO Ke JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-image/" name="XSLFO Ke IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-psd/" name="XSLFO Ke PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-wmz/" name="XSLFO Ke WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-svgz/" name="XSLFO Ke SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to/" name="XSLFO Ke" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-wmf/" name="XSLFO Ke WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-dxf/" name="XSLFO Ke DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xslfo-to-dicom/" name="XSLFO Ke DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}