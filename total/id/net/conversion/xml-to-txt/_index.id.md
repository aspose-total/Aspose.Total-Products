---
title: Konversi XML ke TXT melalui C# API
description: C# API untuk Mengonversi File XML ke TXT tanpa menggunakan Microsoft Excel atau Adobe Reader
url_ignore: /id/net/conversion/xml-to-txt/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: TXT
otherformats: EXCEL XLT XLSB MD XLAM DIF TXT FODS ODS TSV XLTX SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API untuk Merender XML ke TXT" h2="Ekspor File XML ke TXT melalui C# tanpa menggunakan Microsoft<sup>&reg;</sup> Excel atau Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Menggunakan [Aspose.Total for .NET](https://products.aspose.com/total/net/) Anda dapat dengan mudah mengonversi file XML ke TXT dalam aplikasi .NET, C#, ASP.NET, dan VB.NET apa pun. Pertama, dengan menggunakan [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), Anda dapat mengekspor XML ke XLSX. Setelah itu, dengan menggunakan [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, Anda dapat mengonversi XLSX ke TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API untuk Mengonversi XML ke TXT" %}}
1. Buka file XML menggunakan kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konversi XML ke XLSX dengan menggunakan metode [Simpan](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Muat dokumen XLSX dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Simpan dokumen ke format TXT menggunakan metode [Simpan](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) dan setel `Txt` sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Instal dari baris perintah sebagai ```nuget install Aspose.Total``` atau melalui Package Manager Console dari Visual Studio dengan ```Install-Package Aspose.Total```.

Atau, dapatkan penginstal MSI offline atau DLL dalam file ZIP dari [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi XML Terproteksi ke TXT melalui C#" %}}
Jika dokumen XML Anda dilindungi kata sandi, Anda tidak dapat mengubahnya menjadi TXT tanpa kata sandi. Dengan menggunakan API, Anda dapat membuka dokumen yang dilindungi terlebih dahulu menggunakan kata sandi yang valid dan mengonversinya setelahnya. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru kelas [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) dan meneruskan nama file dan sandi sebagai argumen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi File XML ke TXT dengan Watermark melalui C#" %}}
Saat mengonversi file XML ke TXT, Anda juga dapat menambahkan tanda air ke format file TXT keluaran Anda. Untuk menambahkan tanda air, Anda dapat membuat objek Buku Kerja baru dan membuka dokumen XLSX yang dikonversi, memilih Lembar Kerja melalui indeksnya, membuat Bentuk dan menggunakan fungsi AddTextEffect-nya. Setelah itu Anda dapat menyimpan dokumen XLSX Anda sebagai TXT dengan Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}