---
title: 在線刪除 PDF 註釋或使用 Android 行動應用程式管理註釋
description: 透過線上應用程式免費刪除 PDF 檔案中的註釋。用於管理 PDF 檔案註解的 Android API 程式碼。

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在線清除 PDF 文件中的註釋或透過 Android 應用程式進行管理" h2="開發強大的基於 Android 的 PDF 文件註釋實用程式。列出用於管理 PDF 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 PDF 註釋" %}}

1. 匯入PDF檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 PDF 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式 API 刪除 PDF 文件註釋" %}}

1. 新增庫引用到android項目
1. 透過Document類別物件載入Document
1. 透過getPages().get_Item(Index)選擇特定頁面
1. 使用AnnotationSelector並透過annotationSelector.getSelected()取得所有文字註釋
1. 遍歷每個註釋並調用刪除方法將其刪除。
1. 呼叫save方法儲存檔。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：刪除PDF檔案中的註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android App API 新增註釋" %}}

1. 新增庫引用到android項目
1. 建立文檔類別對象
1. 使用 getPages().add() 新增頁面和內容
1. 使用 TextAnnotation 類別的 getPages().get_Item(Index)
1. 設定相關註釋，如標題、主題、內容等
1. 使用getAnnotations().add新增註釋
1. 呼叫save方法保存新增註解的文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代碼：新增PDF註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>開發 PDF 文件註釋 Android 應用程式</h2>

需要開發 PDF 註釋行動應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/zh-hant/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/zh-hant/android-java/) 的子 API），任何 Android 開發人員都可以將上述 API 程式碼整合到其文件註釋應用程式中。強大的 android 庫允許對任何文檔註釋解決方案進行編程。而且它可以支援許多流行的格式，包括PDF格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註釋 PDF 檔案的 Android 函式庫" %}}

- 我們在 [Maven 儲存庫](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/) 中託管 Java 套件。 
- Aspose.PDF for Java 是包含字節碼的常見 JAR 檔案。
- 請依照 [逐步說明](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) 了解如何安裝 Aspose.PDF for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

- Android API 31 和 32
- 安卓4.0及以上
- Android Studio 和 SDK 工具

<br />
有關可選包依賴項的更多詳細信息，例如 JogAmp JOGL、Harfbuzz 字體引擎、Java Advanced Imaging JAI，請參閱 [產品文件](https://docs.aspose.com/pdf/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}