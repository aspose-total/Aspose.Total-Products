---
title: 通过 C# API 将 CGM 转换为 DXF
description: 在您的 .NET 应用程序中将 CGM 导出为 DXF，而无需使用任何第三方应用程序
url_ignore: /zh/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 CGM 文件转换为 DXF" h2="在 .NET 应用程序中将 CGM 导出为 DXF，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader 或任何其他第三方应用程序" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 CGM 导出到任何 .NET 应用程序中的 DXF 图像。首先，通过使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 CGM 导出为 JPEG。之后，通过使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) 图像处理 API，您可以将 JPEG 转换为 DXF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 将 CGM 文件转换为 DXF" %}}
1. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类打开CGM文件
2. 初始化[JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)类对象并使用[Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 方法
3. 使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类加载 JPEG 文件
4. 使用[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)方法将文档保存为DXF格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 在单个文件中将 CGM 文件转换为 DXF" %}}
使用 API，您还可以将 CGM 文件转换为 DXF 到单个图像文件。为了转换所有页面，您可以首先将 CGM 文档渲染为一个 TIFF 文件，然后您可以将 TIFF 文件导出为 DXF。您可以使用 [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 类。最后，您可以使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类加载 TIFF 文件
并使用 [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 方法将其保存为 DXF 格式。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 CGM 文件转换为 DXF" %}}
使用 API，您还可以根据需要旋转输出的 DXF 图像。 Image.RotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类公开的工厂方法加载转换后的 JPEG 图像并调用 Image .RotateFlip 方法同时指定适当的 [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="以编程方式将 CGM 文件转换为 DXF：用例" %}}
将CGM（计算机图形元文件）文件转换为DXF（绘图交换格式）文件对于充分发挥您的CAD设计与制造能力至关重要。这种转换使您能够：

**应用场景：**

*   **CAD设计集成**：将CGM文件转换为DXF文件，以便与CAD软件无缝集成，实现设计协作与数据交换。
*   **制造流程优化**：使用DXF文件优化制造流程，降低生产成本并提高产品质量。
*   **设计可制造性（DFM）**：将CGM文件转换为DFM设计，考虑因素包括材料特性、工具要求和装配约束。
*   **与CNC机器通信**：使用DXF文件传递设计数据给CNC机器，确保切割和焊接零件的准确性。
*   **产品开发与测试**：将CGM文件转换为原型，以测试设计并验证产品功能在生产前的可行性。

注意：我以相同模式将源格式CGM转换为目标格式DXF。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}