---
title: Ekspor MSG ke WORDML melalui Java
description: Java API untuk Mengonversi MSG ke WORDML tanpa menggunakan Microsoft Word atau Outlook
url_ignore: /id/java/conversion/msg-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD_ML
otherformats: DOCX DOTM EMF PCL PS JPEG DOC EPUB OTT TIFF PDF TEXT DOT XPS DOTX GIF MD WORDML SVG FLATOPC DOCM PNG ODT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Merender MSG ke WORDML" h2="Ekspor MSG ke WORDML dengan menggunakan Java API lokal tanpa menggunakan dependensi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konversi msg adalah fitur canggih yang dapat diintegrasikan oleh pengembang Java dalam aplikasi Java J2SE, J2EE, J2ME melalui [Aspose.Total for Java](https://products.aspose.com/total/java/). Dengan menggunakan dua API dalam paket, Anda dapat mengonversi Msg MSG ke WORDML tanpa ketergantungan pihak ketiga. Pertama, Anda dapat menggunakan API Manipulasi Msg [Aspose.Email for Java](https://products.aspose.com/email/java/) untuk mengonversi format file MSG ke HTML. Kedua, Anda dapat merender HTML ke WORDML dengan menggunakan API Pemrosesan Dokumen [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi MSG ke WORDML" %}}
1. Buka file MSG menggunakan kelas [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konversi MSG ke HTML dengan menggunakan [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions)) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format WORDML menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur WORDML sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.WORD_ML
document.save("output.word_ml", SaveFormat.WORD_ML);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}