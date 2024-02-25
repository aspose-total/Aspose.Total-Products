---
title: Convert EML to DOCX in Python
description: Save EML to DOCX in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: EML
outformat: DOCX
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert EML to DOCX using Python" h2="EML to DOCX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert EML to DOCX?</h2>

EML (Electronic Mail) is a file format used to store emails. It is widely used by many email clients such as Microsoft Outlook, Mozilla Thunderbird, and Apple Mail. DOCX is a file format used by Microsoft Word to store documents. It is the default file format for Microsoft Word 2007 and later versions. Converting EML to DOCX is useful for archiving emails, sharing emails with others, and for editing emails in Microsoft Word.

<h2>How Aspose.Total helps for EML to DOCX Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that makes the conversion of EML to DOCX easy using Python. It is a two step process, firstly load Email and render it into HTML via Aspose.Email for Python via .NET. Secondly load the converted HTML using Aspose.Words for Python via .NET and save it into respective Word DOCX format. The API provides a wide range of features to manipulate the documents and offers a great performance. It also supports various other file formats such as PDF, HTML, XPS, and many more.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert EML to DOCX in Python" %}}

- Open the source EML file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your EML file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the EML is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For EML to DOCX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save EML To DOCX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}