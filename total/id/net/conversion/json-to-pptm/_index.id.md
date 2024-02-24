---
title: Konversi Format JSON ke PPTM melalui .NET
description: Parsing JSON ke PPTM dalam C# tanpa menggunakan Microsoft PowerPoint
url_ignore: /id/net/conversion/json-to-pptm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPTM
otherformats: POWERPOINT POTM OTP POT PPS PPT PPSM POTX PPTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format JSON ke PPTM melalui C#" h2="C# API untuk mengurai JSON ke PPTM tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi JSON ke PPTM dalam aplikasi .NET, C#, ASP.NET, dan VB.NET apa pun dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), Anda dapat mengurai JSON ke PPTX. Setelah itu, dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengonversi PPTX ke PPTM. Kedua API berada di bawah paket [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke PPTM melalui C#" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) baru dan baca data JSON yang valid dari file
2. Impor file JSON ke lembar kerja menggunakan kelas [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) dan [Simpan](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) sebagai PPTX
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Simpan dokumen ke format PPTM menggunakan metode [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
C#
{{% blocks/products/pf/feature-page-section  h2="Atur Tata Letak dan Konversi Format JSON ke PPTM melalui C#" %}}
Saat menguraikan JSON ke PPTM, Anda juga dapat menyetel opsi tata letak untuk format JSON menggunakan [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Format JSON ke PPTM dengan Tanda Air" %}}
Menggunakan API, Anda juga dapat mengonversi JSON ke PPTM dengan tanda air. Untuk menambahkan tanda air ke dokumen PPTM Anda, pertama-tama Anda dapat mengurai JSON ke PPTX dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PPTX yang baru dibuat menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation), pilih presentasi master, tambahkan jenis bentuk menggunakan AddAutoShape, dan tambahkan teks watermark menggunakan AddTextFrame. Setelah menambahkan tanda air, Anda dapat menyimpan dokumen ke PPTM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}