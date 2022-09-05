---
title: Konversi Dokumen melalui Android API 
url: /id/android-java/conversion/
description: Konversi format Word, Excel, PowerPoint, HTML, PDF, dan Gambar menggunakan API konversi Android. Android mengonversi Office docx, xlsx, pptx ke PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Dokumen menggunakan Android API" h2="Konversi Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Gambar, dan berbagai format lainnya menggunakan Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) menyediakan solusi konversi dan pengelolaan dokumen untuk aplikasi Android tanpa bergantung pada perangkat lunak lain. Pemrogram dapat mengotomatisasi manajemen dokumen dan solusi manipulasi dengan mudah dengan mengintegrasikan API dalam aplikasi baru yang dikembangkan atau dalam aplikasi yang sudah ada. Dengan mengintegrasikan API, Programmer dapat dengan mudah menambahkan fungsionalitas untuk membuat, mengedit, atau mengonversi berbagai format dokumen dalam aplikasi. PDF Converter API di Android menangani kasus konversi seperti Office DOCX, XLSX, PPTX ke PDF atau sebaliknya. Selain itu, Beberapa kasus yang ditangani API tercantum di bawah ini dan beberapa tautan yang diberikan untuk kasus konversi yang relevan. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PDF ke CSV" %}}
Total Android API mendukung konversi PDF ke Excel XLSX dan CSV. Ini adalah proses dua langkah. Dua Total API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) dan (Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) yang terlibat. Prosesnya adalah Anda dapat menyembunyikan format PDF ke Excel XLSX terlebih dahulu dan kemudian XLSX ke CSV. Lebih detail, Muat file PDF melalui kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan render ke XLSX melalui [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Selanjutnya muat dokumen XLSX yang dirender dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dan aktifkan [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) metode.

{{% blocks/products/pf/feature-page-code h3="Android - Konversi PDF ke Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Konversi Excel ke Word" %}}
Android API juga menangani konversi Excel. Prosesnya adalah, Muat file EXCEL XLSX menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dan konversi EXCEL ke PDF dengan mengatur SaveFormat ke AUTO terlebih dahulu. Selanjutnya muat file PDF yang disimpan menggunakan kelas [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) dan aktifkan [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) metode untuk menyimpan dokumen ke format Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Konversi Excel ke Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi POWERPOINT ke HTML dan MHTML" %}}
Android Total API menangani berbagai format termasuk file PowerPoint sehingga dapat mengonversi presentasi ke HTML dan MHTML. Prosesnya adalah, Muat file PPT/PPTX POWERPOINT menggunakan kelas [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) dan aktifkan [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) metode untuk mengonversi POWERPOINT ke HTML. Selain itu, Sekarang muat dokumen HTML yang dikonversi dengan menggunakan kelas [Buku Kerja](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) dan panggil [save](https://reference.aspose.com/cells/java/com.aspose.cells/) metode untuk konversi MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - Slide PowerPoint ke Konversi HTML dan MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}