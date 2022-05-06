---
title: Konversi XLSB ke DOCX menggunakan Java
description: Java API untuk Mengekspor XLSB ke DOCX dengan menggunakan Excel atau Word
url_ignore: /id/java/conversion/xlsb-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: DOCXX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Mengekspor XLSB ke DOCX" h2="On Premise Java API untuk Mengekspor XLSB ke DOCX tanpa mengandalkan Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Rendering XLSB ke DOCX adalah proses dua langkah. Pertama-tama Anda akan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java) API untuk mengonversi dokumen XLSB yang diberikan ke PDF, lalu dengan menggunakan [Aspose.Pdf for Java](https ://products.aspose.com/pdf/java) API, Anda dapat dengan mudah mengonversi dokumen PDF Anda ke DOCX. Kedua API berada di bawah koleksi [Aspose.Total for Java](https://products.aspose.com/total/java/) perpustakaan otomatisasi format file.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLSB ke DOCX melalui Java API" %}}
1. Buka file XLSB menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi XLSB ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Simpan dokumen ke format DOCX menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode dan atur Docx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Workbook class
Workbook book = new Workbook("input.xlsb");
// save XLSB as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsb-to-docxx/" name="XLSB Ke DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsb-to-pptx/" name="XLSB Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsb-to-powerpoint/" name="XLSB Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsb-to-word/" name="XLSB Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}