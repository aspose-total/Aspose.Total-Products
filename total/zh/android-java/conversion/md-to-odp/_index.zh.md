---
title: 在 Android 中将 MD 导出到 ODP
description: 无需使用 Microsoft Word 即可将 MD 转换为 ODP 的 Android API
url: /zh/android-java/conversion/md-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: ODP
otherformats: PPTM PPT POTX PPS POT PPSX PPSM XAML SWF POTM POWERPOINT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 在 Android 上将 MD 转换为 ODP" h2="在您的 Android 应用程序中将 MD 转换为 ODP，而无需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤在您的 Android 应用程序中集成 MD 到 ODP 的转换功能。第一步，您可以使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 将 MD 导出到 PPTX。之后，通过使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以将 PPTX 转换为 ODP。这两个 API 都属于 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用于将 MD 导出为 ODP 的 Android API" %}}
1.使用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)类打开MD文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法将 MD 转换为 PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 类加载 PPTX 文档
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法将文档保存为 ODP 格式并设置 ` Odp` 作为 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
您可以直接从 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通过 Java 轻松使用 Aspose.Total for Android 和通过 Java 安装 [Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Slides for Android 通过 Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 在您的应用程序中。

或者，您可以从 [下载](https://downloads.aspose.com/total/androidjava) 获取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MD file with an instance of Document class
Document document = new Document("template.md");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Odp format
presentation.save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 Java 在 Android 中打开受密码保护的 MD 文件" %}}
加载 MD 文件格式时，您的文档可能受密码保护。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 也允许您打开加密文档。为了打开加密文件，您可以初始化[Document]的新实例（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 类并将文件名和密码作为参数传递。
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 应用程序中创建 ODP 文件的缩略图" %}}
将 MD 转换为 ODP 后，您还可以创建输出文档的缩略图。通过使用丰富的功能 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以通过创建 [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)类。之后，您可以通过其 ID 或索引获取任何所需幻灯片的引用，并获取指定比例的引用幻灯片的缩略图。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a ODP file
Presentation presentation = new Presentation("output.odp");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-pptm/" name="MD 至 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-ppt/" name="MD 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-potx/" name="MD 至 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-pps/" name="MD 至 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-pot/" name="MD 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-ppsx/" name="MD 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-ppsm/" name="MD 至 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-xaml/" name="MD 至 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-swf/" name="MD 至 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-potm/" name="MD 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-powerpoint/" name="MD 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/android-java/conversion/md-to-otp/" name="MD 至 OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}