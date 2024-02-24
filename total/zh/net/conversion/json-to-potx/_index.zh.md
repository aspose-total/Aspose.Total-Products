---
title: 通过 .NET 将 JSON 格式转换为 POTX
description: 在 C# 中将 JSON 解析为 POTX，而不使用 Microsoft PowerPoint
url_ignore: /zh/net/conversion/json-to-potx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POTX
otherformats: PPSX OTP POTM PPS POWERPOINT PPTM POTX PPT POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="通过 C# 将 JSON 格式转换为 POTX" h2="无需使用 Microsoft<sup>&reg;</sup> PowerPoint 即可将 JSON 解析为 POTX 的 C# API" >}}

{{% blocks/products/pf/feature-page-summary %}}
您可以通过两个简单的步骤在任何 .NET、C#、ASP.NET 和 VB.NET 应用程序中将 JSON 转换为 POTX。首先，通过使用 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)，您可以将 JSON 解析为 PPTX。之后，通过使用 [Aspose.Slides for .NET](https://products.aspose.com/slides/net/)，您可以将 PPTX 转换为 POTX。这两个 API 都属于 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 包。
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="通过 C# 将 JSON 格式转换为 POTX" %}}
1. 创建一个新的 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 对象并从文件中读取有效的 JSON 数据
2. 使用 [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) 类和 [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) 将 JSON 文件导入工作表 它作为 PPTX
3. 用[Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)类加载PPTX文档
4. 使用[Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)方法将文档保存为POTX格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C# 设置布局并将 JSON 格式转换为 POTX" %}}
在将 JSON 解析为 POTX 时，您还可以使用 [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions) 为 JSON 格式设置布局选项。它允许您将数组作为表格处理、忽略空值、忽略数组标题、忽略对象标题、将字符串转换为数字或日期、设置日期和数字格式以及设置标题样式。所有这些选项都允许您根据需要呈现数据。以下代码片段向您展示了如何设置布局选项。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="将 JSON 格式转换为带水印的 POTX" %}}
使用 API，您还可以将 JSON 转换为带水印的 POTX。为了给你的 POTX 文档添加水印，你可以先将 JSON 解析为 PPTX 并为其添加水印。为了添加水印，使用 [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) 类加载新创建的 PPTX 文件，选择主演示文稿，使用添加形状类型AddAutoShape，并使用 AddTextFrame 添加水印文本。添加水印后，您可以将文档保存到POTX。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}