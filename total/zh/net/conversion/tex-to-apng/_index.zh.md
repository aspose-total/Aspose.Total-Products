---
title: 通过 C# API 将 TEX 转换为 APNG
description: 在您的 .NET 应用程序中将 TEX 导出为 APNG，而无需使用任何第三方应用程序
url: /zh/net/conversion/tex-to-apng/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: APNG
otherformats: JPEG2000  PSD TGA DXF EMZ SVGZ WMZ IMAGE WMF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 TEX 文件转换为 APNG" h2="在 .NET 应用程序中将 TEX 导出为 APNG，无需使用 Adobe<sup>&reg;</sup> Acrobat Reader 或任何其他第三方应用程序" >}}

{{% blocks/products/pf/feature-page-summary %}}
使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以通过两个简单的步骤轻松地将 TEX 导出到任何 .NET 应用程序中的 APNG 图像。首先，通过使用 [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/)，您可以将 TEX 导出为 JPEG。之后，通过使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) 图像处理 API，您可以将 JPEG 转换为 APNG。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 .NET 将 TEX 文件转换为 APNG" %}}
1.使用[Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)类打开TEX文件
2. 初始化[JpegDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice)类对象并使用[Process](https://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) 方法
3. 使用 [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) 类加载 JPEG 文件
4. 使用[Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)方法将文档保存为APNG格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 在单个文件中将 TEX 文件转换为 APNG" %}}
使用 API，您还可以将 TEX 文件转换为 APNG 到单个图像文件。为了转换所有页面，您可以首先将 TEX 文档渲染为一个 TIFF 文件，然后您可以将 TIFF 文件导出为 APNG。您可以使用 [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) 类打开输入文件并创建 Resolution、TiffSettings 和 TIFF 设备对象。您可以使用 [TiffDevice](https://apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) 类。最后，您可以使用 [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) 类加载 TIFF 文件
并使用 [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4) 方法将其保存为 APNG 格式。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 将 TEX 文件转换为 APNG" %}}
使用 API，您还可以根据需要旋转输出的 APNG 图像。 Image.RotateFlip 方法可用于将图像旋转 90/180/270 度并水平或垂直翻转图像。您可以指定要应用于图像的旋转和翻转类型。为了旋转和翻转图像，您可以使用 [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image) 类公开的工厂方法加载转换后的 JPEG 图像并调用 Image .RotateFlip 方法同时指定适当的 [RotateFlipType](https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype)。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-emz/" name="TEX 转 EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-tga/" name="TEX 转 TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-jpeg2000/" name="TEX 转 JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-image/" name="TEX 转 IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-psd/" name="TEX 转 PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-wmz/" name="TEX 转 WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-svgz/" name="TEX 转 SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to/" name="TEX 转" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-wmf/" name="TEX 转 WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-dxf/" name="TEX 转 DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/tex-to-dicom/" name="TEX 转 DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}