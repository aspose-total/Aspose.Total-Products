---
title: 通过 Java API 将 CGM 转换为 POT
description: Java API 在不使用 Microsoft Word 的情况下将 CGM 转换为 POT
url_ignore: /zh/java/conversion/cgm-to-pot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POT
otherformats: PPSM PPT PPTM PPS POTM OTP PPSX SWF POWERPOINT POTX XAML POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 CGM 导出为 POT 的 Java API" h2="通过本地 Java API 将 CGM 导出到 POT，无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java J2SE、J2EE、J2ME 应用程序中轻松地将 CGM 转换为 POT。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 导出为 PPTX。之后，通过使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API，您可以将 PPTX 转换为 POT。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 CGM 转换为 POT" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 CGM 转换为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 POT 格式并设置 ` Pot` 作为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://releases.aspose.com/total/java/) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。

或者，您可以从 [下载](https://releases.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
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
{{% blocks/products/pf/feature-page-section  h2="通过 Java 保存具有预定义视图类型的 POT 文件" %}}
将 CGM 转换为 POT 后，您还可以为演示文稿添加预定义的视图类型。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) 提供了一种工具来设置生成的演示文稿在通过 [ViewProperties](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 类。 [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 属性用于通过使用[ViewType](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) 枚举器。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pot format
presentation.save("output.pot", SaveFormat.Pot);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
将 CGM（计算机图形元文件）文件转换为 POT（PowerPoint 模板）在基于 Java 的环境中，使组织能够创建可重复使用、标准化的演示文稿模板，其中包含丰富的技术图表。这个过程对需要一致的幻灯片布局、公司品牌和准确的视觉表现的工程、商业和教育部门非常有价值。

{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- **标准化的商业演示文稿** – 在公司所有演示文稿中保持品牌一致性。
- **可重复使用的工程幻灯片** – 预先构建带有嵌入的 CGM 图表的布局，以加快项目报告速度。
- **品牌报告模板** – 为定期报告周期创建可立即使用的 PowerPoint 模板。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **基于 Java 的演示文稿引擎** – 使用 Apache POI 或类似的 API 集成 CGM 到 POT 的转换。
- **办公文件生成工具** – 自动化带有嵌入图表的 POT 文件创建，适用于多个部门。
- **内容自动化工作流** – 部署定时脚本以批量生成和更新 PowerPoint 模板。
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}