---
title: 在线将 MHTML 转换为 ODP 或开发基于 Java 的应用程序来转换 MHTML 文件
description: 免费在线应用程序将 MHTML 文件转换为 ODP 文件。MHTML 文档的 Java 转换库代码。 

family: total
platformtag: Java
feature: conversion
informat: MHTML
outformat: ODP
otherformats: POT POWERPOINT PPT POTM PPTM XAML POTX PPSX SWF PPSM OTP PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在线 MHTML 到 ODP 转换应用程序和 Java 代码来转换 MHTML 文件" h2="开发强大的基于 Java 的 MHTML 转换和导出应用程序。 通过 Java 自动化 API 将单个或多个 MHTML 文件转换为 ODP 和其他格式。 通过应用程序在线自由转换 MHTML 文件并即时下载。" >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="免费在线 MHTML 至 ODP 转换应用程序" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=odp&from=mhtml" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="使用应用程序在线将 MHTML 文件转换为 ODP 文件" %}}

1. 上传 MHTML 文件进行转换
1. 等待几秒钟或更长时间，具体取决于 MHTML 大小
1. 留意上传状态栏
1. 点击“转换”按钮
1. MHTML 将转换为 ODP 文档
1. 下载转换后的ODP文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 自动化 API 将 MHTML 转换为 ODP" %}}


1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MHTML文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 MHTML 转换为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 ODP 格式并设置 ` Odp` 作为 SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "89f68c1b3e3c772c46b1f2adbaf240e5" "convert-mhtml-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

使用其他功能（如 通过 Java 打开加密的 MHTML 文件, 通过 Java 保存具有预定义视图类型的 ODP 文件）将 MHTML 保存为 ODP 的情况较少。

{{% blocks/products/pf/feature-page-code %}}


```java
// open MHTML document
Document doc = new Document("input.mhtml", "Your@Password");
// save MHTML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>使用 Java 开发 MHTML 文件转换应用程序</h2>

需要开发基于 Java 的软件应用程序来轻松保存和导出 MHTML 文件到 ODP 文档吗？ 通过[Aspose.Total for Java](https://products.aspose.com/total/zh/java/)，任何Java开发人员都可以集成上述API代码来编写跨多种格式的转换应用程序，包括Microsoft Word（DOC、DOCX）、Excel（XLS、XLSX）、Powerpoint（PPT、PPTX）、PDF、电子邮件文件、图像（JPG、PNG、BMP、GIF）和其他格式。 强大的 Java 文档转换库，支持许多流行格式，包括 MHTML 格式。 将文档导出和渲染为其他格式，程序员可以使用 Aspose.Total for Java 子 API，包括 [Aspose.Words for Java](https://products.aspose.com/words/zh/java/)、[Aspose.Cells for Java](https://products.aspose.com/cells/zh/java/)、[Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/)、[Aspose.PDF for Java](https://products.aspose.com/pdf/zh/java/)、[Aspose.Imaging for Java](https://products.aspose.com/imaging/zh/java/) 等。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MHTML Java 转换库" %}}

还有其他选项可以将 Aspose.Total for Java 集成到您的系统中。 请选择一个符合您需求的方案并按照分步说明进行操作：<br /><br />

- 直接从基于 Maven 的项目中使用 Aspose.Total for Java，并在 pom.xml 中包含相关子 API。
- 或者，可以从 [下载](https://releases.aspose.com/total/java) 获取一个 ZIP 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="正在将 MHTML 保存至 ODP 应用要求" %}}

任何可以运行 Java 运行时环境 (JRE) 的操作系统都可以运行 Aspose.Total for Java。 以下列出了大多数（但不是全部）受支持的操作系统。 <br /><br />
- 微软 Windows
- Linux：Ubuntu、OpenSUSE、CentOS 等
- macOS ：10.9 (Mavericks) 及更高版本
- 移动设备：Android、iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



将MHTML（Web存档）文件转换为ODP（OpenDocument演示文稿）可将Web内容转换为适用于LibreOffice或OpenOffice的可完全编辑幻灯片。ODP确保跨平台兼容性并保留原始格式。



{{% blocks/products/pf/agp/feature-section-col title="主要用途" %}}



* 将在线营销内容转换为ODP幻灯片组。

* 从基于Web的教案创建的教育模块。

* 存档最初托管在Web门户上的公司演示文稿。

* 将基于Web的项目更新转换为专业幻灯片。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}



* 批量将多个MHTML报告转换为ODP幻灯片组。

* 为内部沟通定期生成演示文稿幻灯片。

* 从实时Web仪表板自动更新演示文稿内容。

* 集成到协作式开源演示文稿工作流程中。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}