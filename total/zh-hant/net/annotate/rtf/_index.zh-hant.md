---
title: 線上刪除 RTF 註釋或透過 .NET 管理註釋
description: 透過線上應用程式免費刪除 RTF 檔案中的註釋。用於管理 RTF 檔案註解的 .NET API 程式碼。

family: total
platformtag: net
feature: Annotate
informat: RTF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="清除來自 RTF 線上文件的註解或透過 .NET 管理" h2="開發功能強大的基於 .NET 的 RTF 文件註解實用程式。列出用於透過 .NET 管理 RTF 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 RTF 註釋" %}}

1. 匯入RTF檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 RTF 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 .NET 刪除特定作者 RTF 文件註釋" %}}

1. 將庫引用新增至 .NET 項目
1. 透過Document類別物件載入Document
1. 使用具有 NodeType.Comment 的 GetChildNodes 取得所有節點註釋
1. 遍歷所有評論並匹配作者姓名
1. 呼叫Remove方法刪除特定作者評論

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# 程式碼：從 RTF 檔案中刪除特定作者註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="透過 .NET 新增評論" %}}

1. 建立文檔類別對象
1. 使用評論類
1. 使用 Paragraphs.Add 新增段落
1. 使用 FirstParagraph.Runs.Add 新增註釋
1. 或者另一種方法是使用 CommentRangeStart 和 CommentRangeEnd 類
1. 呼叫save方法保存新增註解的文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="提取所有評論" %}}

1. 透過Document類別物件載入Document
1. 建立一個ArrayList對象
1. 取得 NodeCollection 中的所有 GetChildNode
1. 遍歷每個集合並在ArrayList中添加註釋

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET 程式碼：從 RTF 檔案新增註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: 提取所有評論" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>透過.NET開發RTF文件註解應用程式</h2>

需要開發 RTF 註釋應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Words for .NET](https://products.aspose.com/words/net/)（[Aspose.Total for .NET](https://products.aspose.com/total/net/) 的子 API），任何 .NET 開發人員都可以將上述 API 程式碼整合到其文件註解應用程式中。強大的.NET 程式庫允許對任何文件註解解決方案進行程式設計。而且它可以支援許多流行的格式，包括RTF格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註解 RTF 檔案的 .NET 函式庫" %}}

可以透過三個替代選項將“Aspose.Words for .NET”或“Aspose.Total for .NET”安裝到您的系統上。請選擇符合您需求的一項並按照逐步說明進行操作：<br /><br />

- 安裝 [NuGet Package](https://www.nuget.org/packages/Aspose.Words/)。參見 [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- 在 Visual Studio IDE 中使用 [Package Manager Console](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) 安裝程式庫
- 使用 [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer) 手動安裝庫

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

我們的產品完全跨平台，支援遵循「.NET Standard 2.0」規範的所有主要 .NET 實作：<br /><br />

- Microsoft .NET Framework，從最早的2.0版本開始，到最新的「.NET Framework 4.8」結束
- .NET Core，從最早的2.0開始，到最新的「.NET 6」結束
- 單聲道 >= 2.6.7
<br /><br />
由於 .NET 程式碼不依賴底層硬體或作業系統，而僅依賴虛擬機，因此您可以自由地為 Windows、macOS、Android、iOS 和 Linux 開發任何類型的軟體。只要確保您已安裝對應版本的 .NET Framework、.NET Core、Windows Azure、Mono 或 Xamarin。<br /><br />
我們建議使用 Microsoft Visual Studio、Xamarin 和 MonoDevelop IDE 建立 C#、F#、VB.NET 應用程式。
<br /><br />
欲了解更多詳情，請參閱[Product Documentation](https://docs.aspose.com/words/net/system-requirements/)。

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
                          <span itemprop="name"><b>我可以在我的應用程式中使用上述 .NET 程式碼嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，歡迎您下載此程式碼並使用它來開發基於 .NET 的文件註解應用程式。此程式碼可以作為寶貴的資源來增強專案在後端文件處理和操作領域的功能和能力。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>這個線上文檔註釋應用程式只能在 Windows 上運行嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">您可以靈活地在任何裝置上啟動文件註釋以刪除註釋，無論其運行何種作業系統，無論是 Windows、Linux、Mac OS 還是 Android。所需要的只是一個現代的網路瀏覽器和一個活躍的網路連線。</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>使用線上應用程式註解 RTF 文件是否安全？</b></span>
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
                          <span itemprop="text">您可以使用任何現代網頁瀏覽器（例如 Google Chrome、Firefox、Opera 或 Safari）進行線上 RTF 文件註釋。但是，如果您正在開發桌面應用程序，我們建議使用 Aspose.Total 文件處理 API 進行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}