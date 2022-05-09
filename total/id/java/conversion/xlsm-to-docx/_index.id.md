---
title: Konversi XLSM ke DOCX menggunakan Java
description: Java API untuk Mengekspor XLSM ke DOCX dengan menggunakan Excel atau Word
url_ignore: /id/java/conversion/xlsm-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOCXX
otherformats: DOCX WORD POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Mengekspor XLSM ke DOCX" h2="On Premise Java API untuk Mengekspor XLSM ke DOCX tanpa mengandalkan Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Rendering XLSM ke DOCX adalah proses dua langkah. Pertama-tama Anda akan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java) API untuk mengonversi dokumen XLSM yang diberikan ke PDF, lalu dengan menggunakan [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, Anda dapat dengan mudah mengonversi dokumen PDF Anda ke DOCX. Kedua API berada di bawah koleksi [Aspose.Total for Java](https://products.aspose.com/total/java/) perpustakaan otomatisasi format file.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLSM ke DOCX melalui Java API" %}}
1. Buka file XLSM menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi XLSM ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Simpan dokumen ke format DOCX menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode dan atur Docx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Workbook class
Workbook book = new Workbook("input.xlsm");
// save XLSM as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsm-to-docxx/" name="XLSM Ke DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsm-to-pptx/" name="XLSM Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsm-to-powerpoint/" name="XLSM Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsm-to-word/" name="XLSM Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}