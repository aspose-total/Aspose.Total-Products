---
title: Update XLSB File using Python
description: Modify XLSB document in Python applications without using Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update XLSB File via Python" h2="Modify XLSB spreadsheets via your Python Applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
<h2>Why to Edit XLSB File via Python?</h2>

Editing XLSB files via Python is advantageous because it allows you to work with binary Excel files efficiently. These files are typically smaller and load faster than XLSX files, making them suitable for handling large datasets. Python's libraries, such as [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/), enable you to parse and edit XLSB files, extract data, manipulate worksheets, and perform data analysis, all while benefiting from the advantages of a binary format. This approach enhances data processing, reduces file size, and improves performance when working with complex Excel data, making it a valuable choice for data-centric Python applications.

<h2>How Aspose.Total can help in Updaing XLSB Files via Python?</h2>

If you're a developer looking to update XLSB files using a Python application, the Aspose.Total for Python via Java API provides automation for this task. This comprehensive API package covers various formats, including Microsoft Excel files. Specifically, the Aspose.Cells for Python via Java API, part of Aspose.Total for Python via Java, simplifies the modification process. Here's how to update XLSB documents using this API.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Update XLSB File in Python?" %}}

- Create new [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) class object having the source XLSB file as parameter
- Access of relevant Worksheet using [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) method
- Insert new data in the accessed cell using [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) method
- Save the file as .xlsb file using save() method by passing the file with path as the parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Tools Required for XLSB Editing" %}}

- For XLSB modification, reference APIs within the project directly from PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Or use the following pip command ```pip install aspose.cells``` 
- Moreover, Download the API package from the [Downloads](https://releases.aspose.com/cells/python-java) section 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Update XLSB File via Python Code" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}