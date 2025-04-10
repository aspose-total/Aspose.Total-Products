---
title: 通过 C# API 将 CGM 转换为 JPEG2000
description: 在您的 .NET 应用程序中将 CGM 导出为 JPEG2000，而无需使用任何第三方应用程序
url_ignore: /zh/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 CGM 文件转换为 JPEG2000" h2="在 .NET 应用程序中将 CGM 导出为 JPEG2000，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader 或任何其他第三方应用程序" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 CGM 导出到任何 .NET 应用程序中的 JPEG2000 图像。首先，通过使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 导出为 JPEG。之后，通过使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) 图像处理 API，您可以将 JPEG 转换为 JPEG2000。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 将 CGM 文件转换为 JPEG2000" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 初始化[JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)类对象并使用[Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类加载 JPEG 文件
4. 使用[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)方法将文档保存为JPEG2000格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 在单个文件中将 CGM 文件转换为 JPEG2000" %}}
使用 API，您还可以将 CGM 文件转换为 JPEG2000 到单个图像文件。为了转换所有页面，您可以首先将 CGM 文档渲染为一个 TIFF 文件，然后您可以将 TIFF 文件导出为 JPEG2000。您可以使用 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 类。最后，您可以使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类加载 TIFF 文件
并使用 [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 方法将其保存为 JPEG2000 格式。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 CGM 文件转换为 JPEG2000" %}}
使用 API，您还可以根据需要旋转输出的 JPEG2000 图像。 Image.RotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类公开的工厂方法加载转换后的 JPEG 图像并调用 Image .RotateFlip 方法同时指定适当的 [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CGM 文件转换为 JPEG2000：用例" %}}
CGM（计算机图形元文件）文件用于存储向量图形信息，因此它们是创建静态图形和插图的理想选择。然而，当处理动态数据时，像JPEG 2000这样的图像格式变得至关重要，以实现最优压缩和最佳质量。

将CGM文件转换为JPEG 2000格式是必要的，以充分发挥您在图像压缩和质量方面的潜力。这种转换使您能够：

**用途：**

*   **高质量图像编辑**：将CGM文件转换为创建高质量图像，优化图形以适用于网络使用，并确保所有营销材料的一致性品牌。
*   **存档和保存应用**：使用JPEG 2000对大型图像数据集进行压缩并存储，以确保长期保存和访问宝贵的视觉内容。
*   **医疗成像和诊断**：将CGM文件转换为创建详细、高质量的医疗图像，以供诊断目的，减少错误并改善患者结果。
*   **科学研究和出版**：使用JPEG 2000对大型科学图像数据集进行压缩并发布，以促进全球合作和知识共享。
*   **数字图书馆和档案**：将CGM文件转换为创建可缩放、高质量的数字图书馆，保存文化遗产和历史文物以供未来世代。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}