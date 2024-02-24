---
title: Konversi Format JSON ke WORDML melalui .NET
description: Parsing JSON ke WORDML di C# tanpa menggunakan Microsoft Word
url_ignore: /id/net/conversion/json-to-wordml/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WORDML
otherformats: PS OTT FLATOPC DOCM EPUB RTF DOTX ODT PCL WORDML DOC WORD DOT MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan Format JSON ke WORDML melalui C#" h2="C# API untuk mengurai JSON ke WORDML tanpa menggunakan Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat mengurai JSON ke WORDML dalam aplikasi .NET, C#, ASP.NET dan VB.NET dalam dua aplikasi sederhana Langkah. Pertama, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), Anda dapat mengekspor JSON ke PDF. Setelah itu, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat mengonversi PDF ke WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan Format JSON ke WORDML melalui C#" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook) baru dan baca data JSON yang valid dari file
2. Impor file JSON ke lembar kerja menggunakan kelas [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) dan [Simpan](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) sebagai PDF
3. Muat dokumen PDF dengan menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Simpan dokumen ke format WORDML menggunakan metode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Setel Tata Letak dan Konversi Format JSON ke WORDML melalui C#" %}}
Saat menguraikan JSON ke WORDML, Anda juga dapat menyetel opsi tata letak untuk JSON menggunakan [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses Array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Parsing Format JSON ke WORDML dengan Watermark" %}}
Menggunakan API, Anda juga dapat mengonversi JSON ke WORDML dengan tanda air. Untuk menambahkan tanda air ke dokumen WORDML Anda, pertama-tama Anda dapat mengurai file JSON ke PDF dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PDF yang baru dibuat menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/document), buat instance TextWatermarkOptions dan atur propertinya, Panggil metode Watermark.SetText dan berikan teks watermark & objek TextWatermarkOptions. Setelah menambahkan tanda air, Anda dapat menyimpan dokumen ke WORDML. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}