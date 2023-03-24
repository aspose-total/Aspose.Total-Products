---
title: 使用 C++ 將 XLSB 轉換為 DOCX 或使用免費的在線轉換器
description: 在 C++ 應用程序中將 XLSB 轉換為 DOCX 或在線。在集成代碼之前快速測試免費的 CSV 到 DOC 在線轉換器。

family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT DOC WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通過 C++ 將 XLSB 轉換為 DOCX 或在線" h2="導出 Excel<sup>&reg;</sup>全功能 C++ 應用程序中的 XLSB 到 DOCX" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ 上的 XLSB 到 DOCX 轉換" %}}
1. 使用[Factory](https://reference.aspose.com/cells)的[IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)成員函數打開XLSB文件/cpp/class/aspose.cells.factory) 類參考
2. 將 XLSB 轉換為 PDF 並將 SaveFormat 設置為 Pdf
3. 用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考加載轉換後的PDF文件
4. 使用[Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)成員函數將文檔保存為DOCX格式，並將Docx設置為SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台安裝 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsb");
// save XLSB as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>XLSB 到 DOCX 在線轉換器</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsb" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsb-to-docx/">試試我們的 XLSB 到 DOCX 轉換的免費應用程序</a></p>
</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}