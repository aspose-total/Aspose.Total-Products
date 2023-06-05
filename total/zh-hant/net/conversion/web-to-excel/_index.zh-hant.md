---
title: 使用 C# 提取網站數據並將網頁 HTML 轉換為 Excel 文件
description: 抓取網站網頁以及將 HTML 導出到 Microsoft Excel 文檔。開發 .NET 應用程序以將網站數據抓取為 XLS、XLSX 格式。
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: EXCEL
otherformats: WORD POWERPOINT PDF IMAGES
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C# 將網頁轉換為 Excel" h2="從 HTML 中提取網頁數據。在 .NET 應用程序中將 HTML 導入 Microsoft Excel XLS、XLSX 格式。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<p>網頁是互聯網的重要組成部分，它們包含對個人和組織有用的大量信息。 然而，一些用戶可能會發現從網頁中提取數據具有挑戰性，尤其是當信息分佈在多個頁面時。在這種情況下，將網頁轉換為 Excel 格式可能是一個有用的解決方案。</p><br />
<p>將網頁轉換為 Excel 格式涉及將網頁上的數據轉換為可以輕鬆導入 Excel 的結構化格式。 可以使用專門為此目的設計的軟件工具自動執行此過程。 這些工具可以從多個網頁中提取數據並將它們轉換成單個 Excel 文件，可以根據需要進行分析和操作。</p><br />

<p>但是，重要的是要強調在網絡抓取方面負責任和道德實踐的重要性。 尊重網站的服務條款，遵守法律規定，避免從事可能侵犯隱私或知識產權的活動，都是需要考慮的重要方面。</p>

<h2 class="heading-border">使用 Aspose.HTML 作為 Scraper API</h2>

<p>通過利用 Aspose.HTML for .NET API（它是 Aspose.Total for .NET 的一個組件），您可以無縫地創建自己的應用程序，用於分析 HTML 文檔並從中提取數據。 這個 API 提供了一套全面的工具，大大簡化了這項工作，使您能夠有效地處理 HTML 內容。</p><br />

<p>在開發爬蟲的過程中，數據選擇器對於從 HTML 文件中識別和提取所需信息具有重要意義。 這些選擇器通常使用 XPath、CSS 選擇器或兩者的結合，作為在 HTML 結構中定位特定數據元素的有價值的工具。 作為一種導航機制，這些選擇器有助於精確定位和提取您要檢索的數據。</p>

<h2 class="heading-border">Web Scrapping 可以執行的任務</h2>

<p>通過使用 Aspose.HTML for .NET，開發人員可以毫不費力地自動化從網頁中提取數據的過程，使他們能夠有效地完成以下網頁抓取任務。</p><br />

1. [HTML Navigation](https://docs.aspose.com/html/net/html-navigation/) - 徹底分析 HTML 文檔及其元素。受益於詳細分析、元素迭代的自定義過濾以及使用 CSS 選擇器或 XPath 的無縫導航等功能。
2. [下載網站](https://docs.aspose.com/html/net/download-website/) - 從 URL 高效地下載網站並自定義下載過程。 根據您的具體要求選擇下載整個網站或特定網頁。
3. [從 URL 下載文件](https://docs.aspose.com/html/net/download-file-from-url/) - 從 URL 輕鬆下載文件。
4. [從網站下載圖像](https://docs.aspose.com/html/net/download-images-from-website/) - 從網站下載各種類型的圖像。
5. [從網站下載 SVG](https://docs.aspose.com/html/net/download-svg-from-website/) - 使用 C# 從網站檢索可縮放矢量圖形 (SVG) 文件。

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何使用 C# 提取 Web 數據？" %}}

1. 使用 URL 從 URL 初始化 HTML 文檔 [HTMLDocument](https://reference.aspose.com/html/net/aspose.html/htmldocument/htmldocument/) 構造函數。
2. 使用指定選擇器 [QuerySelectorAll(selector)](https://reference.aspose.com/html/net/aspose.html.dom/document/queryselectorall/) 方法檢索與選擇器匹配的所有元素。
3. 遍曆元素列表並根據您的特定要求格式化輸出。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="網頁抓取和轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total``` 或直接從 Visual Studio 的包管理器控制台安裝。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子 API， [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 和 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) 將被整合。

或者，從 ZIP 文件中獲取脫機 MSI 安裝程序或 DLL [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "extract-data-using-csharp.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="使用 Aspose.Cells 將 HTML 轉換為 Excel" %}}
<p>要將 HTML 轉換為 XLS，您可以使用 Aspose.Cells for .NET API，它允許您僅用幾行代碼以編程方式執行此任務。 使用 API，您可以開發跨平台的應用程序，這些應用程序能夠生成、修改、轉換、呈現和打印各種 Excel 文件。 .NET Excel API 超越了簡單的格式轉換，因為它還可以將 Excel 文件呈現為圖像、PDF、HTML、ODS、CSV、SVG、JSON、WORD、PPT 等。 這種全面的功能使其成為以行業標準格式交換文檔的絕佳選擇。</p><br />

<p>將 HTML 轉換為 Microsoft Excel XLS，C# 中的 XLSX 對於 .NET 開發人員來說是一個簡單的過程。 您只需幾行代碼即可實現此目的：</p><br />

1. 通過創建 Workbook 類的實例來加載 HTML 文件。
1. 通過調用 Workbook 實例上的 Save 方法，將加載的 HTML 轉換為 Excel。

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-html-to-excel.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}