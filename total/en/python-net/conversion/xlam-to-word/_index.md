---
title: Convert XLAM to WORD using Python
description: XLAM to WORD conversion in your Python applications without using Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLAM
outformat: WORD
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XLAM to WORD via Python" h2="XLAM to WORD conversion in your Python applications without installing Microsoft Excel<sup>&reg;</sup> or Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a XLAM to WORD conversion feature within application. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API can help to automate the conversion process. It's a full package of various APIs dealing different formats including XLAM and WORD files.

It's mainly in two steps. Firstly use [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API to convert XLAM file to HTML. After that by using Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), save the created HTML into desired Microsoft Word format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert XLAM to WORD in Python" %}}
- **Step 1** Open the source XLAM file using Workbook class
- Save XLAM file to HTML by using save(file, SaveFormat.HTML) method by providing the file name and desired directory path
-  **Step 2** Load HTML file with an instance of [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
-  Call the `save` method while specifying output WORD file path. So your XLAM file is converted to WORD at the specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For XLAM to WORD conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) and [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Or use the following pip commands ```pip install aspose-cells-python``` and ```pip install aspose.words```
-  Moreover, Microsoft Windows or Linux based OS (see more for [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) and [Words](https://docs.aspose.com/words/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow [step by step instructions](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save XLAM To HTML in Python - Step 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Save HTML To WORD in Python - Step 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}