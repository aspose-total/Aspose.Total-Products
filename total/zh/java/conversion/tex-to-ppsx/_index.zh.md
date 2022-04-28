---
title: 通过 Java API 将 TEX 转换为 PPSX
description: Java API 在不使用 Microsoft Word 的情况下将 TEX 转换为 PPSX
url: /zh/java/conversion/tex-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PPSX
otherformats: PPSM POT SWF POWERPOINT XAML PPTM POTX PPS POTM PPSX PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="用于将 TEX 导出为 PPSX 的 Java API" h2="通过本地 Java API 将 TEX 导出到 PPSX，无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for Java](https://products.aspose.com/total/java/)，您可以在任何 Java J2SE、J2EE、J2ME 应用程序中轻松地将 TEX 转换为 PPSX。首先，通过使用 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/)，您可以将 TEX 导出为 PPTX。之后，通过使用 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API，您可以将 PPTX 转换为 PPSX。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API 将 TEX 转换为 PPSX" %}}
1.使用[Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开TEX文件
2. 使用 [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 TEX 转换为 PPTX
3.使用[Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)类加载PPTX文档
4. 使用 [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 PPSX 格式并设置 ` Ppsx` 作为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从您可以直接从基于 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) 的项目轻松地使用 Aspose.Total for Java 并在您的 pom.xml 中包含库。。

或者，您可以从 [下载](https://downloads.aspose.com/total/java) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 打开加密的 TEX 文件" %}}(
加载 TEX 文件格式时，您的文档可能受密码保护。 [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) 也允许您打开加密文档。为了打开加密文件，您可以初始化[Document]的新实例(https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。  
{{% blocks/products/pf/feature-page-code %}}

```java
// open TEX document
Document doc = new Document("input.tex", "Your@Password");
// save TEX as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="通过 Java 保存具有预定义视图类型的 PPSX 文件" %}}
将 TEX 转换为 PPSX 后，您还可以为演示文稿添加预定义的视图类型。 [Aspose.Slides for Java](https://products.aspose.com/slides/java/) 提供了一种工具来设置生成的演示文稿在通过 [ViewProperties](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) 类。 [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) 属性用于通过使用[ViewType](https:// /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) 枚举器。 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsx format
presentation.save("output.ppsx", SaveFormat.Ppsx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-pps/" name="TEX 到 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-swf/" name="TEX 到 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-potx/" name="TEX 到 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-ppsx/" name="TEX 到 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-potm/" name="TEX 到 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-ppt/" name="TEX 到 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-ppsm/" name="TEX 到 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-xaml/" name="TEX 到 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-otp/" name="TEX 到 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-pptm/" name="TEX 到 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-pot/" name="TEX 到 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-powerpoint/" name="TEX 到 POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}