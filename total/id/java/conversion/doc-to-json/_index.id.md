---
title: Konversi Format DOC ke JSON melalui Java
description: Konversi format DOC ke JSON melalui Java tanpa menggunakan Microsoft Word atau Microsoft Excel
url_ignore: /id/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format DOC ke JSON melalui Java" h2="On Premise Java API untuk mengonversi DOC ke JSON tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Mengonversi format DOC ke JSON melalui [Aspose.Total for Java](https://products.aspose.com/total/java/) adalah proses dua langkah sederhana. Dengan menggunakan API konversi dan manipulasi dokumen yang kaya fitur [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengekspor DOC ke HTML. Setelah itu, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java/), Anda dapat mengonversi HTML ke JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format DOC ke JSON melalui Java" %}}
1. Buka file DOC menggunakan kelas [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
2. Konversi DOC ke HTML dengan menggunakan [Simpan](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metode
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
Menggunakan API, Anda juga dapat membuka dokumen yang dilindungi kata sandi. Jika dokumen DOC masukan Anda dilindungi kata sandi, Anda tidak dapat mengonversinya ke format JSON tanpa menggunakan kata sandi. API memungkinkan Anda untuk membuka dokumen terenkripsi dengan meneruskan kata sandi yang benar di objek LoadOptions. Contoh kode berikut menunjukkan cara mencoba membuka dokumen terenkripsi dengan kata sandi:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Konversikan Format DOC yang Dilindungi ke JSON melalui Java" %}}
Saat Anda mengonversi DOC ke JSON, Anda juga dapat mengatur rentang ke format JSON keluaran Anda. Untuk mengatur rentang, Anda dapat membuka HTML yang dikonversi menggunakan kelas Buku Kerja, membuat Rentang data untuk diekspor menggunakan metode Cells.createRange, memanggil metode JsonUtility.exportRangeToJson dengan referensi Range & ExportRangeToJsonOptions dan menulis data string JSON ke file melalui Metode BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xlam/" name="DOC Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xlt/" name="DOC Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-csv/" name="DOC Ke CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xlsx/" name="DOC Ke XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-fods/" name="DOC Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xltm/" name="DOC Ke XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xlsm/" name="DOC Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xltx/" name="DOC Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-ods/" name="DOC Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-xlsb/" name="DOC Ke XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-excel/" name="DOC Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-sxc/" name="DOC Ke SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-tsv/" name="DOC Ke TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/doc-to-dif/" name="DOC Ke DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}