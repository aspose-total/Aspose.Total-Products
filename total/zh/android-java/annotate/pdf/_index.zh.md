---
title: 在线删除 PDF 注释或使用 Android 移动应用程序管理注释
description: 通过在线应用程序免费从 PDF 文件中删除注释。用于管理 PDF 文件注释的 Android API 代码。

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线清除 PDF 文档中的注释或通过 Android 应用程序进行管理" h2="开发功能强大的基于Android的PDF文档注释实用应用程序。列出用于管理 PDF 文件注释的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除PDF注释" %}}

1. 导入PDF文件，上传即可删除评论
1. 通过注释应用程序的拖放操作，单击放置区域内部即可
1. 根据 PDF 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过Android App API删除PDF文档注释" %}}

1. 向 android 项目添加库引用
1. 通过 Document 类对象加载文档
1. 通过getPages().get_Item(Index)选择特定页面
1. 使用 AnnotationSelector 并通过 annotationSelector.getSelected() 获取所有文本注释
1. 遍历每个注释并调用删除方法将其删除。
1. 调用save方法保存文件。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：从 PDF 文件中删除注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Android App API 添加注释" %}}

1. 向 android 项目添加库引用
1. 创建 Document 类对象
1. 使用 getPages().add() 添加新页面和内容
1. 使用 TextAnnotation 类的 getPages().get_Item(Index)
1. 设置相关注释，如标题、主题、内容等
1. 使用 getAnnotations().add 添加注释
1. 调用 save 方法保存添加注释的文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：添加PDF注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>开发 PDF 文档注释 Android 应用程序</h2>

需要开发 PDF 注释移动应用程序或实用程序来提供反馈、提出建议或与他人合作处理文档吗？借助 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 的子 API），任何 Android 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的android库允许编写任何文档注释解决方案。此外，它还可以支持许多流行格式，包括 PDF 格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 PDF 文件的 Android 库" %}}

- 我们在 [Maven repositories](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/) 中托管我们的 Java 包。 
- Aspose.PDF for Java 是一个包含字节码的常见 JAR 文件。
- 按照 [step by step instructions](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) 了解如何安装 Aspose.PDF for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

- Android API 31 和 32
- Android 4.0 及以上版本
- Android Studio 和 SDK 工具

<br />
有关可选包依赖项的更多详细信息，例如 JogAmp JOGL、Harfbuzz 字体引擎、Java Advanced Imaging JAI，请参阅 [Product Documentation](https://docs.aspose.com/pdf/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}