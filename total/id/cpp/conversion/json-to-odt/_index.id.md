---
title: Konversi Format JSON ke ODT melalui C++
description: C++ API t0 Parsing JSON ke ODT tanpa menggunakan Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODT
otherformats: MOBI DOCM FLATOPC CHM WORD DOTX WORDML PCL EPUB OTT PS RTF DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Format JSON ke ODT melalui C++" h2="Parsing JSON ke ODT dalam aplikasi C++ tanpa menggunakan Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for C++](https://products.aspose.com/total/cpp/) Anda dapat mengurai JSON ke ODT dalam aplikasi C++ Anda dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), Anda dapat mengekspor JSON ke PDF. Setelah itu, dengan menggunakan [Aspose.Words for C++](https://products.aspose.com/words/cppp/), Anda dapat mengonversi PDF ke ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke ODT di C++" %}}
1. Buat objek [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) baru dan baca data JSON yang valid dari file
2. Simpan JSON sebagai PDF menggunakan metode [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Muat dokumen PDF dengan menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Simpan dokumen ke format ODT menggunakan metode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Setel Tata Letak & Konversi Format JSON ke ODT di C++" %}}
Saat menguraikan JSON ke ODT, Anda juga dapat mengatur ukuran baris dan kolom dengan memuat JSON dengan kelas [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Jika Anda perlu mengatur tinggi baris yang sama untuk semua baris di lembar kerja, Anda dapat melakukannya dengan menggunakan [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metode koleksi [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Demikian pula, untuk menyetel lebar kolom yang sama untuk semua kolom di lembar kerja, gunakan metode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) dari koleksi ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Format JSON ke ODT dengan Tanda Air di C++" %}}
Menggunakan API, Anda juga dapat mengurai JSON ke ODT dengan tanda air. Untuk menambahkan tanda air ke dokumen ODT Anda, pertama-tama Anda dapat mengonversi JSON ke PDF dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PDF yang baru dibuat menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), atur properti yang berbeda untuk tanda air teks,
panggil metode SetText dan berikan teks watermark & objek TextWatermarkOptions. Setelah menambahkan tanda air, Anda dapat menyimpan dokumen ke ODT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}