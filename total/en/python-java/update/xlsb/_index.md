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

For a developer, who is trying to update XLSB files via  Python application. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API can help to automate the updating process. It's a full package of various APIs dealing different formats including Microsoft Excel files. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API that is part of [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) package makes this modifying process easy. Below is the process of updating the XLSB document.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Update XLSB File in Python" %}}

- Create new [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) class object having the source XLSB file as parameter
- Access of relevant Worksheet using [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) method
- Insert new data in the accessed cell using [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) method
- Save the file as .xlsb file using save() method by passing the file with path as the parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Modification Requirements" %}}

- For XLSB modification, reference APIs within the project directly from PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Or use the following pip command ```pip install aspose.cells``` 
- Moreover, Download the API package from the [Downloads](https://releases.aspose.com/cells/python-java) section 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - Update XLSB File in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}