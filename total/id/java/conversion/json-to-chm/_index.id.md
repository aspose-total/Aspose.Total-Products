---
title: Konversi Format JSON ke CHM melalui Java
description: Parsing JSON ke CHM di Java tanpa menggunakan Microsoft Word
url_ignore: /id/java/conversion/json-to-chm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: CHM
otherformats: FLATOPC DOCM WORD WORDML ODT RTF DOC MOBI OTT DOTX PCL DOT EPUB PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konversi Format JSON ke CHM melalui Java" h2="Java API lokal untuk mengurai JSON ke CHM tanpa menggunakan Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Dengan menggunakan [Aspose.Total for Java](https://products.aspose.com/total/java/), Anda dapat mengonversi JSON ke CHM di aplikasi Java Anda dalam proses dua langkah. Pertama, dengan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java/) Anda dapat mengurai JSON ke PDF. Pada langkah kedua, Anda dapat mengonversi PDF ke CHM dengan menggunakan Word Processing API [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi Format JSON ke CHM melalui Java" %}}
1. Buat objek [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) baru dan baca data JSON yang valid dari file
2. Impor file JSON ke lembar kerja menggunakan kelas [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) dan [Simpan](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) sebagai PDF
3. Muat dokumen PDF dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format CHM menggunakan [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode
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
Selain itu, API memungkinkan Anda menyetel opsi tata letak untuk JSON saat menguraikan JSON ke CHM menggunakan [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Ini memungkinkan Anda untuk memproses Array sebagai tabel, mengabaikan nol, mengabaikan judul array, mengabaikan judul objek, mengonversi string menjadi angka atau tanggal, mengatur format tanggal dan angka, dan mengatur gaya judul. Semua opsi ini memungkinkan Anda untuk menyajikan data sesuai kebutuhan Anda. Cuplikan kode berikut menunjukkan cara menyetel opsi tata letak.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Setel Tata Letak & Konversi Format JSON ke CHM melalui Java" %}}
Menggunakan API, Anda juga dapat mengurai JSON ke CHM dengan tanda air. Untuk menambahkan tanda air ke dokumen CHM Anda, Anda dapat terlebih dahulu mengonversi file JSON ke PDF dan menambahkan tanda air ke dalamnya. Untuk menambahkan tanda air, muat file PDF yang baru dibuat menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), buat instance TextWatermarkOptions dan atur propertinya, Panggil metode Watermark.setText dan berikan teks watermark & objek TextWatermarkOptions. Setelah menambahkan tanda air, Anda dapat menyimpan dokumen ke CHM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Mengonversi **JSON ke CHM (Compiled HTML Help)** sangat penting untuk membangun **manual bantuan terkompilasi** langsung dari dokumentasi terstruktur. File CHM menggabungkan beberapa topik bantuan menjadi satu sumber daya yang dapat dicari dan diakses secara offline, menjadikannya ideal untuk dukungan perangkat lunak dan manajemen pengetahuan perusahaan. Dengan mengubah JSON menjadi CHM, organisasi dapat menyederhanakan pengiriman dokumentasi, meningkatkan kegunaan, dan memastikan aksesibilitas bahkan tanpa koneksi internet.

{{% blocks/products/pf/agp/feature-section-col title="Kasus Penggunaan Utama" %}}

- **Dokumentasi perangkat lunak** – Kemas panduan teknis ke dalam format yang mudah digunakan.
- **Sistem bantuan offline** – Sampaikan dokumentasi tanpa memerlukan akses internet.
- **Basis pengetahuan perusahaan** – Pusatkan pengetahuan organisasi dalam file bantuan terstruktur.
- **Manual pelatihan** – Distribusikan sumber daya pembelajaran terkompilasi untuk staf atau siswa.
- **Referensi API pengembang** – Konversi definisi JSON terstruktur menjadi referensi offline yang dapat dicari.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Skenario Otomatisasi" %}}

- **Pipa JSON ke CHM** – Otomatisasikan konversi data terstruktur menjadi manual bantuan terkompilasi.
- **Pembuatan file bantuan otomatis** – Hasilkan file CHM langsung dari konten berbasis JSON yang berkembang.
- **Kompilasi data ke dokumentasi** – Ubah dokumentasi JSON terstruktur menjadi sistem bantuan yang dapat diakses.
- **Distribusi pengetahuan offline** – Standarisasi manual CHM untuk pelatihan dan dukungan di seluruh perusahaan.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}