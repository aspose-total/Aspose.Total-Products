---
title: C++ API untuk Mengonversi XPS ke MD
description: Konversi XPS ke MD melalui C++ API tanpa menggunakan Microsoft Excel atau Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MD
otherformats: XLT XLTX DIF ODS XLSM TSV EXCEL XLAM XLSB TXT SXC CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XPS ke MD di Aplikasi C++" h2="Konversi XPS ke MD dalam aplikasi C++ asli tanpa memerlukan Microsoft<sup>&reg;</sup> Excel atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Mengonversi XPS ke MD dalam C++ melalui [Aspose.Total for C++](https://products.aspose.com/total/cpp/) pustaka otomatisasi format file adalah proses dua langkah yang sederhana. Pada langkah pertama, Anda dapat mengekspor XPS ke XLSX dengan menggunakan [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), Setelah itu, dengan menggunakan [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API Pemrograman Spreadsheet, Anda dapat mengonversi XLSX ke MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API untuk Mengonversi XPS ke MD" %}}
1. Buka file XPS menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konversi XPS ke XLSX dengan menggunakan fungsi anggota [Simpan](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Muat dokumen XLSX dengan menggunakan referensi kelas [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Simpan dokumen ke format MD menggunakan fungsi anggota [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total.Cpp``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total.Cpp```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan atau Setel Informasi File XPS melalui C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) juga memungkinkan Anda mendapatkan informasi tentang dokumen XPS dan memungkinkan Anda mengambil keputusan yang tepat sebelum proses konversi. Untuk mendapatkan informasi spesifik file dari file XPS, Anda harus terlebih dahulu memanggil metode [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) dari [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) kelas. Setelah objek DocumentInfo diambil, Anda bisa mendapatkan nilai dari masing-masing properti. Selanjutnya, Anda juga dapat mengatur properti dengan menggunakan metode masing-masing kelas DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Simpan Format File MD ke Streaming melalui C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) memungkinkan penyimpanan format file MD untuk streaming. Untuk menyimpan file ke aliran, buat objek MemoryStream atau FileStream dan simpan file ke objek aliran tersebut dengan memanggil [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metode [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) objek. Tentukan format file yang diinginkan menggunakan enumerasi [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) saat memanggil metode Simpan.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-md-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}