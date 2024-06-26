---
title: Konversi Format JSON ke OTP melalui C++
description: Parsing JSON ke OTP di C++ tanpa menggunakan Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: OTP
otherformats: PPSX PPS POTM PPT POT PPTM ODP POTX PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Format JSON ke OTP melalui C++" h2="C++ API untuk mengurai JSON ke OTP tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi JSON ke OTP dalam aplikasi C++ apa pun dalam dua langkah sederhana. Pertama, dengan menggunakan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), Anda dapat mengurai JSON ke PPTX. Setelah itu, dengan menggunakan [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), Anda dapat mengonversi PPTX ke OTP. Kedua API berada di bawah paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke OTP melalui C++" %}}
1. Buat objek [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) baru dan baca data JSON yang valid dari file
2. Simpan JSON sebagai PPTX menggunakan metode [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Simpan dokumen ke format OTP menggunakan metode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Atur Tata Letak dan Konversi Format JSON ke OTP melalui C++" %}}
Saat menguraikan JSON ke OTP, Anda juga dapat mengatur ukuran baris dan kolom dengan memuat JSON dengan kelas [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Jika Anda perlu mengatur tinggi baris yang sama untuk semua baris di lembar kerja, Anda dapat melakukannya dengan menggunakan [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metode koleksi [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Demikian pula, untuk menyetel lebar kolom yang sama untuk semua kolom di lembar kerja, gunakan metode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) dari koleksi ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Format JSON ke OTP dengan Watermark di C++" %}}
Menggunakan API, Anda juga dapat mengonversi JSON ke OTP dengan tanda air. Untuk menambahkan tanda air ke dokumen OTP Anda, pertama-tama Anda dapat mengurai JSON ke PPTX dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PPTX yang baru dibuat menggunakan kelas [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), dapatkan slide pertama, Tambahkan AutoShape tipe Rectangle, menambahkan TextFrame ke Rectangle, membuat objek Paragraph untuk bingkai teks, membuat objek Porsi untuk paragraf, menambahkan watermark menggunakan set_Text() dan, dapat menyimpan dokumen ke OTP.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}