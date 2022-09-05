---
title: Document Conversion via C++ 
url: /cpp/conversion/
description: Convert various document formats such as Word, Excel, PowerPoint, PDF, JSON, Images and more using C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Document Conversion using C++" h2="Convert Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Images and various other formats using C++ library." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) solves the issue of document conversion and developers can automate the document management and manipulation solution eaisly by integrating API within new developed applications or in existing applications. C++ Programmers can add functionalities like create, edit or convert various format documents within their solution without relying on any software. Few generic cases like txt to PDF, SVG to PNG, XLSX to CSV, JSON to CSV, Word to PDF, HTML to PDF, one can easily convert. Moreover, Few cases that API deals listed below and few links given for the relevant conversion cases. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Word to Excel" %}}
Total C++ API supports Microsoft Word DOC/DOCX to Excel conversion.  Process is,  Load Word DOC / DOCX file using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference and invoke [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) member function to convert into HTML firstly. Then load HTML document by using [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) class reference and invoke [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) member function to save the document to Excel format. 

{{% blocks/products/pf/feature-page-code h3="C++ - Word to Excel Conversion" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF to Word Conversion" %}}
C++ conversion library also supports PDF to word DOC, DOCX and other format conversion. Considering the case of rendering PDF to RTF, It's a two step process, firstly convert PDF to Word DOC/DOCX format and then render that to RTF. Steps included for this, Loading PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference and invoking [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) member function to convert PDF to Word. Now load again Word DOC / DOCX file by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference of Aspose.Words API and save it to RTF format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) member function.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF to Word Conversion" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert JSON to Word" %}}
For JSON conversion, C++ API supports various combinations such as JSON to Word, Json to PowerPoint, Word to JSON etc. Considering the case of Word conversion, Process is, read valid JSON data from file by using a new [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object and then invoke [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) method to save JSON as PDF file. So now load saved file using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class and save it to word document format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method.
{{% blocks/products/pf/feature-page-code h3="C++ - JSON to Word Conversion" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}