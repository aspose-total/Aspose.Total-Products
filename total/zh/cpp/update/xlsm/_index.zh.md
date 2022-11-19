---
title: 使用 C++ 更新 XLSM 文件
description: 在不使用 Microsoft Excel 的情况下在 C++ 应用程序中修改 XLSM 文档.
family: total
platformtag: C++
feature: update
informat: XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 C++ 更新 XLSM 文件" h2="无需安装 Microsoft Office<sup>&reg;</sup>，即可通过基于 C++ 的应用程序修改 XLSM 电子表格。" >}}

{{% blocks/products/pf/feature-page-summary %}}

对于试图在 C++ 应用程序中更新 XLSM 文件的程序员, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API 可以帮助自动化更新过程。 它是处理多种格式（包括 Microsoft Excel 文档）的不同 C++ 库的完整包。 作为 [Aspose.Total for C++](https://products.aspose.com/total/cpp/) 包的一部分的 [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API 使这个修改过程变得容易。 更新 XLSM 文档的过程很简单，首先访问工作表，然后使用 C++ 在 excel 中更新单元格值。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="如何在 C++ 中更新 XLSM 文件" %}}

- 使用 [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) 加载 XLSM 文件
- 使用 GetIWorksheets()->GetObjectByIndex(0) 访问相关 [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet)，使用 GetICells()->GetObjectByIndex 访问相关单元格
- 使用 PutValue 方法在访问的单元格中插入新数据
- 通过将文件以路径作为参数传递，使用 Save 方法将文件保存为 .xlsm 文件

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="修改要求" %}}

- XLSM修改，Windows和Linux系统遵循[系统要求](https://docs.aspose.com/cells/cpp/system-requirements/) 
- 从命令行安装为```nuget install Aspose.Total.Cpp```
- 或者通过 Visual Studio 的包管理器控制台使用 ```Install-Package Aspose.Total.Cpp```
- 或者，从 [下载](https://downloads.aspose.com/cells/cpp) 获取 ZIP 文件中的脱机 MSI 安装程序或 DLL

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="代码 - 在 C++ 中更新 XLSM 文件" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="其他修改选项" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xls/" name="更新 XLS 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xlsx/" name="更新 XLSX 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/csv/" name="更新 CSV 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xlsb/" name="更新 XLSB 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xlsm/" name="调整 XLSM 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xlt/" name="更新 XLT 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xltx/" name="更新 XLTX 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/xltm/" name="更新 XLTM 文件" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/zh/cpp/update/tsv/" name="更新 TSV 文件" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}