---
title: Android API untuk Merender PCL ke DOCM
description: Ubah PCL ke DOCM melalui Android melalui Java API

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: DOCM
otherformats: FLATOPC DOT PS ODT RTF OTT WORDML MARKDOWN MHTML XAMLFLOW DOTM DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render PCL ke DOCM di Android melalui Java" h2="Konversi PCL ke DOCM di aplikasi seluler tanpa menginstal perangkat lunak apa pun" >}}

{{% blocks/products/pf/feature-page-summary %}}
Anda dapat mengintegrasikan fitur konversi PCL ke DOCM di aplikasi seluler Anda dengan menggunakan dua API paket [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). Pertama, Anda perlu mengonversi file PCL ke DOC menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). Kedua, dengan menggunakan Word Processing API [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/), Anda dapat merender DOC ke DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konversi PCL ke DOCM di Android melalui Java" %}}
1. Buka file PCL menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Konversi PCL ke DOC dengan menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode
3. Muat file DOC dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) dari Aspose.Words
4. Simpan dokumen ke format DOCM menggunakan metode [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) dan set DOCM sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOCM
outputDocument.save("output.docm", SaveFormat.DOCM);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dapatkan Informasi File PCL di Android melalui Java" %}}
Sebelum mengonversi PCL ke DOCM, Anda mungkin memerlukan informasi tentang dokumen termasuk penulis, tanggal pembuatan, kata kunci, tanggal modifikasi, subjek, dan judul. Informasi ini berguna untuk pengambilan keputusan untuk proses konversi. Menggunakan [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API yang kuat, Anda bisa mendapatkan semuanya. Untuk mendapatkan informasi khusus file tentang file PCL, pertama-tama dapatkan objek [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) menggunakan [getInfo](https://reference.aspose.com/pdf/Java/com.aspose.pdf/Document#getInfo--). Setelah objek DocumentInfo diambil, Anda bisa mendapatkan nilai dari masing-masing properti.
{{% blocks/products/pf/feature-page-code %}}

```java
// load PCL document
Document doc = new Document("template.pcl");
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

{{% blocks/products/pf/feature-page-section  h2="Masukkan Catatan Akhir dalam Dokumen DOCM di Android melalui Java" %}}
Selain konversi dokumen, Anda juga dapat menambahkan banyak fitur lain di dalam Aplikasi Android Anda menggunakan [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/) API. Salah satu fitur tersebut adalah menyisipkan catatan akhir dan penomoran pada dokumen DOCM. Jika Anda ingin menyisipkan catatan kaki atau catatan akhir dalam dokumen DOCM, gunakan metode DocumentBuilder.InsertFootnote. Metode ini menyisipkan catatan kaki atau catatan akhir ke dalam dokumen. Kelas EndnoteOptions dan FootnoteOptions mewakili opsi penomoran untuk catatan kaki dan catatan akhir.
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
doc.save("output.docm", SaveFormat.DOCM);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}