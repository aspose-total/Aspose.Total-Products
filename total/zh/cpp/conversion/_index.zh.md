---
title: 通过 C++ 进行文档转换 
url: /zh/cpp/conversion/
description: 使用 C++ API 转换各种文档格式，例如 Word、Excel、PowerPoint、PDF、JSON、图像等。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 C++ 进行文档转换" h2="使用 C++ 库转换 Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、图像和各种其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) 解决了文档转换问题，开发人员可以通过在新开发的应用程序或现有应用程序中集成 API 轻松地自动化文档管理和操作解决方案。 C++ 程序员可以在其解决方案中添加创建、编辑或转换各种格式文档等功能，而无需依赖任何软件。很少有通用案例，如 txt 转 PDF、SVG 转 PNG、XLSX 转 CSV、JSON 转 CSV、Word 转 PDF、HTML 转 PDF，可以轻松转换。 此外，下面列出的 API 处理的案例很少，相关转换案例的链接也很少。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="将 Microsoft Word 转换为 Excel" %}}
Total C++ API 支持 Microsoft Word DOC/DOCX 到 Excel 的转换。  过程是，使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类引用加载 Word DOC / DOCX 文件并调用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 成员函数首先转换为 HTML。 然后使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类引用加载 HTML 文档并调用 [Save](https://reference.aspose.com/ cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) 成员函数将文档保存为 Excel 格式。 

{{% blocks/products/pf/feature-page-code h3="C++ - Word 到 Excel 的转换" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF 到 Word 转换" %}}
C++转换库还支持PDF到word DOC、DOCX等格式的转换。 考虑到将 PDF 渲染为 RTF 的情况，这是一个两步过程，首先将 PDF 转换为 Word DOC/DOCX 格式，然后将其渲染为 RTF。 为此包括的步骤，使用 [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 类引用加载 PDF 文件并调用 [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) 将 PDF 转换为 Word 的成员函数。 现在使用 Aspose.Words API 的 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类参考再次加载 Word DOC / DOCX 文件，并将其保存为 RTF 格式[保存](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) 成员函数。

{{% blocks/products/pf/feature-page-code h3="C++ - PDF 到 Word 转换" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="将 JSON 转换为 Word" %}}
对于 JSON 转换，C++ API 支持多种组合，例如 JSON 转 Word、Json 转 PowerPoint、Word 转 JSON 等。 考虑到 Word 转换的情况，Process 是使用新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 对象从文件中读取有效的 JSON 数据，然后调用[保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法将 JSON 保存为 PDF 文件。 所以现在使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 类加载保存的文件，并使用 [Save](https://reference) 将其保存为 word 文档格式.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 方法。
{{% blocks/products/pf/feature-page-code h3="C++ - JSON 到 Word 的转换" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}