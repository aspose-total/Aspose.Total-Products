---
title: Konversi XLTX ke DOCX menggunakan Java atau dengan Konverter Online gratis
description: Java API untuk Mengekspor XLTX ke DOCX atau daring dengan menggunakan Excel atau Word atau daring. Uji konverter online CSV ke DOC gratis dengan cepat sebelum mengintegrasikan kode.
url_ignore: /id/java/conversion/xltx-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: PPTX WORD DOCX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API untuk Mengekspor XLTX ke DOCX atau daring" h2="On Premise Java API untuk Mengekspor XLTX ke DOCX atau daring tanpa mengandalkan Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Rendering XLTX ke DOCX adalah proses dua langkah. Pertama-tama Anda akan menggunakan [Aspose.Cells for Java](https://products.aspose.com/cells/java) API untuk mengonversi dokumen XLTX yang diberikan ke PDF, lalu dengan menggunakan [Aspose.Pdf for Java](https://products.aspose.com/pdf/java) API, Anda dapat dengan mudah mengonversi dokumen PDF Anda ke DOCX. Kedua API berada di bawah koleksi [Aspose.Total for Java](https://products.aspose.com/total/java/) perpustakaan otomatisasi format file.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cara Mengonversi XLTX ke DOCX melalui Java API" %}}
1. Buka file XLTX menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. Konversi XLTX ke PDF dan atur SaveFormat ke AUTO
3. Muat file PDF yang dikonversi menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. Simpan dokumen ke format DOCX menggunakan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode dan atur Docx sebagai SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Persyaratan Konversi" %}}
Anda harus menggunakan Aspose.Total untuk Java langsung dari proyek berbasis [Maven](https://releases.aspose.com/total/java/) dan sertakan perpustakaan di pom.xml Anda.

Atau, Anda bisa mendapatkan file ZIP dari [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Workbook class
Workbook book = new Workbook("input.xltx");
// save XLTX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Konverter Online untuk XLTX ke DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xltx-to-docx/">Coba aplikasi gratis kami untuk konversi XLTX ke DOCX</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Opsi Konversi Lainnya" subTitle="" >}}DOCX
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xltx-to-docxx/" name="XLTX Ke DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xltx-to-pptx/" name="XLTX Ke PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xltx-to-powerpoint/" name="XLTX Ke POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/id/net/conversion/xltx-to-word/" name="XLTX Ke WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}