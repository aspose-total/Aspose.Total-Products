---
title: 使用 .NET 将 SXC 转换为 WORD 
description: 在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上将 SXC 转换为 WORD
url: /zh/net/conversion/sxc-to-word/
family: total
platformtag: net
feature: conversion
informat: SXC
outformat: DOC
otherformats: PPTX DOCX DOC POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通过 C# 将 SXC 转换为 WORD" h2="导出 Excel&reg; .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 SXC 到 WORD">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 上的 SXC 到 WORD 转换" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 类打开 SXC 文件
2.将SXC转换为PDF并将SaveFormat设置为Auto
3.使用[Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)类加载转换后的PDF文件
4. 使用[Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将文档保存为DOC格式，并将Doc设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://downloads.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。(https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="用于 SXC 到 WORD 转换的 .NET C# 代码" gistPath="" %}}

```cs
// load the SXC file using Workbook class
var book = new Aspose.Cells.Workbook("input.sxc");
// save SXC as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-pptx/" name="SXC 转 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-docx/" name="SXC 转 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-doc/" name="SXC 转 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/sxc-to-powerpoint/" name="SXC 转 POWERPOINT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}