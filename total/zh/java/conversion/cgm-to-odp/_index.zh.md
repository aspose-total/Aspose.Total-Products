---
title: 通过 Java API 将 CGM 转换为 ODP
description: Java API 在不使用 Microsoft Word 的情况下将 CGM 转换为 ODP
url_ignore: /zh/java/conversion/cgm-to-odp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODP
otherformats: PPS SWF POTX PPSX POTM PPT PPSM XAML OTP PPTM POT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 CGM 导出为 ODP 的 Java API" h2="通过本地 Java API 将 CGM 导出到 ODP，无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java J2SE、J2EE、J2ME 应用程序中轻松地将 CGM 转换为 ODP。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 导出为 PPTX。之后，通过使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API，您可以将 PPTX 转换为 ODP。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 CGM 转换为 ODP" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 CGM 转换为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 ODP 格式并设置 ` Odp` 作为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-odp.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开加密的 CGM 文件" %}}
加载 CGM 文件格式时，您的文档可能受密码保护。 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 也允许您打开加密文档。为了打开加密文件，您可以初始化[Document]的新实例(https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 保存具有预定义视图类型的 ODP 文件" %}}
将 CGM 转换为 ODP 后，您还可以为演示文稿添加预定义的视图类型。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) 提供了一种工具来设置生成的演示文稿在通过 [ViewProperties](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 类。 [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 属性用于通过使用[ViewType](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) 枚举器。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
将 CGM（计算机图形元文件）文件转换为 ODP（OpenDocument Presentation）可实现高质量矢量图表与开源演示文稿格式的无缝集成。这种转换非常适合确保跨平台兼容性，在教育、企业和技术演示中实现专业的视觉叙事，而不会牺牲图像质量。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- 将矢量图表嵌入到LibreOffice Impress演示文稿中。
- 跨平台技术和企业报告生成。
- 制作具有可伸缩插图的教育视觉内容。
- 将工程图纸整合到演示幻灯片中。
- 用精密图形增强科学会议材料。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- 基于Java的文档流水线集成，用于自动生成幻灯片。
- 与LibreOffice兼容的演示文稿制作系统。
- 用于技术部门的企业内容生成工具。
- 基于API的图表到演示文稿的工作流程。
- 批量处理CGM图表，用于大规模演示。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}