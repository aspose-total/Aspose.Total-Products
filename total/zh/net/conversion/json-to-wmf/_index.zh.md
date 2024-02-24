---
title: 通过 .NET 将 JSON 格式转换为 WMF
description: 在 C# 中将 JSON 解析为 WMF，而不使用第三方依赖项
url_ignore: /zh/net/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: DICOM WMF IMAGE WMZ DXF TGA PSD JPEG2000 SVGZ EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 JSON 格式转换为 WMF" h2="C# API 在不使用第三方依赖项的情况下将 JSON 解析为 WMF" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过使用 [Aspose.Total for .NET](https://products.aspose.com/total/net/)，您可以在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中以两个简单的方式将 JSON 解析为 WMF脚步。首先，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)，您可以将 JSON 导出为 JPEG。之后，通过使用 [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/)，您可以将 JPEG 转换为 WMF。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 JSON 格式转换为 WMF" %}}
1. 建[Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)对象，从文件中读取JSON数据
2. 用[Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)方法将JSON转换为JPEG
3. 使用 [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) 类加载 JPEG 文档
4. 使用[Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)方法将文档保存为WMF格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 设置布局并将 JSON 格式转换为 WMF" %}}
在将 JSON 解析为 WMF 时，您还可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) 为 JSON 设置布局选项。它允许您将 Array 处理为表格、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="将 JSON 格式解析为带水印的 WMF" %}}
使用 API，您还可以在 WMF 文档中将 JSON 转换为带有水印的 WMF。为了添加水印，您可以首先将您的 JSON 文档渲染为 JPEG 并在其中添加水印。为了演示操作，您可以加载转换后的 JPEG 图像，使用 Matrix 类的对象添加转换，并使用 [Graphics](https://reference.aspose.com/imaging/) 在图像表面绘制一个字符串作为水印net/aspose.imaging/graphics) 类的 [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring) 方法。添加水印后，您可以将JPEG保存为WMF格式。下面的代码示例演示了如何向文档添加对角线水印。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}