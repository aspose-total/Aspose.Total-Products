---
title: 使用 C++ 將 FODS 轉換為 WORD
description: 在 C++ 應用程序中將 FODS 轉換為 WORD
url: /zh-hant/cpp/conversion/fods-to-word/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOC
otherformats: POWERPOINT DOC PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 FODS 轉換為 WORD" h2="導出 Excel<sup>&reg;</sup>全功能 C++ 應用程序中的 FODS 到 WORD" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 FODS 到 WORD 轉換" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成員函數打開FODS文件/cpp/class/aspose.cells.factory) 類參考
2. 將 FODS 轉換為 PDF 並將 SaveFormat 設置為 Pdf
3.使用[Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)類參考加載轉換後的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db)成員函數將文檔保存為WORD格式，並將Word設置為SaveFormat
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
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-powerpoint/" name="FODS 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-word/" name="FODS 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-pptx/" name="FODS 至 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh-hant/cpp/conversion/fods-to-wordx/" name="FODS 至 WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}