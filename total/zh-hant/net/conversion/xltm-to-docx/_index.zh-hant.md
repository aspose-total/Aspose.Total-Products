---
title: 使用 .NET 將 XLTM 轉換為 DOCX 
description: 在 .NET Framework、.NET Core、Mono 或 Xamarin 平台上將 XLTM 轉換為 DOCX

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 XLTM 轉換為 DOCX" h2="導出 Excel&reg; .NET Framework、.NET Core、Mono 或 Xamarin 平台上的 XLTM 到 DOCX">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET 上的 XLTM 到 DOCX 轉換" %}}
1. 使用 [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 類打開 XLTM 文件
2. 將 XLTM 轉換為 PDF 並將 SaveFormat 設置為 Auto
3.使用[Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)類加載轉換後的PDF文件
4. 使用[Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)方法將文檔保存為DOCX格式，並將Docx設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total```。

或者，從 [下載](https://downloads.aspose.com/total/net) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="用於 XLTM 到 DOCX 轉換的 .NET C# 代碼" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/net/conversion/csv-to-word/" name="CSV 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/net/conversion/csv-to-powerpoint/" name="CSV 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/net/conversion/csv-to-pptx/" name="CSV 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/net/conversion/csv-to-docx/" name="CSV 至 DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}