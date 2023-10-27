---
title: Update Excel Files using .NET 

description: Edit Microsoft Excel XLSX, XLS, CSV documents without installing Microsoft Office with C# .NET based applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update Excel Documents via .NET" h2="Modify Microsoft Excel XLSX, XLS files within .NET based applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
It's common for organization to update their data, stored in excel files such as students data, patients records and warehouse items list etc via company software. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API provides the functionality of modifying the spreadsheets using the software. Programmers can enhance the software with the modification capabilities by just writing few lines of API code. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API that is part of [Aspose.Total for .NET](https://products.aspose.com/total/net/) package makes this modification process easy. Below is the process of updating the Excel document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Update Excel Documents using .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API provides Workbook class that handles the loading of Excel spreadsheets. Process is simple. Create the [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) object by providing the source file as parameter. Access the relevant Worksheet by providing its index using [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) method. Use the [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) method to modify the content in the accessed cell and finally call the save() method to save the document.

{{% blocks/products/pf/feature-page-code h3=".NET Code - Update Excel Documents" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-autogen-total-feature>}}