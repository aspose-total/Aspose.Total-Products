---
title: Konversi format PPT ke JSON melalui .NET
description: Konversi PPT ke JSON di C# tanpa menggunakan Microsoft Excel atau Powerpoint
url_ignore: /id/net/conversion/ppt-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversikan PPT ke Format JSON melalui C#" h2="Ekspor PPT ke JSON melalui C# tanpa menggunakan Microsoft<sup>&reg;</sup> Excel atau PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat mengonversi format PPT ke JSON dalam aplikasi .NET, C#, ASP.NET, dan VB.NET apa pun dalam dua langkah-langkah sederhana. Pertama, dengan menggunakan [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), Anda dapat mengekspor PPT ke HTML. Setelah itu, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, Anda dapat mengonversi HTML ke JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversikan PPT ke Format JSON melalui C#" %}}
1. Buka file PPT menggunakan kelas [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Konversi PPT ke HTML dengan menggunakan metode [Simpan](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Muat dokumen HTML dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Simpan dokumen ke format JSON menggunakan metode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversikan PPT Terproteksi ke Format JSON melalui C#" %}}
Menggunakan API, Anda juga dapat membuka dokumen yang dilindungi kata sandi. Jika dokumen PPT masukan Anda dilindungi kata sandi, Anda tidak dapat mengonversinya ke format JSON tanpa menggunakan kata sandi. API memungkinkan Anda untuk membuka dokumen terenkripsi dengan meneruskan kata sandi yang benar di objek LoadOptions. Contoh kode berikut menunjukkan cara membuka dokumen terenkripsi dengan kata sandi.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PPT ke JSON dalam Rentang melalui C#" %}}
Saat Anda mengonversi PPT ke JSON, Anda juga dapat mengatur rentang ke format JSON keluaran Anda. Untuk menyetel rentang, Anda dapat membuka HTML yang dikonversi menggunakan kelas Buku Kerja, mendapatkan CellsCollection dari Lembar Kerja yang berisi data, membuat rentang dari CellsCollection dengan menentukan indeks baris & kolom, dan memanggil metode ExportRangeToJson dengan referensi ke objek Range & ExportRangeToJsonOptions. Terakhir, Anda dapat menyimpan data JSON ke file melalui metode File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}