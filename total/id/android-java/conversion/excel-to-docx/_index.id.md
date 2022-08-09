---
title: Ekspor EXCEL ke DOCX di Android
description: Android API untuk Mengonversi EXCEL ke DOCX tanpa menggunakan Microsoft Word
url: /id/android-java/conversion/excel-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOCX
otherformats: WORD POWERPOINT PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EXCEL ke DOCX di Android melalui Java" h2="Ubah EXCEL menjadi DOCX dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total untuk Android melalui Java](https://products.aspose.com/total/android-java/) adalah paket File Automation API yang andal. Dengan menggunakan dua API-nya, Anda dapat mengintegrasikan fitur konversi EXCEL ke DOCX di dalam aplikasi Android Anda. Pada langkah pertama Anda dapat mengekspor EXCEL ke PDF dengan menggunakan [Aspose.Cells untuk Android melalui Java](https://products.aspose.com/cells/android-java/). Setelah itu, dengan menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), Anda dapat mengonversi PDF ke DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor EXCEL ke DOCX" %}}
1. Buka file EXCEL menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi EXCEL ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument)
4. Simpan dokumen ke format DOCX menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total untuk Android melalui Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF untuk Android melalui Java](https://docxs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Cells untuk Android melalui Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Properti Kustom dari File EXCEL di Android melalui Java" %}}
Selain konversi dokumen, [Aspose.Cells untuk Android melalui Java](https://products.aspose.com/cells/android-java/) juga menyediakan banyak fitur lainnya. Sebelum proses konversi, Anda dapat menghapus properti kustom dari dokumen EXCEL. Untuk menghapus properti kustom, panggil metode [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) dan teruskan nama properti dokumen yang akan dihapus.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/excel-to-word/" name="EXCEL Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/excel-to-powerpoint/" name="EXCEL Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/excel-to-pptx/" name="EXCEL Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/excel-to-docx/" name="EXCEL Ke DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}