---
title: 使用 C++ 将 SXC 转换为 PPTX
description: 在 C++ 应用程序中将 SXC 转换为 PPTX

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: POWERPOINT WORD DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 将 SXC 转换为 PPTX" h2="导出 Excel<sup>&reg;</sup>全功能 C++ 应用程序中的 SXC 到 PPTX" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 SXC 到 PPTX 转换" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成员函数打开SXC文件/cpp/class/aspose.cells.factory) 类参考
2. 将 SXC 转换为 PDF 并将 SaveFormat 设置为 Pdf
3.使用[Pptxument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument)类参考加载转换后的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db)成员函数将文档保存为PPTX格式，并将Pptx设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://downloads.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/sxc-to-powerpoint/" name="SXC 至 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/sxc-to-word/" name="SXC 至 WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/sxc-to-pptxx/" name="SXC 至 PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/conversion/sxc-to-pptx/" name="SXC 至 PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}