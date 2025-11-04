---
title: 在线将 XPS 转换为 POTM 或开发基于 Java 的应用程序来转换 XPS 文件
description: 免费在线应用程序将 XPS 文件转换为 POTM 文件。XPS 文档的 Java 转换库代码。 

family: total
platformtag: Java
feature: conversion
informat: XPS
outformat: POTM
otherformats: OTP POTX PPSM POTM POWERPOINT XAML PPTM PPSX PPS POT PPT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在线 XPS 到 POTM 转换应用程序和 Java 代码来转换 XPS 文件" h2="开发强大的基于 Java 的 XPS 转换和导出应用程序。 通过 Java 自动化 API 将单个或多个 XPS 文件转换为 POTM 和其他格式。 通过应用程序在线自由转换 XPS 文件并即时下载。" >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="免费在线 XPS 至 POTM 转换应用程序" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=potm&from=xps" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="使用应用程序在线将 XPS 文件转换为 POTM 文件" %}}

1. 上传 XPS 文件进行转换
1. 等待几秒钟或更长时间，具体取决于 XPS 大小
1. 留意上传状态栏
1. 点击“转换”按钮
1. XPS 将转换为 POTM 文档
1. 下载转换后的POTM文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 自动化 API 将 XPS 转换为 POTM" %}}


1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开XPS文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 XPS 转换为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 POTM 格式并设置 ` Potm` 作为 SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "ff4a1b9329c9c3428525cb1c7b528cc0" "convert-xps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

使用其他功能（如 通过 Java 打开加密的 XPS 文件, 通过 Java 保存具有预定义视图类型的 POTM 文件）将 XPS 保存为 POTM 的情况较少。

{{% blocks/products/pf/feature-page-code %}}


```java
// open XPS document
Document doc = new Document("input.xps", "Your@Password");
// save XPS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>使用 Java 开发 XPS 文件转换应用程序</h2>

需要开发基于 Java 的软件应用程序来轻松保存和导出 XPS 文件到 POTM 文档吗？ 通过[Aspose.Total for Java](https://products.aspose.com/total/zh/java/)，任何Java开发人员都可以集成上述API代码来编写跨多种格式的转换应用程序，包括Microsoft Word（DOC、DOCX）、Excel（XLS、XLSX）、Powerpoint（PPT、PPTX）、PDF、电子邮件文件、图像（JPG、PNG、BMP、GIF）和其他格式。 强大的 Java 文档转换库，支持许多流行格式，包括 XPS 格式。 将文档导出和渲染为其他格式，程序员可以使用 Aspose.Total for Java 子 API，包括 [Aspose.Words for Java](https://products.aspose.com/words/zh/java/)、[Aspose.Cells for Java](https://products.aspose.com/cells/zh/java/)、[Aspose.Slides for Java](https://products.aspose.com/slides/zh/java/)、[Aspose.PDF for Java](https://products.aspose.com/pdf/zh/java/)、[Aspose.Imaging for Java](https://products.aspose.com/imaging/zh/java/) 等。<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XPS Java 转换库" %}}

还有其他选项可以将 Aspose.Total for Java 集成到您的系统中。 请选择一个符合您需求的方案并按照分步说明进行操作：<br /><br />

- 直接从基于 Maven 的项目中使用 Aspose.Total for Java，并在 pom.xml 中包含相关子 API。
- 或者，可以从 [下载](https://releases.aspose.com/total/java) 获取一个 ZIP 文件。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="正在将 XPS 保存至 POTM 应用要求" %}}

任何可以运行 Java 运行时环境 (JRE) 的操作系统都可以运行 Aspose.Total for Java。 以下列出了大多数（但不是全部）受支持的操作系统。 <br /><br />
- 微软 Windows
- Linux：Ubuntu、OpenSUSE、CentOS 等
- macOS ：10.9 (Mavericks) 及更高版本
- 移动设备：Android、iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

```
{{< blocks/products/pf/agp/feature-section >}}



将 XPS 转换为 **POTM（启用宏的 PowerPoint 模板）**，将可重复使用的模板与自动化相结合，实现可以执行嵌入式宏的交互式幻灯片，用于高级演示。



{{% blocks/products/pf/agp/feature-section-col title="关键用例" %}}



* 具有自动化图表更新的公司模板。

* 嵌入式宏的互动培训演示。

* 需要在幻灯片中动态更新数据的财务仪表板。

* 在基于 PowerPoint 的报告中进行工作流自动化。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}



* 将 XPS 文件批量转换为启用宏的模板。

* 与 Excel 或数据库源集成，动态提供幻灯片内容。

* 定期生成启用宏的演示模板。

* 为公司会议简化创建交互式仪表板。



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}


{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}