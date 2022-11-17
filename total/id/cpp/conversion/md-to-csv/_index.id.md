---
title: C++ API untuk Mengonversi MD ke CSV
description: Konversi MD ke CSV melalui C++ API tanpa menggunakan Microsoft Excel atau Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: CSV
otherformats: XLAM XLSM ODS EXCEL TSV DIF XLTX FODS XLT XLTM SXC TXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render MD ke CSV di Aplikasi C++" h2="Konversi MD ke CSV dalam aplikasi C++ asli tanpa memerlukan Microsoft<sup>&reg;</sup> Excel atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mengonversi MD ke CSV dalam C++ melalui [Aspose.Total for C++](https://products.aspose.com/total/cpp/) pustaka otomatisasi format file adalah proses dua langkah yang sederhana. Pada langkah pertama, Anda dapat mengekspor MD ke XLSX dengan menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), Setelah itu, dengan menggunakan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API Pemrograman Spreadsheet, Anda dapat mengonversi XLSX ke CSV. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi MD ke CSV" %}}
1. Buka file MD menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi MD ke XLSX dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Muat dokumen XLSX dengan menggunakan referensi kelas [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Simpan dokumen ke format CSV menggunakan fungsi anggota [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan atau Setel Informasi File MD melalui C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) juga memungkinkan Anda mendapatkan informasi tentang dokumen MD dan memungkinkan Anda mengambil keputusan yang tepat sebelum proses konversi. Untuk mendapatkan informasi spesifik file dari file MD, Anda harus terlebih dahulu memanggil metode [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) dari [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) kelas. Setelah objek DocumentInfo diambil, Anda bisa mendapatkan nilai dari masing-masing properti. Selanjutnya, Anda juga dapat mengatur properti dengan menggunakan metode masing-masing kelas DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Simpan Format File CSV ke Streaming melalui C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) memungkinkan penyimpanan format file CSV untuk streaming. Untuk menyimpan file ke aliran, buat objek MemoryStream atau FileStream dan simpan file ke objek aliran tersebut dengan memanggil [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metode [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) objek. Tentukan format file yang diinginkan menggunakan enumerasi [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) saat memanggil metode Simpan.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-csv-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xlam/" name="MD Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xlsm/" name="MD Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-ods/" name="MD Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-excel/" name="MD Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-tsv/" name="MD Ke TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-dif/" name="MD Ke DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xltx/" name="MD Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-fods/" name="MD Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xlt/" name="MD Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-xltm/" name="MD Ke XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-sxc/" name="MD Ke SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/cpp/conversion/md-to-txt/" name="MD Ke TXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}