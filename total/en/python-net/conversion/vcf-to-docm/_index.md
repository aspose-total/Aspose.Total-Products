---
title: Convert VCF to DOCM in Python
description: Save VCF to DOCM in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: VCF
outformat: DOCM
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert VCF to DOCM using Python" h2="VCF to DOCM conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert VCF to DOCM?</h2>

VCF (Virtual Contact File) is a standard format used to store contact information like name, address, phone number, email address, etc. It is widely used to store contact information in mobile phones, tablets, and other electronic devices. DOCM (Document Macro-Enabled) is a Microsoft Word document format that supports macros. It is used to store documents with macros and other embedded objects. Converting VCF to DOCM is useful for creating documents with contact information in a more organized and structured way.

<h2>How Aspose.Total helps for VCF to DOCM Conversion?</h2>

Aspose.Total for Python via .NET is a comprehensive package of APIs that helps developers to automate the conversion process from VCF to DOCM. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that makes the conversion easy using Python. It is a two-step process, firstly load Email and render it into HTML via Aspose.Email for Python via .NET. Secondly, load the converted HTML using Aspose.Words for Python via .NET and save it into respective Word DOCM format. Aspose.Total for Python via .NET also supports other formats like Email, Images and Microsoft Word formats.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert VCF to DOCM in Python" %}}

- Open the source VCF file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your VCF file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the VCF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For VCF to DOCM conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save VCF To DOCM in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}