---
title: Konversi Format JSON ke POTX di Android melalui Java
description: Parsing JSON ke POTX di Aplikasi Android tanpa menggunakan Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX PPTM POWERPOINT POT POTM ODP PPSM OTP PPS PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Format JSON ke POTX di Android" h2="Parsing format JSON ke POTX di Aplikasi Android tanpa menggunakan Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi format JSON ke POTX di aplikasi Android Anda dalam proses dua langkah. Pertama, dengan menggunakan [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), Anda dapat mengurai JSON ke PPTX. Setelah itu, dengan menggunakan [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/), Anda dapat mengonversi PPTX ke POTX. Kedua API berada di bawah paket [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke POTX di Android" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) baru dan buka file JSON
2. Simpan JSON sebagai PPTX menggunakan [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metode
3. Muat dokumen PPTX dengan menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Simpan dokumen ke format POTX menggunakan metode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal pustaka di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Atur Tata Letak dan Konversi Format JSON ke POTX di Aplikasi Android" %}}
Selanjutnya, API memungkinkan Anda untuk mengurai JSON ke POTX dengan opsi tata letak yang ditentukan. Untuk menentukan opsi tata letak, Anda dapat menggunakan kelas [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Format JSON ke POTX dengan Watermark di Android melalui Java" %}}
Menggunakan API, Anda juga dapat mengonversi JSON ke POTX dengan tanda air. Untuk menambahkan tanda air ke dokumen POTX Anda, pertama-tama Anda dapat mengurai JSON ke PPTX dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PPTX yang baru dibuat menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), loop melalui semua slide, tambahkan teks menggunakan addTextFrame, atur semua opsi yang relevan seperti warna, fillType, dan lainnya dan dapat menyimpan dokumen ke POTX.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}