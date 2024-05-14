---
title: 在線刪除 TXT 註釋或使用 Android 行動應用程式管理註釋
description: 透過線上應用程式免費刪除 TXT 檔案中的註釋。用於管理 TXT 檔案註解的 Android API 程式碼。

family: total
platformtag: Android
feature: Annotate
informat: TXT
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在線清除 TXT 文件中的註釋或透過 Android 應用程式進行管理" h2="開發強大的基於 Android 的 TXT 文件註釋實用程式。列出用於管理 TXT 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 TXT 註釋" %}}

1. 匯入TXT檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 TXT 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式刪除 TXT 文件註釋" %}}

1. 新增庫引用到android項目
1. 透過Document類別物件載入Document
1. 使用 [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) 和 NodeType.COMMENT 取得所有節點的所有註釋
1. 呼叫[clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)方法刪除所有註釋
1. 呼叫save方法儲存檔。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：刪除TXT檔案中的註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="刪除並添加 TXT 評論回复" %}}

1. 新增庫引用到android項目
1. 透過Document類別物件載入Document
1. 使用 getChild 取得評論
1. 使用 [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) 刪除對此評論的指定回复
1. 使用 [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) 添加對此評論的任何回复
1. 呼叫save方法儲存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式新增評論" %}}

1. 新增庫引用到android項目
1. 建立文檔類別對象
1. 使用[Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/)建立註釋
1. 使用 getParagraphs().add 和 getFirstParagraph().getRuns().add
1. 呼叫save方法儲存文件 with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代碼：從 TXT 檔案中刪除並新增註釋回复" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="程式碼：新增註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>開發 TXT 文件註釋 Android 應用程式</h2>

需要開發 TXT 註釋行動應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Words for Android via Java](https://products.aspose.com/words/zh-hant/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/zh-hant/android-java/) 的子 API），任何 Android 開發人員都可以將上述 API 程式碼整合到其文件註釋應用程式中。強大的 android 庫允許對任何文檔註釋解決方案進行編程。而且它可以支援許多流行的格式，包括TXT格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註釋 TXT 檔案的 Android 函式庫" %}}

- 我們在 [Maven 儲存庫](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) 中託管 Java 套件。 
- Aspose.Words for Java 是包含字節碼的常見 JAR 檔案。
- 請依照 [逐步說明](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) 了解如何安裝 Aspose.Words for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

- 支援 Java SE 7 和更新的 Java 版本。
- Java SE 6 的單獨包，以防必須使用過時的 JRE。
- Java套件是跨平台的，可以在所有具有JVM實作的作業系統上運行。
- 作業系統包括 Microsoft Windows、Linux、macOS、Android 和 iOS。

<br />
有關可選包依賴項的更多詳細信息，例如 JogAmp JOGL、Harfbuzz 字體引擎、Java Advanced Imaging JAI，請參閱 [產品文件](https://docs.aspose.com/words/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}