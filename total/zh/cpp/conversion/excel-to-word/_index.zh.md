---
title: 使用 C++ 将 EXCEL 转换为 WORD 或使用免费的在线转换器
description: 在 C++ 应用程序中将 EXCEL 转换为 WORD 或在线。在集成代码之前快速测试免费的 CSV 到 DOC 在线转换器。

family: total
platformtag: cpp
feature: conversion
informat: CSV
outformat: DOC
otherformats: DOC PPTX POWERPOINT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 将 EXCEL 转换为 WORD 或在线" h2="导出 Excel<sup>&reg;</sup>全功能 C++ 应用程序中的 EXCEL 到 WORD" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 EXCEL 到 WORD 转换" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成员函数打开EXCEL文件/cpp/class/aspose.cells.factory) 类参考
2. 将 EXCEL 转换为 PDF 并将 SaveFormat 设置为 Pdf
3. 用[Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)类参考加载转换后的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db)成员函数将文档保存为WORD格式，并将Word设置为SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EXCEL file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.excel");
// save EXCEL as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>EXCEL 到 WORD 在线转换器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-docx/">试试我们的 EXCEL 到 WORD 转换的免费应用程序</a></p>
</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}