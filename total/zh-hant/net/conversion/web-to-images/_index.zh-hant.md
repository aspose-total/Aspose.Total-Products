---
title: 使用 C# 將網頁 HTML 轉換為圖像
description: 抓取網站網頁並將 HTML 導出到圖像。開發 .NET 應用程序以將網站數據抓取為 JPEG、PNG、GIF、BMP 等格式。 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C# 將網頁轉換為圖像" h2="從 HTML 網頁中提取網站數據。在 .NET 應用程序中將 HTML 轉換為 JPG、GIF、PNG、BMP 圖像。" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">為什麼要將網頁轉換為圖像？</h2>
<p>將網頁轉換為圖像在多種情況下都很有用。這是許多應用程序的共同要求。 在某些情況下，需要將整個網頁捕獲為圖像，包括屏幕上不可見的部分。 這對於生成網站預覽、捕獲收據和發票或出於法律目的存檔網頁很有用。它可用於創建用於文檔或測試目的的網頁屏幕截圖。 它還可用於創建網頁的縮略圖或預覽，以用於搜索結果或圖像庫。 無論您是構建桌面應用程序還是 Web 應用程序，都有許多選項可用於使用 C# 將網頁轉換為圖像。</p><br />

<p>使用 C# 將網頁轉換為圖像可以提供多種好處，包括：</p><br />
<ul>
<li>改進的可訪問性： 對於有視覺障礙或其他殘疾的人來說，圖像可以更容易閱讀和理解。</li>
<li>增加便攜性： 圖像可以輕鬆共享或嵌入到其他文檔或應用程序中。</li>
</ul>
<p>使用 C# 將網頁轉換為圖像也會帶來一些挑戰，包括：</p><br />
<ul>
<li>有限的格式支持： 某些 API 或工具可能不支持所有圖像格式，或者可能對輸出圖像的大小或分辨率有限制。</li>
<li>兼容性問題： 某些網頁可能無法在所有瀏覽器中正確呈現，或者可能需要特定設置或插件才能正確顯示。</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何使用 C# 將網頁轉換為圖像？" %}}
要使用 C# 將網頁轉換為圖像，您可以使用 Aspose.HTML for .NET API，它提供將 HTML 頁面轉換為圖像格式（包括 JPEG、PNG 和 TIFF）的功能。</p>

1. 使用其中可用的構造函數之一加載 HTML 文檔 [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). 您可以從文件、HTML 代碼、流或 URL 加載 HTML。
2. 創建一個新的實例 [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) 並將 ImageFormat 屬性設置為 JPEG。默認情況下，格式屬性設置為 PNG。
3. 利用 [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) Converter 類中的方法將 HTML 文檔保存為 JPEG 文件。 您需要將 HTMLDocument、ImageSaveOptions 和輸出文件路徑作為參數提供給 ConvertHTML() 方法。
4. 生成的 JPEG 文件將保存到指定的文件路徑。
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Web 抓取和圖像轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total``` 或直接從 Visual Studio 的包管理器控制台安裝。

二 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 子API， [Aspose.HTML for .NET](https://products.aspose.com/html/net/) 將被整合。

或者，從 ZIP 文件中獲取脫機 MSI 安裝程序或 DLL [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}