---
title: Ekspor XLSX ke PPTX di Android
description: Android API untuk Mengonversi XLSX ke PPTX tanpa menggunakan Microsoft Word
url: /id/android-java/conversion/xlsx-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: WORD POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render XLSX ke PPTX di Android melalui Java" h2="Ubah XLSX menjadi PPTX dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) adalah paket File Automation API yang andal. Dengan menggunakan dua API-nya, Anda dapat mengintegrasikan fitur konversi XLSX ke PPTX di dalam aplikasi Android Anda. Pada langkah pertama Anda dapat mengekspor XLSX ke PDF dengan menggunakan [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Setelah itu, dengan menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), Anda dapat mengonversi PDF ke PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor XLSX ke PPTX" %}}
1. Buka file XLSX menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi XLSX ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument)
4. Simpan dokumen ke format PPTX menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF for Android via Java](https://pptxs.aspose.com/pdf/androidjava/installation/) dan [Aspose.Cells for Android via Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Properti Kustom dari File XLSX di Android melalui Java" %}}
Selain konversi dokumen, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) juga menyediakan banyak fitur lainnya. Sebelum proses konversi, Anda dapat menghapus properti kustom dari dokumen XLSX. Untuk menghapus properti kustom, panggil metode [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) dan teruskan nama properti dokumen yang akan dihapus.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xlsx-to-word/" name="XLSX Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xlsx-to-powerpoint/" name="XLSX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xlsx-to-pptxx/" name="XLSX Ke PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/xlsx-to-pptx/" name="XLSX Ke PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}