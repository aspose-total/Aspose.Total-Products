---
title: Java API untuk Mengekspor PS ke RTF
description: Konversi PS ke RTF menggunakan API Java di tempat
url: /id/java/conversion/ps-to-rtf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: RTF
otherformats: XAMLFLOW FLATOPC ODT DOTM WORDML DOT MARKDOWN MHTML RTF DOTX PCL OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ubah PS ke RTF melalui Java" h2="On Premise Java API untuk Merender PS ke RTF tanpa menggunakan aplikasi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi PS ke RTF dengan menggunakan dua langkah sederhana. Pertama, Anda perlu merender file PS ke DOC menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengonversi DOC ke RTF. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API untuk Mengonversi PS ke RTF" %}}
1. Buka file PS menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi PS ke DOC dengan menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format RTF menggunakan metode [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set RTF sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan [Aspose.PDF untuk Java](https://docs.aspose.com/pdf/java/installation/) dan [Aspose.Words untuk Java](https://docs.aspose.com/words/java/ instalasi/) di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PS file with an instance of Document class
Document document = new Document("template.ps");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.RTF
outputDocument.save("output.rtf", SaveFormat.RTF);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Persyaratan Konversi" %}}
Saat mengonversi PS ke RTF, meskipun dokumen Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Untuk membuka file terenkripsi, Anda perlu membuat objek [Dokumen](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuka PS menggunakan kata sandi pemilik.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.ps", "password");
// save PS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Buka Dokumen PS yang Dilindungi Kata Sandi melalui Java" %}}
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
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-rtf/" name="PS Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-wordml/" name="PS Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-odt/" name="PS Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-flatopc/" name="PS Ke FLAKePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-ps/" name="PS Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-pcl/" name="PS Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-mhtml/" name="PS Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-dotm/" name="PS Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-ott/" name="PS Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-dotx/" name="PS Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-xamlflow/" name="PS Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/ps-to-markdown/" name="PS Ke MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}