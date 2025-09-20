---
title: Konversi Format JSON ke ODT melalui Java
description: Parsing JSON ke ODT di Java tanpa menggunakan Microsoft Word
url_ignore: /id/java/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: WORDML EPUB WORD RTF DOT ODT PCL PS DOCM DOC OTT MOBI FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format JSON ke ODT melalui Java" h2="Java API lokal untuk mengurai JSON ke ODT tanpa menggunakan Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for Java](https://products.aspose.com/total/java/), Anda dapat mengonversi JSON ke ODT di aplikasi Java Anda dalam proses dua langkah. Pertama, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Anda dapat mengurai JSON ke PDF. Pada langkah kedua, Anda dapat mengonversi PDF ke ODT dengan menggunakan Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke ODT melalui Java" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) baru dan baca data JSON yang valid dari file
2. Impor file JSON ke lembar kerja menggunakan kelas [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) dan [Simpan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) sebagai PDF
3. Muat dokumen PDF dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format ODT menggunakan [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}
Selain itu, API memungkinkan Anda menyetel opsi tata letak untuk JSON saat menguraikan JSON ke ODT menggunakan [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses Array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Setel Tata Letak & Konversi Format JSON ke ODT melalui Java" %}}
Menggunakan API, Anda juga dapat mengurai JSON ke ODT dengan tanda air. Untuk menambahkan tanda air ke dokumen ODT Anda, Anda dapat terlebih dahulu mengonversi file JSON ke PDF dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PDF yang baru dibuat menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), buat instance TextWatermarkOptions dan atur propertinya, Panggil metode Watermark.setText dan berikan teks watermark & objek TextWatermarkOptions. Setelah menambahkan tanda air, Anda dapat menyimpan dokumen ke ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Mengonversi **JSON ke ODT** sangat penting untuk menghasilkan file teks **OpenDocument** dari kumpulan data terstruktur. ODT, format asli untuk LibreOffice dan OpenOffice, memastikan aksesibilitas jangka panjang, kompatibilitas open-source, dan interoperabilitas lintas platform. Dengan mengubah JSON menjadi ODT, organisasi dapat mengotomatisasi pembuatan dokumen teks profesional berbasis data tanpa pengeditan manual.

{{% blocks/products/pf/agp/feature-section-col title="Kasus Penggunaan Utama" %}}

- **Dokumen pemerintah** – Hasilkan dokumen yang sesuai, standar untuk administrasi publik.
- **Alur kerja kantor open-source** – Integrasikan data JSON dengan lingkungan LibreOffice dan Apache OpenOffice.
- **Makalah akademis** – Hasilkan laporan penelitian dan publikasi dari kumpulan data terstruktur.
- **Kontrak bisnis** – Otomatisasikan penyusunan perjanjian dan pembuatan kontrak dari catatan JSON.
- **Surat berbasis data** – Buat korespondensi terstruktur yang dipersonalisasi dalam skala besar.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skenario Otomatisasi" %}}

- **Pipa JSON-ke-ODT** – Otomatisasikan transformasi data terstruktur menjadi dokumen ODT yang dapat diedit.
- **Generasi ODT otomatis** – Kurangi upaya manual dengan menghasilkan file teks siap pakai langsung dari JSON.
- **Standarisasi JSON-ke-OpenDocument** – Pastikan kepatuhan dengan standar terbuka untuk berbagi dokumen.
- **Alur kerja dokumentasi lintas platform** – Aktifkan interoperabilitas yang lancar di seluruh sistem perusahaan dan akademis.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}