---
title: 使用 C++ 在線從 Word 檔案中提取文字和圖像
description: 線上 Word 檔案解析器應用程式。用於從 Word 文件中提取圖像和文字內容的 C++ API 程式碼。

family: total
platformtag: cpp
feature: Parse
informat: Word
otherformats: Word DOCX DOC DOTX DOT RTF ODT OTT PDF Excel XLS XLSX XLSM XLSB ODS Powerpoint PPT PPTX ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在線以及透過 C++ 解析 Word 文件" h2="開發強大的基於 C++ 的 Word 文件解析器實用應用程式。列出用於 Word 文件文字擷取的 C++ 程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="透過線上應用程式解析 Word 文檔" %}}

1. 透過上傳導入Word檔案進行解析。
1. 透過拖放解析器應用程式在放置區域內點擊來完成此操作。
1. 根據 Word 檔案的大小和網路速度，等待幾秒鐘。
1. 按一下“立即解析”按鈕來解析文件。
1. 下載解析的文件以立即查看。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過C++解析Word文件" %}}

1. 將庫引用新增至 C++ 項目
1. 加載Word文件
1. 使用 GetChildNodes 取得所有子節點
1. 使用 NodeType::Shape 作為參數
1. 遍歷每個節點並保存圖像
1. 使用 shape->get_ImageData()->Save 方法儲存提取的文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++程式碼：Word文件影像擷取" offSpacer="" %}}

{{< gist "aspose-com-gists" "0916cd11f2eb51ded9c1c14a8a1a3f68" "parse-word-document-by-extracting-images.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>透過 C++ 開發 Word 檔案解析器應用程式</h2>

需要開發 Word 解析器應用程式或軟體？透過 [Aspose.Words for C++](https://products.aspose.com/words/cpp/)（[Aspose.Total for C++](https://products.aspose.com/total/zh-hant/cpp/) 的子 API），任何 C++ 開發人員都可以將上述 API 程式碼整合到其文件解析器應用程式中。強大的 C++ 庫允許對任何文件解析解決方案進行編程以提取圖像和文字。而且它可以支援許多流行的格式，包括Word格式。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於為解析器應用程式處理 Word 檔案的 C++ 實用程式" %}}

您可以透過三個選項將 Aspose.Words for C++ 或 Aspose.Total for C++ 安裝到您的開發環境中。請選擇符合您需求的一項並按照逐步說明進行操作：<br /><br />

- 安裝 [NuGet 套件](https://www.nuget.org/packages/Aspose.Words.Cpp/)。參見 [文件](https://docs.aspose.com/words/cpp/installation/#install-or-update-aspose-words-for-cpp-using-nuget)
- 在 Visual Studio IDE 中使用 [套件管理器控制台](https://docs.aspose.com/words/cpp/installation/#install-or-update-asposewords-using-package-manager-console) 安裝程式庫
- 使用 [Windows安裝程式](https://docs.aspose.com/words/cpp/installation/#install-asposewords-for-c-by%20hand) 手動安裝庫

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}
您可以使用此 C++ 程式庫在 Microsoft Windows、Linux 和 macOS 作業系統上開發軟體：<br /><br />

- Linux 需要 GCC >= 6.3.0 和 Clang >= 3.9.1
- macOS 需要 Xcode >= 12.5.1、Clang 和 libc++

<br /><br />
如果您為 Linux 或 macOS 開發軟體，請檢查 [產品文件](https://docs.aspose.com/words/cpp/system-requirements/) 中有關其他函式庫相依性（fontconfig 和 mesa-glu 開源套件）的資訊。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="常見問題解答" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>常見問題解答</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>我可以在我的應用程式中使用上述 C++ 程式碼嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，歡迎您下載此程式碼並使用它來開發基於 C++ 的文檔解析器應用程式。此程式碼可以作為寶貴的資源來增強專案在後端文件處理領域的功能和能力，例如讀取節點和載入文件以進行文字和圖像提取。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>這個線上文件解析器應用程式只能在 Windows 上運行嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以靈活地在任何裝置上啟動文件解析，無論其執行的作業系統是 Windows、Linux、Mac OS 還是 Android。所需要的只是一個現代的網路瀏覽器和一個活躍的網路連線。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用線上應用程式解析 Word 文件安全嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">當然！透過我們的服務產生的輸出檔案將在 24 小時內安全地自動從我們的伺服器中刪除。因此，與這些文件關聯的顯示連結將在此期限後停止運行。</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>App該用什麼瀏覽器？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以使用任何現代 Web 瀏覽器（例如 Google Chrome、Firefox、Opera 或 Safari）作為線上 Word 文件解析器。但是，如果您正在開發桌面應用程序，我們建議使用 Aspose.Total 文件處理 API 進行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}