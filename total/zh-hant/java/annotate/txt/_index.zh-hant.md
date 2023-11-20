---
title: 線上刪除 TXT 註釋或透過 Java 管理註釋
description: 透過線上應用程式免費刪除 TXT 檔案中的註釋。用於管理 TXT 檔案註解的 Java API 程式碼。

family: total
platformtag: Java
feature: Annotate
informat: TXT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="從 TXT 線上文件或透過 Java 管理清除註釋" h2="開發強大的基於 Java 的 TXT 文件註解實用程式。列出了透過 Java 管理 TXT 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 TXT 註釋" %}}

1. 匯入TXT檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 TXT 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Java 刪除 TXT 文件註釋" %}}

1. 新增庫引用到Java項目
1. 透過Document類別物件載入Document
1. 使用 [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) 和 NodeType.COMMENT 取得所有節點的所有評論
1. 呼叫[clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)方法刪除所有評論
1. 呼叫save方法儲存檔。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="從 TXT 檔案中刪除註解的 Java 程式碼範例" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="刪除並添加 TXT 評論回复" %}}

1. 新增庫引用到Java項目
1. 透過Document類別物件載入Document
1. 使用 getChild 取得評論
1. 使用 [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) 刪除對此評論的指定回复
1. 使用 [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) 添加對此評論的回复
1. 呼叫save方法儲存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Java 新增評論" %}}

1. 新增庫引用到Java項目
1. 建立文檔類別對象
1. 使用 [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) 建立評論
1. 使用 getParagraphs().add 和 getFirstParagraph().getRuns().add
1. 呼叫save方法儲存文件 with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="用於從 TXT 檔案中刪除和新增註解回應的 Java 程式碼" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Java 程式碼：新增註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>透過Java開發TXT文件註解應用程式</h2>

需要開發 TXT 註釋應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Words for Java](https://products.aspose.com/words/java/)（[Aspose.Total for Java](https://products.aspose.com/total/java/) 的子 API），任何 Java 開發人員都可以將上述 API 程式碼整合到其文件註解應用程式中。強大的 Java 程式庫允許對任何文件註解解決方案進行程式設計。而且它可以支援許多流行的格式，包括TXT格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註解 TXT 檔案的 Java 函式庫" %}}
還有其他選項可以將“[Aspose.Words for Java](https://products.aspose.com/words/java/)”或“[Aspose.Total for Java](https://products.aspose.com/total/java/)”安裝到您的系統上。我們的 Java 套件被設計為跨平台的，與 Microsoft Windows、Linux、macOS、Android 和 iOS 等各種作業系統上的 JVM 實作相容。請選擇符合您需求的一項並按照逐步說明進行操作：<br />

- 安裝[Aspose.Words for Java](https://docs.aspose.com/words/java/installation/)
- 或來自[Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-words/)
- 一步一步 [指示](https://docs.aspose.com/words/java/installation/#install-aspose-words-for-java-from-maven-repository)

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

- Java SE 7 或最新的 Java 版本
- Java SE 6 的單獨包裝以防您有這個過時的 JRE。

<br />
有關 JogAmp JOGL、Harfbuzz 字體引擎和 Java Advanced Imaging JAI 的詳細資訊請參閱 [產品文件](https://docs.aspose.com/words/java/system-requirements/#optional-dependencies)。

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
                          <span itemprop="name"><b>我可以在我的應用程式中使用上述 Java 程式碼嗎？</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">是的，歡迎您下載此程式碼並使用它來開發基於 Java 的文檔註釋應用程式。此程式碼可以作為寶貴的資源來增強專案在後端文件處理和操作領域的功能和能力。</span>
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
                          <span itemprop="name"><b>使用線上應用程式註解 TXT 文件是否安全？</b></span>
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
                          <span itemprop="text">您可以使用任何現代網頁瀏覽器（例如 Google Chrome、Firefox、Opera 或 Safari）進行線上 TXT 文件註釋。但是，如果您正在開發桌面應用程序，我們建議使用 Aspose.Total 文件處理 API 進行高效管理。</span>
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