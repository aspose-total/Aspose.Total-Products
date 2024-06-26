---
title: Convert PDF to MHTML in Python
description: PDF to mhtml Web archive format and HtmlFixed file conversion in your Python applications without using Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to MHTML using Python" h2="PDF to MHTML, HtmlFixed and HTML conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

As a Python developer, you may need to add a feature to your application that allows you to convert PDF files to MHTML (Web archive format) or HtmlFixed (HTML format with absolutely positioned elements). Aspose.Total for Python via .NET API can help you automate this process. It is a comprehensive package of various APIs that can handle different file formats. 

Aspose.Words for Python via .NET API, which is part of the Aspose.Total for Python via .NET package, can be used to add the PDF to MHTML conversion feature. If the PDF file is simple, it can be done with just two lines of code. You can load the PDF file and call the save method with the appropriate file path and the SaveFormat enumeration as MHTML or HTML_FIXED. However, if you need to restore the document model as close to the original as possible, you will need to save some extra information within the resultant document, known as round-trip information.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to MHTML in Python" %}}
- Load source PDF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Create the instance of [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Set the export_roundtrip_information as True
- Specify the [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) as MHTML
- Call the `save` method while specifying output file path & SaveFormat as parameters. So your PDF file is converted to MHTML at the specified path

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PDF to MHTML or HtmlFixed format conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Or use the following pip commands ```pip install aspose.words```
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PDF To MHTML in Python - Simple" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-mhtml-simple.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="PDF To MHTML Conversion in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "pdf-to-mhtml-conversion-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}