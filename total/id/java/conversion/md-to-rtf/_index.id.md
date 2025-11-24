---
title: Java API untuk Mengekspor MD ke RTF
description: Konversi MD ke RTF menggunakan API Java di tempat
url_ignore: /id/java/conversion/md-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: RTF
otherformats: DOTM DOT PCL ODT PS MARKDOWN RTF XAMLFLOW WORDML OTT DOTX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ubah MD ke RTF melalui Java" h2="On Premise Java API untuk Merender MD ke RTF tanpa menggunakan aplikasi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi MD ke RTF dengan menggunakan dua langkah sederhana. Pertama, Anda perlu merender file MD ke DOC menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengonversi DOC ke RTF. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API untuk Mengonversi MD ke RTF" %}}
1. Buka file MD menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi MD ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format RTF menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set RTF sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan [Aspose.PDF untuk Java](https://docs.aspose.com/pdf/java/installation/) dan [Aspose.Words untuk Java](https://docs.aspose.com/words/java/installation/) di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-docm.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}
Saat mengonversi MD ke RTF, meskipun dokumen Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Untuk membuka file terenkripsi, Anda perlu membuat objek [Dokumen](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuka MD menggunakan kata sandi pemilik.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.md", "password");
// save MD as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Buka Dokumen MD yang Dilindungi Kata Sandi melalui Java" %}}
Saat menyimpan dokumen input Anda ke format file RTF, Anda juga dapat menyimpan dokumen Anda ke database alih-alih sistem file. Anda mungkin perlu menerapkan penyimpanan dan pengambilan objek Dokumen ke dan dari database. Ini akan diperlukan jika Anda menerapkan semua jenis sistem manajemen konten. Untuk menyimpan RTF Anda ke database, seringkali perlu membuat serial dokumen untuk mendapatkan array byte. Ini dapat dilakukan menggunakan [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Setelah mendapatkan array byte Anda, Anda dapat menyimpannya di database menggunakan pernyataan SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.RTF);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



Mengonversi MD (Markdown) ke RTF (Rich Text Format) memastikan kompatibilitas lintas platform dan aksesibilitas. Berkas RTF mempertahankan gaya di hampir semua sistem operasi, sehingga cocok untuk distribusi ringan, pengarsipan, dan akses offline.



{{% blocks/products/pf/agp/feature-section-col title="Penggunaan Kunci" %}}



* Mengonversi dokumentasi Markdown menjadi manual RTF portabel.

* Membuat lembar pelatihan yang kompatibel secara universal dari panduan MD.

* Berkas bantuan berbasis RTF yang bersumber dari Markdown untuk sistem-sistem warisan.

* Dokumen teks yang ramah offline untuk tim dengan akses perangkat lunak terbatas.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Skenario Otomatisasi" %}}



* Generasi MD-to-RTF terjadwal untuk arsip digital.

* Alur kerja ETL yang mengekspor repositori konten ke perpustakaan RTF.

* Pembuatan RTF otomatis untuk kit dukungan pelanggan offline.

* Konversi batch catatan Markdown menjadi berkas RTF yang kompatibel dengan berbagai platform.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}