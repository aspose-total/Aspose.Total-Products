---
title: Java API untuk Mengekspor EPUB ke MARKDOWN
description: Konversi EPUB ke MARKDOWN menggunakan API Java di tempat
url: /id/java/conversion/epub-to-markdown/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MARKDOWN
otherformats: MARKDOWN DOT PCL ODT FLATOPC WORDML XAMLFLOW DOTX RTF DOTM PS OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ubah EPUB ke MARKDOWN melalui Java" h2="On Premise Java API untuk Merender EPUB ke MARKDOWN tanpa menggunakan aplikasi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi EPUB ke MARKDOWN dengan menggunakan dua langkah sederhana. Pertama, Anda perlu merender file EPUB ke DOC menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengonversi DOC ke MARKDOWN. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API untuk Mengonversi EPUB ke MARKDOWN" %}}
1. Buka file EPUB menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi EPUB ke DOC dengan menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format MARKDOWN menggunakan metode [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set MARKDOWN sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan [Aspose.PDF untuk Java](https://docs.aspose.com/pdf/java/installation/) dan [Aspose.Words untuk Java](https://docs.aspose.com/words/java/ instalasi/) di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.MARKDOWN
outputDocument.save("output.markdown", SaveFormat.MARKDOWN);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}
Saat mengonversi EPUB ke MARKDOWN, meskipun dokumen Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Untuk membuka file terenkripsi, Anda perlu membuat objek [Dokumen](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuka EPUB menggunakan kata sandi pemilik.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.epub", "password");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Buka Dokumen EPUB yang Dilindungi Kata Sandi melalui Java" %}}
Saat menyimpan dokumen input Anda ke format file MARKDOWN, Anda juga dapat menyimpan dokumen Anda ke database alih-alih sistem file. Anda mungkin perlu menerapkan penyimpanan dan pengambilan objek Dokumen ke dan dari database. Ini akan diperlukan jika Anda menerapkan semua jenis sistem manajemen konten. Untuk menyimpan MARKDOWN Anda ke database, seringkali perlu membuat serial dokumen untuk mendapatkan array byte. Ini dapat dilakukan menggunakan [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Setelah mendapatkan array byte Anda, Anda dapat menyimpannya di database menggunakan pernyataan SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MARKDOWN);
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-rtf/" name="EPUB Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-wordml/" name="EPUB Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-odt/" name="EPUB Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-flatopc/" name="EPUB Ke FLAKePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-ps/" name="EPUB Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-pcl/" name="EPUB Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-mhtml/" name="EPUB Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-dotm/" name="EPUB Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-ott/" name="EPUB Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-dotx/" name="EPUB Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-xamlflow/" name="EPUB Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/epub-to-markdown/" name="EPUB Ke MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}