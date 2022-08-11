---
title: 使用 C++ 將 FODS 轉換為 POWERPOINT
description: 在 C++ 應用程序中將 FODS 轉換為 POWERPOINT
url: /zh-hant/cpp/conversion/fods-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: DOCX PPTX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 FODS 轉換為 POWERPOINT" h2="導出 Excel&reg;全功能 C++ 應用程序中的 FODS 到 POWERPOINT" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 FODS 到 POWERPOINT 轉換" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成員函數打開FODS文件/cpp/class/aspose.cells.factory) 類參考
2. 將 FODS 轉換為 PDF 並將 SaveFormat 設置為 Pdf
3.使用[Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)類參考加載轉換後的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db)成員函數將文檔保存為POWERPOINT格式，並將Powerpoint設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://downloads.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-powerpointx/" name="FODS 至 POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-pptx/" name="FODS 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-word/" name="FODS 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-powerpoint/" name="FODS 至 POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}