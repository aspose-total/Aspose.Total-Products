---
title: 在 Android 中將 XML 導出到 POWERPOINT
description: 無需使用 Microsoft Word 即可將 XML 轉換為 POWERPOINT 的 Android API
url: /zh-hant/android-java/conversion/xml-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: PPT
otherformats: PPSM ODP OTP PPSX PPS PPT POT PPTM POTM XAML SWF POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 Java 在 Android 上將 XML 轉換為 POWERPOINT" h2="在您的 Android 應用程序中將 XML 轉換為 POWERPOINT，而無需使用 Microsoft<sup>&reg;</sup> PowerPoint 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通過兩個簡單的步驟在您的 Android 應用程序中集成 XML 到 POWERPOINT 的轉換功能。第一步，您可以使用 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 將 XML 導出到 PPTX。之後，通過使用 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以將 PPTX 轉換為 POWERPOINT。這兩個 API 都屬於 [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) 包。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="用於將 XML 導出為 POWERPOINT 的 Android API" %}}
1.使用[Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)類打開XML文件
2. 使用 [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) 方法將 XML 轉換為 PPTX
3. 使用 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 類加載 PPTX 文檔
4. 使用 [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) 方法將文檔保存為 POWERPOINT 格式並設置 ` Powerpoint` 作為 SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
您可以直接從 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total)通過 Java 輕鬆使用 Aspose.Total for Android 和通過 Java 安裝 [Aspose.PDF for Android](https://docs.aspose.com/pdf/androidjava/installation/) 和 [Aspose.Slides for Android 通過 Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) 在您的應用程序中。

或者，您可以從 [下載](https://downloads.aspose.com/total/androidjava) 獲取 ZIP 文件。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 Java 在 Android 中打開受密碼保護的 XML 文件" %}}
加載 XML 文件格式時，您的文檔可能受密碼保護。 [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) 也允許您打開加密文檔。為了打開加密文件，您可以初始化[Document]的新實例（https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) 類並將文件名和密碼作為參數傳遞。
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="在 Android 應用程序中創建 POWERPOINT 文件的縮略圖" %}}
將 XML 轉換為 POWERPOINT 後，您還可以創建輸出文檔的縮略圖。通過使用豐富的功能 [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)，您可以通過創建 [Presentation]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)類。之後，您可以通過其 ID 或索引獲取任何所需幻燈片的引用，並獲取指定比例的引用幻燈片的縮略圖。
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
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
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-ppsm/" name="XML 至 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-powerpoint/" name="XML 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-otp/" name="XML 至 OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-ppsx/" name="XML 至 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-pps/" name="XML 至 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-ppt/" name="XML 至 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-pot/" name="XML 至 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-pptm/" name="XML 至 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-potm/" name="XML 至 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-xaml/" name="XML 至 XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-swf/" name="XML 至 SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/android-java/conversion/xml-to-potx/" name="XML 至 POTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}