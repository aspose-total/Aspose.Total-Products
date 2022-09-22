---
title: Convert PPTX to DOCX in Python
description: PPTX to DOCX conversion in your Python applications without using Microsoft Word or PowerPoint 
url: /python-net/conversion/pptx-to-docx/
family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: DOCX
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PPTX to DOCX using Python" h2="PPTX to DOCX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a PPTX to DOCX conversion feature within application? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API can help to automate the conversion process. It's a full package of various APIs dealing different formats. 

It's mainly in two steps. Firstly use [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API to convert PPTX file to PDF. After that by using Microsoft Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), save the created PDF into Microsoft Word as a DOCX format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PPTX to DOCX in Python" %}}
-  **Step 1** Load PDF file with an instance of [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) class
	-  Call the `save` method while specifying output file path & SaveFormat.PDF as parameters. So your PPTX file is converted to PDF at the specified path.
- **Step 2** Open the PDF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
	- Save PDF file to DOCX file by using [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) method by providing the file name and desired directory path.
	- Here is another code snippet for [PowerPoint Presentation to Word](https://products.aspose.com/total/python-net/conversion/) Conversion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PPTX to DOCX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) and [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Or use the following pip commands ```pip install aspose.slides``` and ```pip install aspose.words```.
-  Moreover, Microsoft Windows or Linux based OS (see more for [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) and [Words](https://docs.aspose.com/words/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow [step by step instructions](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PPTX To PDF in Python - Step 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Save PDF To DOCX in Python - Step 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}