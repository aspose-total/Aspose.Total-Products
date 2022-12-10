---
title: Android API untuk Mengonversi DOCX ke FODS
description: Konversi DOCX ke FODS di Android melalui Java tanpa menggunakan Microsoft Word atau Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: FODS
otherformats: XLTM XLT XLTX XLS DIF XLSM XLSB EXCEL ODS XLAM XLSX TSV CSV SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi DOCX ke FODS di Aplikasi Android" h2="Ekspor DOCX ke FODS di Android melalui Java tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Anda dapat mengintegrasikan fitur konversi DOCX ke FODS di dalam aplikasi android Anda. Pertama, Anda dapat mengonversi DOCX ke HTML dengan menggunakan API konversi dan manipulasi dokumen yang kaya fitur [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Setelah itu, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), Anda dapat mengonversi HTML ke FODS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengonversi DOCX ke FODS" %}}
1. Buka file DOCX menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Konversi DOCX ke HTML dengan menggunakan [Simpan](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) metode
3. Muat dokumen HTML dengan menggunakan kelas [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Simpan dokumen ke format FODS menggunakan [Simpan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Cells for Android via Java](https://docxs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) dan [Aspose.Words for Android via Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-Android-via-Java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Informasi yang Tidak Digunakan dari Dokumen DOCX di Android melalui Java" %}}Document
Sebelum mengonversi DOCX ke FODS, Anda dapat menghapus informasi yang tidak digunakan dari Dokumen DOCX melalui [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Terkadang Anda mungkin perlu menghapus informasi yang tidak digunakan atau duplikat untuk mengurangi ukuran dokumen keluaran dan waktu pemrosesan. Kelas [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) memungkinkan Anda menentukan opsi untuk pembersihan dokumen. Untuk menghapus gaya duplikat atau hanya gaya atau daftar yang tidak digunakan dari dokumen, Anda dapat menggunakan metode [Pembersihan](https://reference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()). Anda dapat menggunakan [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) dan [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanuoptions#UnusedBuiltinStyles) properti untuk mendeteksi dan menghapus gaya yang ditandai sebagai "tidak digunakan".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-document.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Simpan File FODS untuk Streaming di Android melalui Java" %}}
Setelah mengonversi DOCX ke FODS, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) memungkinkan Anda menyimpan dokumen untuk streaming. Jika Anda perlu menyimpan file ke Stream maka Anda harus membuat objek FileOutputStream dan kemudian [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) file ke objek Stream tersebut dengan memanggil metode penyimpanan [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) obyek.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xltm/" name="DOCX Ke XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xlt/" name="DOCX Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xltx/" name="DOCX Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xls/" name="DOCX Ke XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-dif/" name="DOCX Ke DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xlsm/" name="DOCX Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xlsb/" name="DOCX Ke XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-excel/" name="DOCX Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-ods/" name="DOCX Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xlam/" name="DOCX Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-xlsx/" name="DOCX Ke XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-tsv/" name="DOCX Ke TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-fods/" name="DOCX Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/docx-to-sxc/" name="DOCX Ke SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}