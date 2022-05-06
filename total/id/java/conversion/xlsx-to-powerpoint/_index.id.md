---
title: Konversi XLSX ke POWERPOINT menggunakan Java
description: Java API untuk Mengekspor XLSX ke POWERPOINT dengan menggunakan Excel atau Word
url_ignore: /id/java/conversion/xlsx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: POWERPOINTX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Mengekspor XLSX ke POWERPOINT" h2="On Premise Java API untuk Mengekspor XLSX ke POWERPOINT tanpa mengandalkan Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Rendering XLSX ke POWERPOINT adalah proses dua langkah. Pertama-tama Anda akan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java) API untuk mengonversi dokumen XLSX yang diberikan ke PDF, lalu dengan menggunakan [Aspose.Pdf for Java](https ://products.aspose.com/pdf/java) API, Anda dapat dengan mudah mengonversi dokumen PDF Anda ke POWERPOINT. Kedua API berada di bawah koleksi [Aspose.Total for Java](https://products.aspose.com/total/java/) perpustakaan otomatisasi format file.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLSX ke POWERPOINT melalui Java API" %}}
1. Buka file XLSX menggunakan kelas [Buku Kerja](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi XLSX ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Powerpointument](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Simpan dokumen ke format POWERPOINT menggunakan [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode dan atur Powerpoint sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsx-to-powerpointx/" name="XLSX Ke POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsx-to-pptx/" name="XLSX Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsx-to-powerpoint/" name="XLSX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xlsx-to-word/" name="XLSX Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}