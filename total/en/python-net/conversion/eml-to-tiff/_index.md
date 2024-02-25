---
title: Convert EML to TIFF in Python
description: Save EML to TIFF in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: EML
outformat: TIFF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert EML to TIFF using Python" h2="EML to TIFF conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
As a Python developer, if you are looking to add a feature to your application that allows for the conversion of EML files to TIFF format, then [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API is the perfect solution. This comprehensive package of APIs provides support for a variety of formats, including Email, Images, and Microsoft Word. The two APIs that are part of the [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) package, [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/), make the conversion process simple and straightforward. The process involves two steps: first, the Email is loaded and rendered into HTML using [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/). Then, the HTML is loaded using [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and saved into the desired Word TIFF format. With this API, you can easily and quickly convert EML files to TIFF format with just a few lines of code.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert EML to TIFF in Python" %}}

- Open the source EML file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your EML file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the EML is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For EML to TIFF conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save EML To TIFF in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}