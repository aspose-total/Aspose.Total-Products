---
title: 在線刪除 Excel 註釋或使用 Android 行動應用程式管理註釋
description: 透過線上應用程式免費刪除 Excel 檔案中的註釋。用於管理 Excel 檔案註解的 Android API 程式碼。

family: total
platformtag: Android
feature: Annotate
informat: Excel
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在線清除 Excel 文件中的註釋或透過 Android 應用程式進行管理" h2="開發強大的基於 Android 的 Excel 文件註釋實用程式。列出用於管理 Excel 檔案註解的程式碼。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="線上刪除 Excel 註釋" %}}

1. 匯入Excel檔案上傳刪除評論
1. 透過拖放註釋應用程式在放置區域內點擊來完成此操作
1. 根據 Excel 檔案的大小和網路速度等待幾秒鐘
1. 點擊「刪除」按鈕清除評論
1. 立即下載文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android 應用程式 API 刪除 Excel 文件註釋" %}}

1. 新增庫引用到Android項目
1. 透過 Workbook 類別物件載入文檔
1. 選擇特定的工作表
1. 獲取使用 [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--) 的所有評論
1. 透過 getThreadedComments 獲取所有線程評論
1. 使用removeAt分別刪除評論和作者
1. 呼叫save方法儲存文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：從 Excel 文件中刪除註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="更新線程 Excel 評論" %}}

1. 透過 Workbook 類別物件載入文檔
1. 取得具體的工作表
1. 使用 getComments().getThreadedComments(Index).get(Index) 取得線程註釋
1. 使用setNotes方法更新註釋
1. 呼叫save方法儲存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="透過 Android App API 新增評論" %}}

1. 透過Workbook類別物件建立Document
1. 取得具體的工作表
1. 透過getComments().add添加評論索引
1. 使用setNotes方法新增註釋
1. 呼叫save方法儲存文件 with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="程式碼：更新 Excel 檔案的執行緒註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="程式碼：新增註釋" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>開發 Excel 文件註釋 Android 應用程式</h2>

需要開發一個基於 Android 的 Excel 註釋應用程式或實用程式來提供回饋、提出建議或與其他人協作處理文件？透過 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/zh-hant/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/zh-hant/android-java/) 的子 API），任何 Android 開發人員都可以將上述 API 程式碼整合到其文件註釋應用程式中。強大的 android 庫允許對任何文檔註釋解決方案進行編程。而且它可以支援許多流行的格式，包括Excel格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於註釋 Excel 檔案的 Android API" %}}

- 我們在 [Maven 儲存庫](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) 中託管 Java 套件。 
- Aspose.Cells for Java 是包含字節碼的常見 JAR 檔案。
- 請依照 [逐步說明](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) 了解如何安裝 Aspose.Cells for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="系統需求" %}}

- Android作業系統2.0以上。
- Java套件是跨平台的，可以在所有具有JVM實作的作業系統上運行。

<br />
欲了解更多詳情，請參閱[產品文件](https://docs.aspose.com/cells/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}