---
title: Konversi CGM ke DXF melalui C# API
description: Ekspor CGM ke DXF di aplikasi .NET Anda tanpa menggunakan aplikasi pihak ketiga
url_ignore: /id/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan file CGM ke DXF melalui C#" h2="Ekspor CGM ke DXF dalam aplikasi .NET tanpa menggunakan Adobe<sup>&reg;</sup> Acrobat Reader atau aplikasi pihak ketiga lainnya" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengekspor gambar CGM ke DXF dalam aplikasi .NET apa pun dalam dua langkah sederhana. Pertama-tama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor CGM ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) Image Processing API, Anda dapat mengonversi JPEG ke DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan file CGM ke DXF melalui .NET" %}}
1. Buka file CGM menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Inisialisasi objek kelas [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) dan render CGM ke JPEG menggunakan [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metode
3. Muat file JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Simpan dokumen ke format DXF menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File CGM ke DXF dalam Satu File melalui C#" %}}
Menggunakan API, Anda juga dapat mengonversi file CGM ke DXF menjadi satu file gambar. Untuk mengonversi semua halaman, pertama-tama Anda dapat merender dokumen CGM Anda ke satu file TIFF dan setelah itu Anda dapat mengekspor file TIFF ke DXF. Anda dapat membuka file input menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan membuat objek perangkat Resolution, TiffSettings, & TIFF. Anda bisa mendapatkan satu gambar TIFF menggunakan metode [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) dari [TiffDevice](https:// kelas apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Terakhir, Anda dapat memuat file TIFF menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
dan simpan ke format DXF menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi & Putar File CGM ke DXF melalui C#" %}}
Menggunakan API, Anda juga dapat memutar gambar DXF keluaran sesuai kebutuhan Anda. Metode Image.RotateFlip dapat digunakan untuk memutar gambar sebesar 90/180/270 derajat dan membalik gambar secara horizontal atau vertikal. Anda dapat menentukan jenis rotasi dan flip untuk diterapkan pada gambar. Untuk memutar dan membalik gambar, Anda dapat memuat gambar JPEG yang dikonversi menggunakan metode pabrik yang diekspos oleh kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) dan memanggil Image Metode .RotateFlip sambil menentukan [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype) yang sesuai. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Mengubah File CGM ke DXF Secara Terprogram : Contoh Penggunaan" %}}
Mengkonversi file CGM (Computer Graphics Metafile) ke DXF (Drawing Exchange Format) adalah penting untuk mengaktifkan potensi penuh dalam kapasitas desain CAD dan manufaktur Anda. Konversi ini memungkinkan Anda:

**Apa yang bisa dilakukan:**

* **Integrasi Desain CAD**: Mengkonversi file CGM ke DXF agar dapat disintegrasikan dengan software CAD, sehingga kolaborasi desain dan pertukaran data menjadi lebih mudah.  
* **Optimasi Proses Manufaktur**: Menggunakan file DXF untuk memperbaiki proses manufaktur, mengurangi biaya produksi, dan meningkatkan kualitas produk.  
* **Desain untuk Manufaktur (DFM)**: Mengkonversi file CGM agar dapat dibuat desain DFM, mempertimbangkan aspek seperti sifat bahan, persyaratan alat potong, dan batasan assembling.  
* **Pertukaran Data dengan Mesin CNC**: Menggunakan file DXF untuk menyebarkan data desain ke mesin CNC, sehingga proses pemotongan dan fabrikasi menjadi lebih akurat.  
* **Pengembangan Produk dan Pengujian**: Mengkonversi file CGM agar dapat dibuat prototipe, diuji desain, dan divalidasi fungsi produk sebelum masuk produksi.

Catatan: Saya telah menggunakan pola yang sama seperti yang digambarkan untuk mengkonversi format sumber :CGM ke target format:Dxf.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}