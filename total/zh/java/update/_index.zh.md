---
title: 使用 Java 更新 Excel 文件 

description: 无需在基于 Java 的应用程序中安装 Microsoft Office 即可编辑 Microsoft Excel XLSX、XLS、CSV 文档。
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="通过 Java 更新 Excel 文件" h2="在基于 Java 的应用程序中修改 Microsoft Excel XLSX、XLS 文件，而无需安装 Microsoft Office<sup>&reg;</sup>。" >}}

{{% blocks/products/pf/feature-page-summary %}}
组织通常会通过公司软件更新存储在 excel 文件中的数据，例如学生数据、患者记录和仓库物品清单等。 [Aspose.Total for Java](https://products.aspose.com/total/java/) API 提供使用他们自己的软件修改电子表格的功能。 程序员只需编写几行 API 代码就可以通过修改功能增强软件。 作为 [Aspose.Total for Java](https://products.aspose.com/total/java/) 包的一部分的 [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API 使这个修改过程变得容易。 下面是更新Excel文件的过程。
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="使用 Java 更新 Excel 文档" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API 提供了处理 Excel 电子表格加载的 [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) 类。 过程很简单。 通过提供源文件作为参数来创建 Workbook 类对象。 使用 [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) 方法访问相关工作表和相关单元格。 使用[getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)方法修改访问单元格中的内容，最后调用save()方法保存文档。

{{% blocks/products/pf/feature-page-code h3="Java 代码 - 更新 Excel 文档" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="更新">}}