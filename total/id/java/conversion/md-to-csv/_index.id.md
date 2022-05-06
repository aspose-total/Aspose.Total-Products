---
title: Java API untuk Merender MD ke CSV
description: Ekspor MD ke CSV melalui Java API tanpa menggunakan Microsoft Excel atau Adobe Reader
url_ignore: /id/java/conversion/md-to-csv/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: CSV
otherformats: TSV SXC XLTX FODS DIF XLSB ODS XLSM XLTM EXCEL TXT XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ekspor MD ke CSV melalui Java" h2="Konversikan file MD ke CSV dengan menggunakan Java API lokal dalam aplikasi Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for Java](https://products.aspose.com/total/java/), Anda dapat mengintegrasikan fitur konversi MD ke CSV di aplikasi Java Anda dalam proses dua langkah. Pertama, dengan menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) Anda dapat merender MD ke XLSX. Pada langkah kedua, Anda dapat mengonversi XLSX ke CSV dengan menggunakan API Pemrograman Spreadsheet [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi File MD ke CSV melalui Java" %}}
1. Buka file MD menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi MD ke XLSX dengan menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat dokumen XLSX dengan menggunakan kelas [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Simpan dokumen ke format CSV menggunakan [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan [Aspose.PDF untuk Java](https://docs.aspose.com/pdf/java/installation/) dan [Aspose.Cells untuk Java](https://docs.aspose.com/cells/java/ instalasi/) di pom.xml Anda.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}String-java.lang.String-
Jika dokumen MD Anda dilindungi kata sandi, Anda tidak dapat mengubahnya menjadi CSV tanpa kata sandi. Dengan menggunakan API, Anda dapat membuka dokumen yang dilindungi terlebih dahulu menggunakan kata sandi yang valid dan mengonversinya setelahnya. Untuk membuka file terenkripsi, Anda dapat menginisialisasi instance baru [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- java.lang.String-) dan berikan nama file dan kata sandi sebagai argumen.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversi MD Terproteksi ke CSV melalui Java" %}}
Saat mengonversi file MD ke CSV, Anda juga dapat menambahkan tanda air ke format file CSV keluaran Anda. Untuk menambahkan tanda air, buat Buku Kerja baru untuk membuka file XLSX yang dikonversi. Pilih Lembar Kerja melalui indeksnya, buat Bentuk dan gunakan fungsi addTextEffect, atur warna, transparansi, dan lainnya. Setelah itu Anda dapat menyimpan dokumen XLSX Anda sebagai CSV dengan Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-dif/" name="MD Ke DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xltx/" name="MD Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-md/" name="MD Ke MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-fods/" name="MD Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xltm/" name="MD Ke XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-excel/" name="MD Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xlsm/" name="MD Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xlam/" name="MD Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xlt/" name="MD Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-xlsb/" name="MD Ke XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-ods/" name="MD Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/md-to-sxc/" name="MD Ke SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}