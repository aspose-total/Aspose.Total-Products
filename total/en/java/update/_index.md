---
title: Update Excel Files using Java 

description: Edit Microsoft Excel XLSX, XLS, CSV documents without installing Microsoft Office within Java based applications.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update Excel Documents via Java" h2="Modify Microsoft Excel XLSX, XLS files within Java based applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
It's common for organization to update their data, stored in excel files such as students data, patients records and warehouse items list etc via company software. [Aspose.Total for Java](https://products.aspose.com/total/java/) API provides the functionality of modifying the spreadsheets using their own software. Programmers can enhance the software with the modification capabilities by just writing few lines of API code. [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API that is part of [Aspose.Total for Java](https://products.aspose.com/total/java/) package makes this modification process easy. Below is the process of updating the Excel document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Update Excel Documents using Java" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API provides [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) class that handles the loading of Excel spreadsheets. Process is simple. Create the Workbook class object by providing the source file as parameter. Access the relevant Worksheet and relevant cell using [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) method. Use the [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) method to modify the content in the accessed cell and finally call the save() method to save the document.

{{% blocks/products/pf/feature-page-code h3="Java Code - Update Excel Documents" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Update">}}