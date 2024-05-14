---
title: 在线删除 PPS 注释或使用 Android 移动应用程序管理注释
description: 通过在线应用程序免费从 PPS 文件中删除注释。用于管理 PPS 文件注释的 Android API 代码。

family: total
platformtag: Android
feature: Annotate
informat: PPS
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线清除 PPS 演示文稿中的注释或通过 Android 应用程序进行管理" h2="开发功能强大的基于Android的PPS演示注释实用应用程序。列出用于管理 PPS 文件注释的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除PPS注释" %}}

1. 导入PPS文件，上传即可删除评论
1. 通过注释应用程序的拖放操作，单击放置区域内部即可
1. 根据 PPS 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过Android应用程序删除PPS演示文稿评论" %}}

1. 向 android 项目添加库引用
1. 通过 Presentation 类对象加载 PPS
1. 通过 Presentation.getCommentAuthors() 集合遍历每个作者
1. 调用 clear() 方法删除其注释
1. 最后调用getCommentAuthors().clear()删除所有作者
1. 调用save方法保存文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：从 PPS 演示文稿中删除评论和作者" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-comments-authors-from-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Android 应用程序添加 PPS 演示文稿评论" %}}

1. 向 android 项目添加库引用
1. 通过 Presentation 类对象加载 PPS
1. 调用 Presentation.getCommentAuthors().addAuthor(String, String) 添加作者
1. 使用 ICommentAuthor.getComments().addComment(String, ISlide, Point2D.Float, Date) 添加注释
1. 调用save方法保存文件 with added comments
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：添加注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-powerpoint-presentation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>开发 PPS 文档注释 Android 应用程序</h2>

需要开发 PPS 注释移动应用程序或实用程序来提供反馈、提出建议或与他人合作处理文档吗？借助 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/zh/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/zh/android-java/) 的子 API），任何 Android 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的android库允许编写任何文档注释解决方案。此外，它还可以支持许多流行格式，包括 PPS 格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 PPS 文件的 Android 库" %}}

- 我们在 [Maven 存储库](https://releases.aspose.com/java/repo/com/aspose/aspose-slides/) 中托管我们的 Java 包。 
- Aspose.Slides for Java 是一个包含字节码的常见 JAR 文件。
- 按照 [逐步说明](https://docs.aspose.com/slides/java/installation/#install-aspose-slides-for-java-from-maven-repository) 了解如何安装 Aspose.Slides for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

- J2SE 6.0 (Java 1.6) 及更高版本
- Java 包是跨平台的，可以在所有具有 JVM 实现的操作系统上运行。

<br />
更多详细信息请参阅[产品文档](https://docs.aspose.com/slides/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}