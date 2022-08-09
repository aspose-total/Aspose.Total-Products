---
title: Android API untuk Mengonversi RTF ke XLSB
description: Konversi RTF ke XLSB di Android melalui Java tanpa menggunakan Microsoft Word atau Microsoft Excel
url: /id/android-java/conversion/rtf-to-xlsb/
family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSB
otherformats: DIF XLS XLT XLSM XLTX TSV XLAM EXCEL CSV SXC ODS XLSX FODS XLTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi RTF ke XLSB di Aplikasi Android" h2="Ekspor RTF ke XLSB di Android melalui Java tanpa menggunakan Microsoft<sup>&reg;</sup> Word atau Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Anda dapat mengintegrasikan fitur konversi RTF ke XLSB di dalam aplikasi android Anda. Pertama, Anda dapat mengonversi RTF ke HTML dengan menggunakan API konversi dan manipulasi dokumen yang kaya fitur [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Setelah itu, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/), Anda dapat mengonversi HTML ke XLSB. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengonversi RTF ke XLSB" %}}
1. Buka file RTF menggunakan kelas [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
2. Konversi RTF ke HTML dengan menggunakan [Simpan](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,com.aspose.words.SaveOptions) ) metode
3. Muat dokumen HTML dengan menggunakan kelas [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Simpan dokumen ke format XLSB menggunakan [Simpan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Android melalui Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.Cells untuk Android melalui Java](https://rtfs.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) dan [Aspose.Words untuk Android melalui Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-Android-via-Java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Informasi yang Tidak Digunakan dari Dokumen RTF di Android melalui Java" %}}
Sebelum mengonversi RTF ke XLSB, Anda dapat menghapus informasi yang tidak digunakan dari Dokumen RTF melalui [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Terkadang Anda mungkin perlu menghapus informasi yang tidak digunakan atau duplikat untuk mengurangi ukuran dokumen keluaran dan waktu pemrosesan. Kelas [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) memungkinkan Anda menentukan opsi untuk pembersihan dokumen. Untuk menghapus gaya duplikat atau hanya gaya atau daftar yang tidak digunakan dari dokumen, Anda dapat menggunakan metode [Pembersihan](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#cleanup()). Anda dapat menggunakan [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) dan [UnusedBuiltinStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanuoptions#UnusedBuiltinStyles) properti untuk mendeteksi dan menghapus gaya yang ditandai sebagai "tidak digunakan".
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-rtfument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Simpan File XLSB untuk Streaming di Android melalui Java" %}}
Setelah mengonversi RTF ke XLSB, [Aspose.Cells untuk Android melalui Java](https://products.aspose.com/cells/android-java/) memungkinkan Anda menyimpan dokumen untuk streaming. Jika Anda perlu menyimpan file ke Stream maka Anda harus membuat objek FileOutputStream dan kemudian [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) file ke objek Stream tersebut dengan memanggil metode penyimpanan [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) obyek.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-dif/" name="RTF Ke DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xls/" name="RTF Ke XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xlt/" name="RTF Ke XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xlsm/" name="RTF Ke XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xltx/" name="RTF Ke XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-tsv/" name="RTF Ke TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xlam/" name="RTF Ke XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-excel/" name="RTF Ke EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xlsb/" name="RTF Ke XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-sxc/" name="RTF Ke SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-ods/" name="RTF Ke ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xlsx/" name="RTF Ke XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-fods/" name="RTF Ke FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/rtf-to-xltm/" name="RTF Ke XLTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}