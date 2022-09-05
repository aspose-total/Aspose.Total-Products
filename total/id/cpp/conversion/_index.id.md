---
title: Konversi Dokumen melalui C++ 
url: /id/cpp/conversion/
description: Konversi berbagai format dokumen seperti Word, Excel, PowerPoint, PDF, JSON, Gambar, dan lainnya menggunakan C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konversi Dokumen menggunakan C++" h2="Konversi Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Gambar, dan berbagai format lainnya menggunakan pustaka C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) memecahkan masalah konversi dokumen dan pengembang dapat mengotomatiskan manajemen dokumen dan solusi manipulasi dengan mudah dengan mengintegrasikan API dalam aplikasi baru yang dikembangkan atau dalam aplikasi yang sudah ada. Pemrogram C++ dapat menambahkan fungsionalitas seperti membuat, mengedit, atau mengonversi berbagai format dokumen dalam solusi mereka tanpa bergantung pada perangkat lunak apa pun. Beberapa kasus umum seperti txt ke PDF, SVG ke PNG, XLSX ke CSV, JSON ke CSV, Word ke PDF, HTML ke PDF, dapat dengan mudah dikonversi. Selain itu, Beberapa kasus yang ditangani API tercantum di bawah ini dan beberapa tautan yang diberikan untuk kasus konversi yang relevan. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konversi Microsoft Word ke Excel" %}}
Total C++ API mendukung konversi Microsoft Word DOC/DOCX ke Excel.  Prosesnya adalah, Muat file Word DOC / DOCX menggunakan referensi kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dan aktifkan [Save](https://reference. aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) fungsi anggota untuk dikonversi ke HTML terlebih dahulu. Kemudian muat dokumen HTML dengan menggunakan referensi kelas [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) dan aktifkan [Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) fungsi anggota untuk menyimpan dokumen ke format Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Konversi Word ke Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi PDF ke Word" %}}
Pustaka konversi C++ juga mendukung PDF ke Word DOC, DOCX dan konversi format lainnya. Mempertimbangkan kasus rendering PDF ke RTF, Ini adalah proses dua langkah, pertama-tama mengonversi PDF ke format Word DOC/DOCX dan kemudian merendernya ke RTF. Langkah-langkah yang disertakan untuk ini, Memuat file PDF menggunakan referensi kelas [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) dan menjalankan [Save](https://reference.aspose .com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) fungsi anggota untuk mengonversi PDF ke Word. Sekarang muat lagi file Word DOC / DOCX dengan menggunakan [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference dari Aspose.Words API dan simpan ke format RTF menggunakan [Simpan](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) fungsi anggota.

{{% blocks/products/pf/feature-page-code h3="C++ - Konversi PDF ke Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Konversi JSON ke Word" %}}
Untuk konversi JSON, C++ API mendukung berbagai kombinasi seperti JSON ke Word, Json ke PowerPoint, Word ke JSON dll. Mempertimbangkan kasus konversi Word, Prosesnya adalah, baca data JSON yang valid dari file dengan menggunakan objek [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) baru dan kemudian panggil [Simpan](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) untuk menyimpan JSON sebagai file PDF. Jadi sekarang muat file yang disimpan menggunakan kelas [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dan simpan ke format dokumen word menggunakan [Save](https://reference .aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Konversi JSON ke Kata" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}