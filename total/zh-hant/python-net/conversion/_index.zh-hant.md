---
title: 通過 Python 進行文檔轉換 
url: /zh-hant/python-net/conversion/
description: 只需幾行 Python 代碼即可將 Microsoft Word 格式 DOC、DOCX 轉換為 PDF、圖像等以及演示幻燈片、電子郵件消息和 3D 圖像。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 Python API 進行文檔轉換" h2="使用 Aspose.Words for Python 通過 .NET 轉換 Microsoft<sup>&reg;</sup> Office Word、PDF、圖像和各種其他格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) 加快了從頭開始開發文檔自動化解決方案或增強現有應用程序以創建、編輯或轉換文檔、演示文稿、電子郵件和 3D 文件的速度。 Python API 不僅可以處理 Microsoft Office Word 和演示文稿幻燈片，還可以處理 PDF、HTML、圖像和電子郵件文件等等。 API 不依賴於任何軟件，是一整套文檔管理和操作解決方案。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="將 Microsoft Word 轉換為 PDF" %}}
Total Python API 支持多種格式的轉換，例如 Microsoft Word 到 PDF、圖像、Markdown 和 HTML。 API 使將 Word 文檔轉換為 PDF 的過程變得簡單，其輸出質量與 DOC、DOCX 文件一樣接近文檔。 過程是將 DOC 或 DOCX 文件加載到 [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) 對像中，然後調用 [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) 方法，帶有目標 PDF 格式及其目錄路徑。 就是這麼簡單。如果需要指定 PDF 標準，如 PDF 1.7 或 1.5，API 提供 [PdfComplaence](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) 枚舉，用於設置[PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/)。 

{{% blocks/products/pf/feature-page-code h3="Python - Word 到 PDF 的轉換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Word 到圖像的轉換" %}}
文字到圖片的轉換是 Python API 的另一個功能。 除了轉換之外，還可以輕鬆設置各種保存選項，例如亮度、對比度、水平和垂直分辨率等。過程是，通過 Document 對象加載文檔，然後使用具有指定路徑的所需圖像文件擴展名調用 save 方法。 為了指定各種保存選項，API 提供了 [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/)、[FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) 或 [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) 類可以從所需的場景開始使用。 下面的代碼示例演示了通過應用一些附加設置來創建第一個文檔頁面的預覽。

{{% blocks/products/pf/feature-page-code h3="Python - 文字到圖像的轉換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="將 Microsoft PowerPoint 轉換為 Word" %}}
Python API 支持將 Microsoft PowerPoint PPT / PPTX 轉換為 Word DOC / DOCX 文件。 兩個 API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) 和 [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) 用於執行此轉換。 使用 [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) 加載 PPT / PPTX 文件。 獲取 Words Document 類對象。遍歷每張幻燈片，生成並插入幻燈片圖像，然後通過遍歷幻燈片形狀來插入幻燈片文本。

{{% blocks/products/pf/feature-page-code h3="Python - PowerPoint 幻燈片到 Word 轉換" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}