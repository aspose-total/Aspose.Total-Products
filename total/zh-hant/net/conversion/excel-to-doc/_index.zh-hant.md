---
title: 使用 .NET 將 EXCEL 轉換為 DOC 或使用免費的在線轉換器
description: 在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上將 EXCEL 轉換為 DOC 或在線。在集成代碼之前快速測試免費的 EXCEL 到 DOC 在線轉換器。

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: DOC
otherformats: PPTX WORD POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="通過 C# 將 EXCEL 轉換為 DOC 或在線應用程序" h2="導出 Excel&reg; .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 EXCEL 到 DOC">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 上的 EXCEL 到 DOC 轉換" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 類打開 EXCEL 文件
2. 將 EXCEL 轉換為 PDF 並將 SaveFormat 設置為 Auto
3. 用[Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)類加載轉換後的PDF文件
4. 使用[Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法將文檔保存為DOC格式，並將Doc設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，從 [下載](https://releases.aspose.com/total/net) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="用於 EXCEL 到 DOC 轉換的 .NET C# 代碼" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>免費的 EXCEL 到 DOC 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xlsx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}