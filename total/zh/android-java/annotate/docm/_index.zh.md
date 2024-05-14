---
title: 在线删除 DOCM 注释或使用 Android 移动应用程序管理注释
description: 通过在线应用程序免费从 DOCM 文件中删除注释。用于管理 DOCM 文件注释的 Android API 代码。

family: total
platformtag: Android
feature: Annotate
informat: DOCM
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="在线清除 DOCM 文档中的注释或通过 Android 应用程序进行管理" h2="开发功能强大的基于Android的DOCM文档注释实用应用程序。列出用于管理 DOCM 文件注释的代码。" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="在线删除DOCM注释" %}}

1. 导入DOCM文件，上传即可删除评论
1. 通过注释应用程序的拖放操作，单击放置区域内部即可
1. 根据 DOCM 文件的大小和互联网速度等待几秒钟
1. 点击“删除”按钮清除评论
1. 立即下载文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过Android应用程序删除DOCM文档注释" %}}

1. 向 android 项目添加库引用
1. 通过 Document 类对象加载文档
1. 使用 [getChildNodes](https://reference.aspose.com/words/java/com.aspose.words/document/#getChildNodes) 和 NodeType.COMMENT 从所有节点获取所有评论
1. 调用[clear](https://reference.aspose.com/words/java/com.aspose.words/nodecollection/#clear)方法删除所有评论
1. 调用save方法保存文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：从 DOCM 文件中删除注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "remove-comments-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="删除并添加DOCM评论回复" %}}

1. 向 android 项目添加库引用
1. 通过 Document 类对象加载文档
1. 使用 getChild 获取评论
1. 使用 [removeReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#removeReply-com.aspose.words.Comment) 删除该评论的指定回复
1. 使用 [addReply](https://reference.aspose.com/words/java/com.aspose.words/comment/#addReply-java.lang.String-java.lang.String-java.util.Date-java.lang.String) 添加对此评论的任何回复
1. 调用save方法保存文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Android 应用添加评论" %}}

1. 向 android 项目添加库引用
1. 创建 Document 类对象
1. 使用 [Comment](https://reference.aspose.com/words/java/com.aspose.words/comment/) 创建注释
1. 使用 getParagraphs().add 和 getFirstParagraph().getRuns().add
1. 调用save方法保存文件 with added comments

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="代码：从 DOCM 文件中删除和添加评论回复" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-and-delete-comments-reply-from-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="代码：添加注释" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-comments-to-word-file.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>开发 DOCM 文档注释 Android 应用程序</h2>

需要开发 DOCM 注释移动应用程序或实用程序来提供反馈、提出建议或与他人合作处理文档吗？借助 [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/)（[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 的子 API），任何 Android 开发人员都可以将上述 API 代码集成到其文档注释应用程序中。强大的android库允许编写任何文档注释解决方案。此外，它还可以支持许多流行格式，包括 DOCM 格式。<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于注释 DOCM 文件的 Android 库" %}}

- 我们在 [Maven repositories](https://releases.aspose.com/java/repo/com/aspose/aspose-words/) 中托管我们的 Java 包。 
- Aspose.Words for Java 是一个包含字节码的常见 JAR 文件。
- 按照 [step by step instructions](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/) 了解如何安装 Aspose.Words for Android via Java。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

- 支持 Java SE 7 及更新的 Java 版本。
- 如果必须使用过时的 JRE，则需要为 Java SE 6 提供单独的软件包。
- Java 包是跨平台的，可以在所有具有 JVM 实现的操作系统上运行。
- 操作系统包括 Microsoft Windows、Linux、macOS、Android 和 iOS。

<br />
有关可选包依赖项的更多详细信息，例如 JogAmp JOGL、Harfbuzz 字体引擎、Java Advanced Imaging JAI，请参阅 [Product Documentation](https://docs.aspose.com/words/java/system-requirements/)。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}