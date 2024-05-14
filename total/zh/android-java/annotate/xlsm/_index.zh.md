---
title: 在线删除 XLSM 注释或使用 Android 移动应用程序管理注释
description: 通过在线应用程序免费从 XLSM 文件中删除注释。用于管理 XLSM 文件注释的 Android API 代码。

family: total
platformtag: Android
feature: Annotate
informat: XLSM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线清除 XLSM 文档中的注释或通过 Android 应用程序进行管理" h2="开发功能强大的基于Android的XLSM文档注释实用应用程序。列出用于管理 XLSM 文件注释的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除XLSM注释" %}}

1. 导入XLSM文件，上传即可删除评论
1. 通过注释应用程序的拖放操作，单击放置区域内部即可
1. 根据 XLSM 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过Android App API删除XLSM文档注释" %}}

1. 将库引用添加到Android项目
1. 通过 Workbook 类对象加载文档
1. 选择特定的工作表
1. 使用 [getComments()](https://reference.aspose.com/cells/java/com.aspose.cells/worksheet/#getComments--) 获取所有评论
1. 通过 getThreadedComments 获取所有主题评论
1. 使用 removeAt 分别删除评论和作者
1. 调用save方法保存文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：从 XLSM 文档中删除注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="更新线程 XLSM 评论" %}}

1. 通过 Workbook 类对象加载文档
1. 获取特定工作表
1. 使用 getComments().getThreadedComments(Index).get(Index) 获取主题评论
1. 使用setNotes方法更新评论
1. 调用save方法保存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Android App API 添加评论" %}}

1. 通过 Workbook 类对象创建文档
1. 获取特定工作表
1. 通过getComments().add添加评论索引
1. 使用 setNotes 方法添加注释
1. 调用save方法保存文件 with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：更新XLSM文件的线程注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "update-threaded-comments-in-excel.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="代码：添加注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-excel-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>开发 XLSM 文档注释 Android 应用程序</h2>

需要开发基于 Android 的 XLSM 注释应用或实用程序来提供反馈、提出建议或与其他人合作处理文档吗？借助 [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 的子 API），任何 Android 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的android库允许编写任何文档注释解决方案。此外，它还可以支持许多流行格式，包括 XLSM 格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 XLSM 文件的 Android API" %}}

- 我们在 [Maven repositories](https://releases.aspose.com/java/repo/com/aspose/aspose-cells/) 中托管我们的 Java 包。 
- Aspose.Cells for Java 是一个包含字节码的常见 JAR 文件。
- 按照 [step by step instructions](https://docs.aspose.com/cells/java/installation/#install-aspose-cells-for-java-from-maven-repository) 了解如何安装 Aspose.Cells for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

- Android OS 2.0或更高版本。
- Java 包是跨平台的，可以在所有具有 JVM 实现的操作系统上运行。

<br />
更多详细信息请参阅[Product Documentation](https://docs.aspose.com/cells/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}