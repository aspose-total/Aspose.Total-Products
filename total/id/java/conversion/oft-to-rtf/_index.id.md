---
title: Ekspor OFT ke RTF melalui Java
description: Java API untuk Mengonversi OFT ke RTF tanpa menggunakan Microsoft Word atau Outlook
url_ignore: /id/java/conversion/oft-to-rtf/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: RTF
otherformats: DOC PS SVG PDF FLATOPC WORDML XPS JPEG TEXT DOTM EMF PNG OTT DOCM GIF EPUB PCL MD ODT RTF DOCX TIFF DOTX DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Merender OFT ke RTF" h2="Ekspor OFT ke RTF dengan menggunakan Java API lokal tanpa menggunakan dependensi pihak ketiga" >}}
{{% blocks/products/pf/feature-page-summary %}}
Konversi oft adalah fitur canggih yang dapat diintegrasikan oleh pengembang Java dalam aplikasi Java J2SE, J2EE, J2ME melalui [Aspose.Total for Java](https://products.aspose.com/total/java/). Dengan menggunakan dua API dalam paket, Anda dapat mengonversi Oft OFT ke RTF tanpa ketergantungan pihak ketiga. Pertama, Anda dapat menggunakan API Manipulasi Oft [Aspose.Oft for Java](https://products.aspose.com/email/java/) untuk mengonversi format file OFT ke HTML. Kedua, Anda dapat merender HTML ke RTF dengan menggunakan API Pemrosesan Dokumen [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi OFT ke RTF" %}}
1. Buka file OFT menggunakan kelas [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Konversi OFT ke HTML dengan menggunakan [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) metode
3. Muat HTML dengan menggunakan kelas [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Simpan dokumen ke format RTF menggunakan [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) metode dan atur RTF sebagai SaveFormat
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