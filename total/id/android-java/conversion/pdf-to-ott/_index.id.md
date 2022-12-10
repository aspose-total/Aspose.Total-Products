---
title: Android API untuk Merender PDF ke OTT
description: Ubah PDF ke OTT melalui Android melalui Java API

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: OTT
otherformats: MHTML RTF MARKDOWN DOT PS DOCM FLATOPC ODT DOTX PCL WORDML XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PDF ke OTT di Android melalui Java" h2="Konversi PDF ke OTT di aplikasi seluler tanpa menginstal perangkat lunak apa pun" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi PDF ke OTT di aplikasi seluler Anda dengan menggunakan dua API paket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Pertama, Anda perlu mengonversi file PDF ke DOC menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Kedua, dengan menggunakan Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), Anda dapat merender DOC ke OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi PDF ke OTT di Android melalui Java" %}}
1. Buka file PDF menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi PDF ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format OTT menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set OTT sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.OTT
outputDocument.save("output.ott", SaveFormat.OTT);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Informasi File PDF di Android melalui Java" %}}
Sebelum mengonversi PDF ke OTT, Anda mungkin memerlukan informasi tentang dokumen termasuk penulis, tanggal pembuatan, kata kunci, tanggal modifikasi, subjek, dan judul. Informasi ini berguna untuk pengambilan keputusan untuk proses konversi. Menggunakan [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API yang kuat, Anda bisa mendapatkan semuanya. Untuk mendapatkan informasi khusus file tentang file PDF, pertama-tama dapatkan objek [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) menggunakan [getInfo](https://reference.aspose.com/pdf/Java/com.aspose.pdf/Document#getInfo--). Setelah objek DocumentInfo diambil, Anda bisa mendapatkan nilai dari masing-masing properti.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF document
Document doc = new Document("template.pdf");
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

{{% blocks/products/pf/feature-page-section  h2="Masukkan Catatan Akhir dalam Dokumen OTT di Android melalui Java" %}}
Selain konversi dokumen, Anda juga dapat menambahkan banyak fitur lain di dalam Aplikasi Android Anda menggunakan [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Salah satu fitur tersebut adalah menyisipkan catatan akhir dan penomoran pada dokumen OTT. Jika Anda ingin menyisipkan catatan kaki atau catatan akhir dalam dokumen OTT, gunakan metode DocumentBuilder.InsertFootnote. Metode ini menyisipkan catatan kaki atau catatan akhir ke dalam dokumen. Kelas EndnoteOptions dan FootnoteOptions mewakili opsi penomoran untuk catatan kaki dan catatan akhir.
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
doc.save("output.ott", SaveFormat.OTT);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-mhtml/" name="PDF Ke MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-rtf/" name="PDF Ke RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-markdown/" name="PDF Ke MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-dot/" name="PDF Ke DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-ps/" name="PDF Ke PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-ott/" name="PDF Ke OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-flatopc/" name="PDF Ke FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-odt/" name="PDF Ke ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-dotx/" name="PDF Ke DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-pcl/" name="PDF Ke PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-wordml/" name="PDF Ke WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/pdf-to-xamlflow/" name="PDF Ke XAMLFLOW" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}