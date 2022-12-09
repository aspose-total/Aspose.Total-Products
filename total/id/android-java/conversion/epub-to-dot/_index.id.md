---
title: Android API untuk Merender EPUB ke DOT
description: Ubah EPUB ke DOT melalui Android melalui Java API

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: DOT
otherformats: MARKDOWN PCL DOTM XAMLFLOW RTF WORDML FLATOPC OTT DOCM ODT PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EPUB ke DOT di Android melalui Java" h2="Konversi EPUB ke DOT di aplikasi seluler tanpa menginstal perangkat lunak apa pun" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi EPUB ke DOT di aplikasi seluler Anda dengan menggunakan dua API paket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Pertama, Anda perlu mengonversi file EPUB ke DOC menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Kedua, dengan menggunakan Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), Anda dapat merender DOC ke DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi EPUB ke DOT di Android melalui Java" %}}
1. Buka file EPUB menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi EPUB ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format DOT menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set DOT sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOT
outputDocument.save("output.dot", SaveFormat.DOT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Informasi File EPUB di Android melalui Java" %}}
Sebelum mengonversi EPUB ke DOT, Anda mungkin memerlukan informasi tentang dokumen termasuk penulis, tanggal pembuatan, kata kunci, tanggal modifikasi, subjek, dan judul. Informasi ini berguna untuk pengambilan keputusan untuk proses konversi. Menggunakan [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API yang kuat, Anda bisa mendapatkan semuanya. Untuk mendapatkan informasi khusus file tentang file EPUB, pertama-tama dapatkan objek [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) menggunakan [getInfo](https://reference.aspose.com/pdf/Java/com.aspose.pdf/Document#getInfo--). Setelah objek DocumentInfo diambil, Anda bisa mendapatkan nilai dari masing-masing properti.
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB document
Document doc = new Document("template.epub");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Masukkan Catatan Akhir dalam Dokumen DOT di Android melalui Java" %}}
Selain konversi dokumen, Anda juga dapat menambahkan banyak fitur lain di dalam Aplikasi Android Anda menggunakan [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Salah satu fitur tersebut adalah menyisipkan catatan akhir dan penomoran pada dokumen DOT. Jika Anda ingin menyisipkan catatan kaki atau catatan akhir dalam dokumen DOT, gunakan metode DocumentBuilder.InsertFootnote. Metode ini menyisipkan catatan kaki atau catatan akhir ke dalam dokumen. Kelas EndnoteOptions dan FootnoteOptions mewakili opsi penomoran untuk catatan kaki dan catatan akhir.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.dot", SaveFormat.DOT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-markdown/" name="EPUB Ke MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-pcl/" name="EPUB Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-dotm/" name="EPUB Ke DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-xamlflow/" name="EPUB Ke XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-rtf/" name="EPUB Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-wordml/" name="EPUB Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-flatopc/" name="EPUB Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-ott/" name="EPUB Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-dot/" name="EPUB Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-odt/" name="EPUB Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-ps/" name="EPUB Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/epub-to-dotx/" name="EPUB Ke DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}