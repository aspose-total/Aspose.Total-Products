---
title: Update Excel Files using C++ 

description: Edit Microsoft Excel XLSX, XLS, CSV documents without installing Microsoft Office with C++ based applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update Excel Documents via C++" h2="Modify Microsoft Excel XLSX, XLS files within C++ based applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
It's common for organization to update their data, stored in excel files such as students data, patients records and warehouse items list etc via company software. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API provides the functionality of modifying the spreadsheets using the software. Programmers can enhance the software with the modification capabilities by just writing few lines of API code. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API that is part of [Aspose.Total for C++](https://products.aspose.com/total/cpp/) package makes this modification process easy. Below is the process of updating the Excel document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Update Excel Documents using C++" %}}

Using [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, load the source document using [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Access the [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) using GetIWorksheets()->GetObjectByIndex(0) and required cell using GetICells()->GetObjectByIndex. By using the PutValue method, modify the content in the accessed cell. Lastly invoke the save() method to save the document.

{{% blocks/products/pf/feature-page-code h3="C++ Code - Update Excel Documents" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/agp/other-autogen-total-feature>}}