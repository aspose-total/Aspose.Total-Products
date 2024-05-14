---
title: 在線刪除 PPTM 註釋或使用 Android 行動應用程式管理註釋
description: 透過線上應用程式免費刪除 PPTM 檔案中的註釋。用於管理 PPTM 檔案註解的 Android API 程式碼。

family: total
platformtag: Android
feature: Annotate
informat: PPTM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="清除 PPTM 線上簡報中的註解或透過 Android 應用程式進行管理" h2="開發強大的基於 Android 的 PPTM 演示註釋實用程式。列出用於管理 PPTM 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 PPTM 註釋" %}}

1. 匯入PPTM檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 PPTM 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式刪除 PPTM 簡報註釋" %}}

1. 新增庫引用到android項目
1. 透過Presentation類別物件載入PPTM
1. 透過 Presentation.getCommentAuthors() 集合迭代每位作者
1. 呼叫clear()方法刪除其註釋
1. 最後調用getCommentAuthors().clear()刪除所有作者
1. 呼叫save方法儲存文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：從 PPTM 簡報中刪除評論和作者" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式新增 PPTM 簡報評論" %}}

1. 新增庫引用到android項目
1. 透過Presentation類別物件載入PPTM
1. 呼叫Presentation.getCommentAuthors().addAuthor(String, String)新增作者
1. 使用ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date)新增註釋
1. 呼叫save方法儲存文件 with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：新增註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>開發 PPTM 文件註釋 Android 應用程式</h2>

需要開發 PPTM 註釋行動應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/zh-hant/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/zh-hant/android-java/) 的子 API），任何 Android 開發人員都可以將上述 API 程式碼整合到其文件註釋應用程式中。強大的 android 庫允許對任何文檔註釋解決方案進行編程。而且它可以支援許多流行的格式，包括PPTM格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註釋 PPTM 檔案的 Android 函式庫" %}}

- 我們在 [Maven 儲存庫](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/) 中託管 Java 套件。 
- Aspose.Slides for Java 是包含字節碼的常見 JAR 檔案。
- 請依照 [逐步說明](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) 了解如何安裝 Aspose.Slides for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

- J2SE 6.0 (Java 1.6) 及更高版本
- Java套件是跨平台的，可以在所有具有JVM實作的作業系統上運行。

<br />
欲了解更多詳情，請參閱[產品文件](https://docs.aspose.com/slides/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}