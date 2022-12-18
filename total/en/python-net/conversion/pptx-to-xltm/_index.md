---
title: Convert PPTX to XLTM using Python
description: PPTX to XLTM conversion in your Python applications without using Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: XLTM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPTX to XLTM via Python" h2="PPTX to XLTM conversion in your Python applications without installing Microsoft PowerPoint<sup>&reg;</sup> or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a PPTX to XLTM conversion feature within application. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API can help to automate the conversion process. It's a full package of various APIs dealing different formats including PPTX and XLTM files.

It's mainly in two steps. Firstly use [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API to convert PPTX file to HTML. After that by using Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), save the created HTML into desired Microsoft Excel format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPTX to XLTM in Python" %}}
- **Step 1** Use [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) class instance to open the source PPTX file 
- Save PPTX file to HTML by using [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) method by providing the file name and desired directory path
-  **Step 2** Load HTML file with an instance of Workbook class
-  Call the `save` method while specifying output XLTM file path. So your PPTX file is converted to XLTM at the specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PPTX to XLTM conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) and [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Or use the following pip commands ```pip install aspose.slides``` and ```pip install aspose-cells-python```
-  Moreover, Microsoft Windows or Linux based OS (see more for [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) and [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PPTX To HTML in Python - Step 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Save HTML To XLTM in Python - Step 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}