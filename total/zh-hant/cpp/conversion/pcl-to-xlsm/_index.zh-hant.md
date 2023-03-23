---
title: 將 PCL 轉換為 XLSM 的 C++ API
description: 通過 C++ API 將 PCL 轉換為 XLSM，無需使用 Microsoft Excel 或 Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: XLSM
otherformats: XLTX XLSB SXC ODS DIF TXT CSV XLT XLAM FODS EXCEL TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="在 C++ 應用程序中將 PCL 渲染為 XLSM" h2="在本機 C++ 應用程序中將 PCL 轉換為 XLSM，無需 Microsoft<sup>&reg;</sup> Excel 或 Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
通過 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 文件格式自動化庫將 PCL 轉換為 C++ 中的 XLSM 是一個簡單的兩步過程。第一步，您可以使用 [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 將 PCL 導出到 XLSX，然後使用 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) 電子表格編程 API，您可以將 XLSX 轉換為 XLSM。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="將 PCL 轉換為 XLSM 的 C++ API" %}}
1. 用[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)類參考打開PCL文件
2. 用[保存](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)成員函數將PCL轉換為XLSX
3. 使用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 類參考加載 XLSX 文檔
4. 使用 [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) 成員函數將文檔保存為 XLSM 格式
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="轉換要求" %}}
從命令行安裝為 ```nuget install Aspose.Total.Cpp``` 或通過 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```。

或者，從 [下載](https://releases.aspose.com/total/cpp) 獲取 ZIP 文件中的離線 MSI 安裝程序或 DLL。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 獲取或設置 PCL 文件信息" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) 還允許您獲取有關 PCL 文檔的信息，並讓您在轉換過程之前做出明智的決定。為了獲取PCL文件的文件特定信息，首先需要調用[get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a)方法[Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) 類。一旦檢索到 DocumentInfo 對象，您就可以獲取各個屬性的值。此外，您還可以使用 DocumentInfo 類的相應方法設置屬性。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="通過 C++ 將 XLSM 文件格式保存到流" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) 允許將 XLSM 文件格式保存為流式傳輸。要將文件保存到流中，請創建 MemoryStream 或 FileStream 對象，然後通過調用 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 將文件保存到該流對像中對象的 [保存](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) 方法。調用 Save 方法時，使用 [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) 枚舉指定所需的文件格式。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlsm-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}