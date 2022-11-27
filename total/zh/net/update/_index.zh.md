---
title: 使用 .NET 更新 Excel 文件 

description: 使用基于 C# .NET 的应用程序，无需安装 Microsoft Office 即可编辑 Microsoft Excel XLSX、XLS、CSV 文档。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 .NET 更新 Excel 文档" h2="在基于 .NET 的应用程序中修改 Microsoft Excel XLSX、XLS 文件，而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
组织通常会通过公司软件更新存储在 excel 文件中的数据，例如学生数据、患者记录和仓库物品清单等。 [Aspose.Total for .NET](https://products.aspose.com/total/net/) API 提供使用软件修改电子表格的功能。 程序员只需编写几行 API 代码就可以通过修改功能增强软件。 作为 [Aspose.Total for .NET](https://products.aspose.com/total/net/) 包的一部分的 [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API 使这个修改过程变得容易。 下面是更新Excel文件的过程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 .NET 更新 Excel 文档" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API 提供了处理 Excel 电子表格加载的工作簿类。 过程很简单。 通过提供源文件作为参数来创建 [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) 对象。 通过使用 [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) 方法提供其索引来访问相关工作表。 使用[PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/)方法修改访问单元格中的内容，最后调用save()方法保存文档。

{{% blocks/products/pf/feature-page-code h3=".NET 代码 - 更新 Excel 文档" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}