---
title: 通过 Java API 将 CGM 转换为 PPTM
description: Java API 在不使用 Microsoft Word 的情况下将 CGM 转换为 PPTM
url_ignore: /zh/java/conversion/cgm-to-pptm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPTM
otherformats: PPSX POTX PPS PPSM POWERPOINT POT OTP POTM SWF PPT XAML PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 CGM 导出为 PPTM 的 Java API" h2="通过本地 Java API 将 CGM 导出到 PPTM，无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java J2SE、J2EE、J2ME 应用程序中轻松地将 CGM 转换为 PPTM。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 CGM 导出为 PPTX。之后，通过使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API，您可以将 PPTX 转换为 PPTM。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 CGM 转换为 PPTM" %}}
1. 用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开CGM文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 CGM 转换为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 PPTM 格式并设置 ` Pptm` 作为 SaveFormat
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
{{% blocks/products/pf/feature-page-section  h2="通过 Java 保存具有预定义视图类型的 PPTM 文件" %}}
将 CGM 转换为 PPTM 后，您还可以为演示文稿添加预定义的视图类型。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) 提供了一种工具来设置生成的演示文稿在通过 [ViewProperties](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 类。 [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 属性用于通过使用[ViewType](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) 枚举器。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="主要用例" %}}
- **数据驱动的演示文稿** – 根据实时数据自动更新可视化内容。
- **带宏的技术模拟** – 在幻灯片中控制模拟播放。
- **交互式工程内容** – 允许在演示过程中实时修改图表。

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="自动化场景" %}}
- **Java 幻灯片自动化工具** – 直接从 CGM 文件创建带宏的幻灯片。
- **AI 生成的带宏幻灯片** – 将自动化与 AI 生成的内容结合，获取见解。
- **基于模板的动态内容管道** – 批量生成和更新技术演示文稿模板。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}