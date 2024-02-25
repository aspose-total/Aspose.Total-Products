---
title: Convert OFT to PCL in Python
description: Save OFT to PCL in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: OFT
outformat: PCL
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert OFT to PCL using Python" h2="OFT to PCL conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert OFT to PCL?</h2>

OFT (Outlook Form Template) is a file format used by Microsoft Outlook to store email messages. It is used to store the message body, attachments, and other message related information. PCL (Printer Command Language) is a page description language used by printers to control the printing process. It is used to control the layout, font, and graphics of a printed page. Converting OFT to PCL is necessary when a user wants to print an email message from Outlook.

<h2>How Aspose.Total helps for OFT to PCL Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It provides two APIs, Aspose.Words for Python via .NET and Aspose.Email for Python via .NET, which makes the conversion of OFT to PCL easy using Python. It is a two step process, firstly load Email and render it into HTML via Aspose.Email for Python via .NET. Secondly load the converted HTML using Aspose.Words for Python via .NET and save it into respective Word PCL format. This process can be automated using Aspose.Total for Python via .NET API.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert OFT to PCL in Python" %}}

- Open the source OFT file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your OFT file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the OFT is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For OFT to PCL conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save OFT To PCL in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}