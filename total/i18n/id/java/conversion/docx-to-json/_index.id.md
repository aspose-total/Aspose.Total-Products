---
title: Konversi Format DOCX ke JSON melalui Java
description: Konversi format DOCX ke JSON melalui Java tanpa menggunakan Microsoft Word atau Microsoft Excel
url: /id/java/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format DOCX ke JSON melalui Java" h2="On Premise Java API untuk mengonversi DOCX ke JSON tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Mengonversi format DOCX ke JSON melalui [Aspose.Total for Java](https://products.aspose.com/total/java/) adalah proses dua langkah sederhana. Dengan menggunakan API konversi dan manipulasi dokumen yang kaya fitur [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengekspor DOCX ke HTML. Setelah itu, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java/), Anda dapat mengonversi HTML ke JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format DOCX ke JSON melalui Java" %}}
1. Buka file DOCX menggunakan kelas [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Konversi DOCX ke HTML dengan menggunakan [Simpan](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metode
3. Muat dokumen HTML dengan menggunakan kelas [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Simpan dokumen ke format JSON menggunakan [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String.%20com.aspose.cells.SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}
Menggunakan API, Anda juga dapat membuka dokumen yang dilindungi kata sandi. Jika dokumen DOCX masukan Anda dilindungi kata sandi, Anda tidak dapat mengonversinya ke format JSON tanpa menggunakan kata sandi. API memungkinkan Anda untuk membuka dokumen terenkripsi dengan meneruskan kata sandi yang benar di objek LoadOptions. Contoh kode berikut menunjukkan cara mencoba membuka dokumen terenkripsi dengan kata sandi:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversikan Format DOCX yang Dilindungi ke JSON melalui Java" %}}
Saat Anda mengonversi DOCX ke JSON, Anda juga dapat mengatur rentang ke format JSON keluaran Anda. Untuk mengatur rentang, Anda dapat membuka HTML yang dikonversi menggunakan kelas Buku Kerja, membuat Rentang data untuk diekspor menggunakan metode Cells.createRange, memanggil metode JsonUtility.exportRangeToJson dengan referensi Range & ExportRangeToJsonOptions dan menulis data string JSON ke file melalui Metode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xlam/" name="DOCX Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xlt/" name="DOCX Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-csv/" name="DOCX Ke CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xlsx/" name="DOCX Ke XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-fods/" name="DOCX Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xltm/" name="DOCX Ke XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xlsm/" name="DOCX Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xltx/" name="DOCX Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-ods/" name="DOCX Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-xlsb/" name="DOCX Ke XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-excel/" name="DOCX Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-sxc/" name="DOCX Ke SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-tsv/" name="DOCX Ke TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/docx-to-dif/" name="DOCX Ke DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}