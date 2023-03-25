---
title: Ekspor EXCEL ke WORD di Android atau dengan Konverter Online gratis
description: Android API untuk Mengonversi EXCEL ke WORD tanpa menggunakan Microsoft Word atau daring. Uji konverter online EXCEL ke DOC gratis dengan cepat sebelum mengintegrasikan kode.

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: DOCX PPTX POWERPOINT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render EXCEL ke WORD di Android melalui Java atau Aplikasi Daring" h2="Ubah EXCEL menjadi WORD dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) adalah paket File Automation API yang andal. Dengan menggunakan dua API-nya, Anda dapat mengintegrasikan fitur konversi EXCEL ke WORD di dalam aplikasi Android Anda. Pada langkah pertama Anda dapat mengekspor EXCEL ke PDF dengan menggunakan [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Setelah itu, dengan menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), Anda dapat mengonversi PDF ke WORD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor EXCEL ke WORD" %}}
1. Buka file EXCEL menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi EXCEL ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Wordument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument)
4. Simpan dokumen ke format WORD menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://releases.aspose.com/total/java/) dan instal [Aspose.PDF for Android via Java](https://words.aspose.com/pdf/androidjava/installation/) dan [Aspose.Cells for Android via Java](https://words.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// save EXCEL as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Konverter Online Gratis untuk EXCEL ke WORD</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Hapus Properti Kustom dari File EXCEL di Android melalui Java" %}}
Selain konversi dokumen, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) juga menyediakan banyak fitur lainnya. Sebelum proses konversi, Anda dapat menghapus properti kustom dari dokumen EXCEL. Untuk menghapus properti kustom, panggil metode [WordumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/wordumentpropertycollection#remove(java.lang.String)) dan teruskan nama properti dokumen yang akan dihapus.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the EXCEL file using Workbook class
Workbook book = new Workbook("input.excel");
// retrieve a list of all custom wordument properties of the Excel file
WordumentPropertyCollection customProperties = workbook.getWorksheets().getCustomWordumentProperties();
// remove a custom wordument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}