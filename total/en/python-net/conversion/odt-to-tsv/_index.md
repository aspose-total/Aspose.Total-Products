---
title: Convert ODT to TSV using Python
description: ODT to TSV conversion in your Python applications without using Microsoft Word or Excel 

family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: TSV
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert ODT to TSV via Python" h2="ODT to TSV conversion in your Python applications without installing Microsoft Word<sup>&reg;</sup> or Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a ODT to TSV conversion feature within application. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API can help to automate the conversion process. It's a full package of various APIs dealing different formats.

It's mainly in two steps. Firstly use [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API to convert ODT file to HTML. After that by using Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), save the created HTML into desired Microsoft Excel format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert ODT to TSV in Python" %}}
- **Step 1** Open the source ODT file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Save ODT file to HTML by using [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) method by providing the file name and desired directory path
-  **Step 2** Load HTML file with an instance of Workbook class with file and LoadOptions as parameters
-  Call the `save` method while specifying output TSV file path. So your ODT file is converted to TSV at the specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For ODT to TSV conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Or use the following pip commands ```pip install aspose.words``` and ```pip install aspose-cells-python``` 
-  Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) and for Linux check additional requirements for gcc and libpython and follow [step by step instructions](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save ODT To HTML in Python - Step 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Save HTML To TSV in Python - Step 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}