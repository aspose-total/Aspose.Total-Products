---
title: Konversi format DOT ke JSON melalui .NET
description: Konversi DOT ke JSON dalam C# tanpa menggunakan Microsoft Excel atau Adobe Reader
url_ignore: /id/net/conversion/dot-to-json/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: JSON
otherformats: XLAM XLS DIF CSV XLTX ODS TSV FODS XLSB XLT XLSX EXCEL XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format DOT ke JSON melalui C#" h2="Parsing DOT ke JSON melalui C# tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat mengonversi format DOT ke JSON dalam aplikasi .NET, C#, ASP.NET, dan VB.NET apa pun dalam dua langkah-langkah sederhana. Pertama, dengan menggunakan [Aspose.Words for .NET](https://products.aspose.com/words/net/), Anda dapat mengekspor DOT ke HTML. Setelah itu, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, Anda dapat mengonversi HTML ke JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format DOT ke JSON melalui C#" %}}
1. Buka file DOT menggunakan kelas [Document](https://reference.aspose.com/words/net/aspose.words/Document)
2. Konversi DOT ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/words/net/aspose.words.Document/save/methods/4)
3. Muat dokumen HTML dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Simpan dokumen ke format JSON menggunakan metode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ubah Format DOT yang Dilindungi ke JSON melalui C#" %}}
Menggunakan API, Anda juga dapat membuka dokumen yang dilindungi kata sandi. Jika dokumen DOT masukan Anda dilindungi kata sandi, Anda tidak dapat mengonversinya ke format JSON tanpa menggunakan kata sandi. API memungkinkan Anda untuk membuka dokumen terenkripsi dengan meneruskan kata sandi yang benar di objek LoadOptions. Contoh kode berikut menunjukkan cara mencoba membuka dokumen terenkripsi dengan kata sandi:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi DOT ke JSON dalam Rentang melalui C#" %}}
Saat Anda mengonversi DOT ke JSON, Anda juga dapat mengatur rentang ke format JSON keluaran Anda. Untuk menyetel rentang, Anda dapat membuka HTML yang dikonversi menggunakan kelas Buku Kerja, mendapatkan CellsCollection dari Lembar Kerja yang berisi data, membuat rentang dari CellsCollection dengan menentukan indeks baris & kolom, dan memanggil metode ExportRangeToJson dengan referensi ke objek Range & ExportRangeToJsonOptions. Terakhir, Anda dapat menyimpan data JSON ke file melalui metode File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}