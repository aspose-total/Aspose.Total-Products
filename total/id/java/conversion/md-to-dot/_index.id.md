---
title: Java API untuk Mengekspor MD ke DOT
description: Konversi MD ke DOT menggunakan API Java di tempat
url_ignore: /id/java/conversion/md-to-dot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOT
otherformats: WORDML RTF OTT DOTM PS DOT FLATOPC XAMLFLOW MHTML MARKDOWN PCL ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Ubah MD ke DOT melalui Java" h2="On Premise Java API untuk Merender MD ke DOT tanpa menggunakan aplikasi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengonversi MD ke DOT dengan menggunakan dua langkah sederhana. Pertama, Anda perlu merender file MD ke DOC menggunakan [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). Setelah itu, dengan menggunakan API Pemrosesan Dokumen yang kuat [Aspose.Words for Java](https://products.aspose.com/words/java/), Anda dapat mengonversi DOC ke DOT. Kedua API berada di bawah paket [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API untuk Mengonversi MD ke DOT" %}}
1. Buka file MD menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi MD ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format DOT menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set DOT sebagai SaveFormat
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
Saat mengonversi MD ke DOT, meskipun dokumen Anda dilindungi kata sandi, Anda masih dapat membukanya menggunakan PDF Manipulation API [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). Untuk membuka file terenkripsi, Anda perlu membuat objek [Dokumen](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan membuka MD menggunakan kata sandi pemilik.  
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
Saat menyimpan dokumen input Anda ke format file DOT, Anda juga dapat menyimpan dokumen Anda ke database alih-alih sistem file. Anda mungkin perlu menerapkan penyimpanan dan pengambilan objek Dokumen ke dan dari database. Ini akan diperlukan jika Anda menerapkan semua jenis sistem manajemen konten. Untuk menyimpan DOT Anda ke database, seringkali perlu membuat serial dokumen untuk mendapatkan array byte. Ini dapat dilakukan menggunakan [Aspose.Words for Java](https://products.aspose.com/words/Java/) API. Setelah mendapatkan array byte Anda, Anda dapat menyimpannya di database menggunakan pernyataan SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOT);
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}