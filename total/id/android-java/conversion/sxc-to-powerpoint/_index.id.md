---
title: Ekspor SXC ke POWERPOINT di Android
description: Android API untuk Mengonversi SXC ke POWERPOINT tanpa menggunakan Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Render SXC ke POWERPOINT di Android melalui Java" h2="Ubah SXC menjadi POWERPOINT dalam Aplikasi Android Anda tanpa menggunakan Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) adalah paket File Automation API yang andal. Dengan menggunakan dua API-nya, Anda dapat mengintegrasikan fitur konversi SXC ke POWERPOINT di dalam aplikasi Android Anda. Pada langkah pertama Anda dapat mengekspor SXC ke PDF dengan menggunakan [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). Setelah itu, dengan menggunakan [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), Anda dapat mengonversi PDF ke POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API untuk Mengekspor SXC ke POWERPOINT" %}}
1. Buka file SXC menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi SXC ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument)
4. Simpan dokumen ke format POWERPOINT menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) metode
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda dapat dengan mudah menggunakan Aspose.Total for Android via Java langsung dari [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) dan instal [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) dan [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via-java-from-maven-repository) di aplikasi Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Hapus Properti Kustom dari File SXC di Android melalui Java" %}}
Selain konversi dokumen, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) juga menyediakan banyak fitur lainnya. Sebelum proses konversi, Anda dapat menghapus properti kustom dari dokumen SXC. Untuk menghapus properti kustom, panggil metode [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) dan teruskan nama properti dokumen yang akan dihapus.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Konversi lain yang Didukung" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/sxc-to-powerpointx/" name="SXC Ke POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/sxc-to-powerpoint/" name="SXC Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/sxc-to-word/" name="SXC Ke WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/android-java/conversion/sxc-to-pptx/" name="SXC Ke PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}