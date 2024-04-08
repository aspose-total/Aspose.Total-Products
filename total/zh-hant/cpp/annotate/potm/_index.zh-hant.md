---
title: 線上刪除 POTM 註釋或透過 C++ 管理註釋
description: 透過線上應用程式免費刪除 POTM 檔案中的註釋。用於管理 POTM 檔案註解的 C++ API 程式碼。

family: total
platformtag: cpp
feature: Annotate
informat: POTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT POL PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="從 POTM 線上演示中清除註解或透過 C++ 管理" h2="開發功能強大的基於 C++ 的 POTM 演示註解實用程式。列出了透過 C++ 管理 POTM 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 POTM 註釋" %}}

1. 匯入POTM檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 POTM 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 C++ 刪除 POTM 簡報註釋" %}}

1. 將庫引用新增至 C++ 項目
1. 加載 POTM 演示文稿
1. 透過presentation->get_CommentAuthors() 迭代每個作者
1. 呼叫 get_Comments()->Clear() 方法刪除評論
1. 呼叫 get_CommentAuthors()->Clear() 方法刪除所有作者
1. 呼叫Save方法儲存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C++ 程式碼：從 POTM 簡報中刪除評論和作者" offSpacer="" %}}

{{< gist "aspose-com-gists" "5449a615aff20a8e0cdcf09b94d2989c" "delete-powerpoint-presentation-annotations.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>透過C++開發POTM文件註解應用程式</h2>

需要開發 POTM 註釋應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/)（[Aspose.Total for C++](https://products.aspose.com/total/zh-hant/cpp/) 的子 API），任何 C++ 開發人員都可以將上述 API 程式碼整合到其文件註解應用程式中。強大的 C++ 程式庫允許對任何文件註解解決方案進行程式設計。而且它可以支援許多流行的格式，包括POTM格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註解 POTM 檔案的 C++ 函式庫" %}}

您可以選擇將 Aspose.Slides for C++ 或 Aspose.Total for C++ 安裝到您的系統上。請選擇符合您需求的一項並按照逐步說明進行操作：<br /><br />

- Install a [NuGet 套件](https://www.nuget.org/packages/Aspose.Slides.Cpp/). See [文件](https://docs.aspose.com/slides/cpp/installation/#option-one-install-or-update-asposeslides-for-c-from-the-nuget-package-manager)
- 在 Visual Studio IDE 中使用 [套件管理器控制台](https://docs.aspose.com/slides/cpp/installation/#option-2-install-or-update-asposeslides-through-the-package-manager-console) 安裝程式庫


{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}
您可以使用此 C++ 程式庫在 Microsoft Windows、Linux 和 macOS 作業系統上開發軟體：<br /><br />

- Linux 需要 GCC >= 6.3.0 和 Clang >= 3.9.1
- macOS 需要 Xcode >= 12.5.1、Clang 和 libc++

<br /><br />
如果您為 Linux 或 macOS 開發軟體，請檢查 [產品文件](https://docs.aspose.com/slides/cpp/system-requirements/) 中有關其他函式庫相依性（fontconfig 和 mesa-glu 開源套件）的資訊。

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
                          <span itemprop="text">是的，歡迎您下載此程式碼並使用它來開發基於 C++ 的文件註解應用程式。此程式碼可以作為寶貴的資源來增強專案在後端文件處理和操作領域的功能和能力。</span>
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
                          <span itemprop="name"><b>使用線上應用程式註解 POTM 文件是否安全？</b></span>
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
                          <span itemprop="text">您可以使用任何現代網頁瀏覽器（例如 Google Chrome、Firefox、Opera 或 Safari）進行線上 POTM 文件註釋。但是，如果您正在開發桌面應用程序，我們建議使用 Aspose.Total 文件處理 API 進行高效管理。</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}