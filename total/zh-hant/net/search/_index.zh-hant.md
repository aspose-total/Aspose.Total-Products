---
title: 透過 C# .NET 搜尋文檔 

description: 透過 .NET 應用程式搜尋文檔，包括 PDF、Microsoft Office Excel、Word、PowerPoint 等。 透過應用程式在線上搜尋文件。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="使用 .NET API 搜尋文檔" h2="使用 Aspose.Total for .NET 以高效的方式輕鬆地從各種文件（包括 Microsoft Office Word、Excel、PowerPoint 和 PDF 文件）中搜尋和取得資料。" >}}

{{% blocks/products/pf/feature-page-summary %}}

為不同的文件文件格式啟用文字搜尋和內容索引使用戶能夠優化生產力、簡化資料檢索並增強跨組織和應用程式的資訊管理。 透過在文件中啟用基於文字的搜尋並建立索引以從各種文件文件格式中高效檢索訊息，增強基於 .NET 的軟體或系統的功能。

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="在文件中搜尋的主要原因" %}}

1. 文件組織
1. 資訊檢索
1. 內容驗證 
1. 內容總結 
1. 文字分析
1. 資料擷取 
1. 文件索引 


{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="搜尋 PDF 文檔" %}}

我們使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，它是 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 的子 API，專為特定文件操作功能以及與檢索和搜尋文件內容相關的任務而設計。 下面的程式碼片段是用 C# 編寫的，用於與 PDF 文件互動。 它首先設定正規表示式模式來搜尋文件中的非空白字元序列。 接下來，它會存取 PDF 的第一頁，並使用 TextFragmentAbsorber 使用指定的正規表示式搜尋該頁面上的文字。 然後，程式碼將發現的文字片段收集到一個集合中。 最後，它迭代該集合並將每個識別的文本片段輸出到控制台。本質上，此程式碼片段可作為從 PDF 文件中提取和顯示特定文字模式的機制。 此外，.NET Search API 也支援 Microsoft [Word文件搜尋](https://products.aspose.com/total/net/search/word/) 和其他格式。

{{% blocks/products/pf/feature-page-code h3="PDF 文件搜尋的 C# 程式碼" %}}

{{< gist "aspose-com-gists" "3c806eb023f399cd402ab922a247f2d0" "pdf-document-search.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}