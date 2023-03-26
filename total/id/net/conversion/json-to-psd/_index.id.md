---
title: Konversi Format JSON ke PSD melalui .NET
description: Parsing JSON ke PSD di C# tanpa menggunakan dependensi pihak ketiga
url_ignore: /id/net/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: EMZ WMZ PSD WMF JPEG2000 DXF DICOM IMAGE SVGZ TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format JSON ke PSD melalui C#" h2="C# API untuk mengurai JSON ke PSD tanpa menggunakan dependensi pihak ketiga" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat mengurai JSON ke PSD dalam aplikasi .NET, C#, ASP.NET dan VB.NET dalam dua aplikasi sederhana Langkah. Pertama, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), Anda dapat mengekspor JSON ke JPEG. Setelah itu, dengan menggunakan [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), Anda dapat mengonversi JPEG ke PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke PSD melalui C#" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) baru dan baca data JSON dari file
2. Konversi JSON ke JPEG menggunakan metode [Simpan](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Muat dokumen JPEG dengan menggunakan kelas [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Simpan dokumen ke format PSD menggunakan metode [Simpan](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Atur Tata Letak dan Konversi Format JSON ke PSD melalui C#" %}}
Saat mengurai JSON ke PSD, Anda juga dapat menyetel opsi tata letak untuk JSON menggunakan [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses Array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Parsing Format JSON ke PSD dengan Watermark" %}}
Menggunakan API, Anda juga dapat mengonversi JSON ke PSD dengan tanda air di dokumen PSD Anda. Untuk menambahkan tanda air, pertama-tama Anda dapat merender dokumen JSON Anda ke JPEG dan menambahkan tanda air di dalamnya. Untuk mendemonstrasikan operasi, Anda dapat memuat gambar JPEG yang dikonversi, menambahkan transformasi menggunakan objek kelas Matrix dan menggambar string sebagai tanda air pada permukaan gambar menggunakan [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) class' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Setelah menambahkan tanda air ke dalamnya, Anda dapat menyimpan JPEG sebagai format PSD. Di bawah ini adalah contoh kode yang menunjukkan cara menambahkan tanda air diagonal ke dokumen Anda. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}