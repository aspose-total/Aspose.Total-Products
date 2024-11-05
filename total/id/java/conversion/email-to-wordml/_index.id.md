---
title: Ekspor EMAIL ke WORDML melalui Java
description: Java API untuk Mengonversi EMAIL ke WORDML tanpa menggunakan Microsoft Word atau Outlook
url_ignore: /id/java/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD_ML
otherformats: MD FLATOPC PNG DOCM DOC EMF GIF DOT SVG WORDML PS ODT DOTX OTT PDF RTF TEXT PCL XPS JPEG EPUB DOCX DOTM TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Merender EMAIL ke WORDML" h2="Ekspor EMAIL ke WORDML dengan menggunakan Java API lokal tanpa menggunakan dependensi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konversi email adalah fitur canggih yang dapat diintegrasikan oleh pengembang Java dalam aplikasi Java J2SE, J2EE, J2ME melalui [Aspose.Total for Java](https://products.aspose.com/total/java/). Dengan menggunakan dua API dalam paket, Anda dapat mengonversi Email EMAIL ke WORDML tanpa ketergantungan pihak ketiga. Pertama, Anda dapat menggunakan API Manipulasi Email [Aspose.Email for Java](https://products.aspose.com/email/java/) untuk mengonversi format file EMAIL ke HTML. Kedua, Anda dapat merender HTML ke WORDML dengan menggunakan API Pemrosesan Dokumen [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi EMAIL ke WORDML" %}}
1. Buka file EMAIL menggunakan kelas [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konversi EMAIL ke HTML dengan menggunakan [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format WORDML menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur WORDML sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}