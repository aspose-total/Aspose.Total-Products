---
title: Konversi Format WORD ke JSON di Android melalui Java
description: Parsing WORD ke format JSON di Android melalui Java tanpa menggunakan Microsoft Word atau Excel

family: total
platformtag: cpp
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Format WORD ke JSON di Android melalui Java" h2="Rancang aplikasi Android untuk mengekspor WORD ke JSON tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi format WORD ke JSON di Aplikasi Android Anda melalui [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Dengan menggunakan manipulasi dokumen dan API konversi [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), Anda dapat mengekspor WORD ke HTML. Setelah itu, dengan menggunakan [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), Anda dapat mengonversi HTML ke JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format WORD ke JSON di Android" %}}
1. Buka file WORD menggunakan kelas [Wordument](https://reference.aspose.com/words/java/com.aspose.words/Wordument)
2. Konversi WORD ke HTML dengan menggunakan [Simpan](https://reference.aspose.com/words/java/com.aspose.words/Wordument#save(java.lang.String,com.aspose.words.SaveOptions) ) metode
3. Muat dokumen HTML dengan menggunakan kelas [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Simpan dokumen ke format JSON menggunakan [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal pustaka di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Format WORD yang Dilindungi ke JSON di Android melalui Java" %}}
Menggunakan API, Anda juga dapat membuka dokumen yang dilindungi kata sandi. Jika dokumen WORD input Anda dilindungi kata sandi, Anda tidak dapat mengonversinya ke format JSON tanpa menggunakan kata sandi. API memungkinkan Anda untuk membuka dokumen terenkripsi dengan meneruskan kata sandi yang benar di objek LoadOptions. Contoh kode berikut menunjukkan cara membuka dokumen terenkripsi dengan kata sandi.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi WORD ke JSON dalam Jangkauan di Android melalui Java" %}}
Saat Anda mengonversi WORD ke JSON, Anda juga dapat mengatur rentang ke format JSON keluaran Anda. Untuk mengatur rentang, Anda dapat membuka HTML yang dikonversi menggunakan kelas Buku Kerja, membuat Rentang data untuk diekspor menggunakan metode Cells.createRange, memanggil metode JsonUtility.exportRangeToJson dengan referensi Range & ExportRangeToJsonOptions dan menulis data string JSON ke file melalui Metode BufferedWriter.write.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}