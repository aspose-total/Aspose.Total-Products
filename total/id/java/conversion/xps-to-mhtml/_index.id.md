---
title: Konversi XPS ke MHTML Online atau Mengembangkan Aplikasi berbasis Java untuk Mengonversi File XPS
description: Aplikasi daring gratis untuk mengonversi berkas XPS ke MHTML. Kode pustaka konversi Java untuk dokumen XPS. 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: MHTML
otherformats: XAMLFLOW OTT MHTML DOT MARKDOWN PCL PS RTF ODT FLATOPC DOTX DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aplikasi Konversi XPS ke MHTML Online dan Kode Java untuk Mengonversi File XPS" h2="Mengembangkan aplikasi konversi dan ekspor XPS berbasis Java yang canggih. Konversi satu atau beberapa file XPS ke MHTML dan format lainnya melalui API otomatisasi Java. Konversi file XPS secara bebas secara daring melalui aplikasi dengan unduhan instan." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Aplikasi Konversi XPS ke MHTML Online Gratis" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=mhtml&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi File XPS ke MHTML Online menggunakan Aplikasi" %}}

1. Unggah file XPS untuk dikonversi
1. Tunggu beberapa detik atau lebih tergantung pada ukuran XPS
1. Perhatikan status bar unggahan
1. Klik tombol "Konversi"
1. XPS akan diubah menjadi dokumen MHTML
1. Unduh file MHTML yang dikonversi

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konversi XPS ke MHTML melalui Java Automation API" %}}


1. Buka file XPS menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi XPS ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format MHTML menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set MHTML sebagai SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Beberapa kasus lagi untuk menyimpan XPS ke MHTML dengan fitur lain seperti Persyaratan Konversi, Buka Dokumen XPS yang Dilindungi Kata Sandi melalui Java.

{{% blocks/products/pf/feature-page-code %}}


```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Mengembangkan Aplikasi Konversi File XPS menggunakan Java</h2>

Perlu mengembangkan aplikasi perangkat lunak berbasis Java untuk dengan mudah menyimpan dan mengekspor file XPS ke dokumen MHTML? Dengan [Aspose.Total for Java](https://products.aspose.com/total/id/java/), pengembang Java mana pun dapat mengintegrasikan kode API di atas untuk memprogram aplikasi konversi di berbagai format termasuk Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, file Email, Gambar (JPG, PNG, BMP, GIF) dan format lainnya. Pustaka Java yang canggih untuk konversi dokumen, mendukung banyak format populer termasuk format XPS. Mengekspor dan merender dokumen ke format lain, programmer dapat menggunakan API anak Aspose.Total for Java termasuk [Aspose.Words for Java](https://products.aspose.com/words/id/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/id/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/id/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/id/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/id/java/) dan banyak lagi.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Pustaka Konversi XPS untuk Java" %}}

Ada pilihan alternatif untuk mengintegrasikan Aspose.Total for Java ke sistem Anda. Silakan pilih salah satu yang sesuai dengan kebutuhan Anda dan ikuti petunjuk langkah demi langkah:<br /><br />

- Gunakan Aspose.Total for Java langsung dari proyek berbasis Maven dan sertakan API anak yang relevan dalam pom.xml.
- Alternatifnya, seseorang bisa mendapatkan berkas ZIP dari [Unduhan](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Aplikasi Menyimpan XPS ke MHTML" %}}

Sistem Operasi apa pun yang dapat menjalankan Java Runtime Environment (JRE) dapat menjalankan Aspose.Total for Java. Berikut ini daftar sebagian besar, tetapi tidak semua, Sistem Operasi yang didukung. <br /><br />
- Microsoft Windows
- Linux : Ubuntu, OpenSUSE, CentOS dan lainnya
- macOS: 10.9 (Mavericks) dan yang lebih baru
- Seluler: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}