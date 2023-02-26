---
title: 使用 .NET 将 XLTX 转换为 POWERPOINT 
description: 在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上将 XLTX 转换为 POWERPOINT 或在线。在集成代码之前快速测试免费的 CSV 到 DOC 在线转换器。 或使用免费的在线转换器
url_ignore: /zh/net/conversion/xltx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通过 C# 将 XLTX 转换为 POWERPOINT 或在线" h2="导出 Excel&reg; XLTX 到 .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 POWERPOINT">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 上的 XLTX 到 POWERPOINT 转换" %}}
1. 使用 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) 类打开 XLTX 文件
2. 将 XLTX 转换为 PDF 并将 SaveFormat 设置为 Auto
3. 用[Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)类加载转换后的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法将文档保存为PPTX格式，并将Pptx设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，从 [下载](https://releases.aspose.com/total/net) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。(https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="用于 XLTX 到 POWERPOINT 转换的 .NET C# 代码" gistPath="" %}}

```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in PPTX format
document.Save("output.pptx", SaveFormat.Pptx); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免费的 XLTX 到 POWERPOINT 在线转换器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xltx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/agp/other-supported-section title="其他转换选项" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xltx-to-docx/" name="XLTX 转 DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xltx-to-doc/" name="XLTX 转 DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xltx-to-word/" name="XLTX 转 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/net/conversion/xltx-to-pptx/" name="XLTX 转 PPTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}