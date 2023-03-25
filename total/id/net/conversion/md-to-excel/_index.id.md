---
title: Konversi MD ke EXCEL melalui C# API
description: C# API untuk Mengonversi File MD ke EXCEL tanpa menggunakan Microsoft Excel atau Adobe Reader
url_ignore: /id/net/conversion/md-to-excel/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: EXCEL
otherformats: XLT EXCEL XLTM TXT FODS XLAM DIF ODS TSV SXC XLSM XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API untuk Merender MD ke EXCEL" h2="Ekspor File MD ke EXCEL melalui C# tanpa menggunakan Microsoft<sup>&reg;</sup> Excel atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengonversi file MD ke EXCEL dalam aplikasi .NET, C#, ASP.NET, dan VB.NET apa pun. Pertama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor MD ke XLSX. Setelah itu, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, Anda dapat mengonversi XLSX ke EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi MD ke EXCEL" %}}
1. Buka file MD menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi MD ke XLSX dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat dokumen XLSX dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Simpan dokumen ke format EXCEL menggunakan metode [Simpan](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) dan setel `Excel` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi MD Terproteksi ke EXCEL melalui C#" %}}
Jika dokumen MD Anda dilindungi kata sandi, Anda tidak dapat mengubahnya menjadi EXCEL tanpa kata sandi. Dengan menggunakan API, Anda dapat membuka dokumen yang dilindungi terlebih dahulu menggunakan kata sandi yang valid dan mengonversinya setelahnya. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan meneruskan nama file dan sandi sebagai argumen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File MD ke EXCEL dengan Watermark melalui C#" %}}
Saat mengonversi file MD ke EXCEL, Anda juga dapat menambahkan tanda air ke format file EXCEL keluaran Anda. Untuk menambahkan tanda air, Anda dapat membuat objek Buku Kerja baru dan membuka dokumen XLSX yang dikonversi, memilih Lembar Kerja melalui indeksnya, membuat Bentuk dan menggunakan fungsi AddTextEffect-nya. Setelah itu Anda dapat menyimpan dokumen XLSX Anda sebagai EXCEL dengan Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}