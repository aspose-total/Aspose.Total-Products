---
title: Ekspor OFT ke XPS melalui Java
description: Java API untuk Mengonversi OFT ke XPS tanpa menggunakan Microsoft Word atau Outlook
url_ignore: /id/java/conversion/oft-to-xps/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: XPS
otherformats: PNG TEXT PDF ODT PS DOT TIFF XPS MD FLATOPC RTF EMF PCL JPEG GIF OTT DOTX SVG DOCX DOCM DOTM EPUB WORDML DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Merender OFT ke XPS" h2="Ekspor OFT ke XPS dengan menggunakan Java API lokal tanpa menggunakan dependensi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konversi oft adalah fitur canggih yang dapat diintegrasikan oleh pengembang Java dalam aplikasi Java J2SE, J2EE, J2ME melalui [Aspose.Total for Java](https://products.aspose.com/total/java/). Dengan menggunakan dua API dalam paket, Anda dapat mengonversi Oft OFT ke XPS tanpa ketergantungan pihak ketiga. Pertama, Anda dapat menggunakan API Manipulasi Oft [Aspose.Oft for Java](https://products.aspose.com/email/java/) untuk mengonversi format file OFT ke HTML. Kedua, Anda dapat merender HTML ke XPS dengan menggunakan API Pemrosesan Dokumen [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi OFT ke XPS" %}}
1. Buka file OFT menggunakan kelas [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konversi OFT ke HTML dengan menggunakan [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format XPS menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur XPS sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.XPS
document.save("output.xps", SaveFormat.XPS);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}