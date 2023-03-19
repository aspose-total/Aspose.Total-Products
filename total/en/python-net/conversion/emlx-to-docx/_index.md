---
title: Convert EMLX to DOCX in Python
description: Save EMLX to DOCX in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert EMLX to DOCX using Python" h2="EMLX to DOCX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

For a Python developer, who is trying to add a EMLX to DOCX conversion feature within application? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API can help to automate the conversion process. It's a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) APIs that are part of [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) package makes this conversion easy using Python. It's a two step process, firstly load Email and render it into HTML via [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/). Secondly load the converted HTML using [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and save it into respective Word DOCX format.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert EMLX to DOCX in Python" %}}

- Open the source EMLX file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your EMLX file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the EMLX is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For EMLX to DOCX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save EMLX To DOCX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}