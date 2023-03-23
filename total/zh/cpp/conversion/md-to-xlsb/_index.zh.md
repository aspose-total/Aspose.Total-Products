---
title: 将 MD 转换为 XLSB 的 C++ API
description: 通过 C++ API 将 MD 转换为 XLSB，无需使用 Microsoft Excel 或 Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: XLSB
otherformats: FODS EXCEL TSV DIF XLSM XLTM XLT SXC CSV XLAM ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 应用程序中将 MD 渲染为 XLSB" h2="在本机 C++ 应用程序中将 MD 转换为 XLSB，无需 Microsoft<sup>&reg;</sup> Excel 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
通过 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 文件格式自动化库将 MD 转换为 C++ 中的 XLSB 是一个简单的两步过程。第一步，您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 将 MD 导出到 XLSX，然后使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) 电子表格编程 API，您可以将 XLSX 转换为 XLSB。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API 将 MD 转换为 XLSB" %}}
1. 用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)类参考打开MD文件
2. 用[保存](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)成员函数将MD转换为XLSX
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 类参考加载 XLSX 文档
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 成员函数将文档保存为 XLSB 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="转换要求" %}}
从命令行安装为 ```nuget install Aspose.Total.Cpp``` 或通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp``。

或者，从 [下载](https://releases.aspose.com/total/cpp) 获取 ZIP 文件中的离线 MSI 安装程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 获取或设置 MD 文件信息" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 还允许您获取有关 MD 文档的信息，并让您在转换过程之前做出明智的决定。为了获取MD文件的文件特定信息，首先需要调用[get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a)方法[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 类。一旦检索到 DocumentInfo 对象，您就可以获取各个属性的值。此外，您还可以使用 DocumentInfo 类的相应方法设置属性。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通过 C++ 将 XLSB 文件格式保存到流" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) 允许将 XLSB 文件格式保存为流式传输。要将文件保存到流中，请创建 MemoryStream 或 FileStream 对象并通过调用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 将文件保存到该流对象中对象的 [保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。调用 Save 方法时，使用 [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) 枚举指定所需的文件格式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsb-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}