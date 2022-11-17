---
title: 通過 C++ 進行文檔轉換 

description: 使用 C++ API 轉換各種文檔格式，例如 Word、Excel、PowerPoint、PDF、JSON、圖像等。 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 C++ 進行文檔轉換" h2="使用 C++ 庫轉換 Microsoft<sup>&reg;</sup> Office Word、Excel、PowerPoint、PDF、圖像和各種其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) 解決了文檔轉換問題，開發人員可以通過在新開發的應用程序或現有應用程序中集成 API 輕鬆地自動化文檔管理和操作解決方案。 C++ 程序員可以在其解決方案中添加創建、編輯或轉換各種格式文檔等功能，而無需依賴任何軟件。很少有通用案例，如 txt 轉 PDF、SVG 轉 PNG、XLSX 轉 CSV、JSON 轉 CSV、Word 轉 PDF、HTML 轉 PDF，可以輕鬆轉換。 此外，下面列出的 API 處理的案例很少，相關轉換案例的鏈接也很少。 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="將 Microsoft Word 轉換為 Excel" %}}
Total C++ API 支持 Microsoft Word DOC/DOCX 到 Excel 的轉換。  過程是，使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類引用加載 Word DOC / DOCX 文件並調用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 成員函數首先轉換為 HTML。 然後使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類引用加載 HTML 文檔並調用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) 成員函數將文檔保存為 Excel 格式。 

{{% blocks/products/pf/feature-page-code h3="C++ - Word 到 Excel 的轉換" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF 到 Word 轉換" %}}
C++轉換庫還支持PDF到word DOC、DOCX等格式的轉換。 考慮到將 PDF 渲染為 RTF 的情況，這是一個兩步過程，首先將 PDF 轉換為 Word DOC/DOCX 格式，然後將其渲染為 RTF。 為此包括的步驟，使用 [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 類引用加載 PDF 文件並調用 [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) 將 PDF 轉換為 Word 的成員函數。 現在使用 Aspose.Words API 的 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類參考再次加載 Word DOC / DOCX 文件，並將其保存為 RTF 格式[保存](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) 成員函數。

{{% blocks/products/pf/feature-page-code h3="C++ - PDF 到 Word 轉換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="將 JSON 轉換為 Word" %}}
對於 JSON 轉換，C++ API 支持多種組合，例如 JSON 轉 Word、Json 轉 PowerPoint、Word 轉 JSON 等。 考慮到 Word 轉換的情況，Process 是使用新的 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 對像從文件中讀取有效的 JSON 數據，然後調用[保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 方法將 JSON 保存為 PDF 文件。 所以現在使用 [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) 類加載保存的文件，並使用 [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) 將其保存為 word 文檔格式 方法。
{{% blocks/products/pf/feature-page-code h3="C++ - JSON 到 Word 的轉換" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}