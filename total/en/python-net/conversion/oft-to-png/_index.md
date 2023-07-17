---
title: Convert OFT to PNG in Python
description: Save OFT to PNG in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: OFT
outformat: PNG
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert OFT to PNG using Python" h2="OFT to PNG conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert OFT to PNG</h2>

For a Python developer, the need to convert OFT to PNG arises when they are trying to add a feature within their application that requires the conversion of Outlook template files to PNG images. OFT files are Outlook template files that are used to create emails, calendar events, and other Outlook items. They are used to store the formatting and content of an Outlook item, and can be used to quickly create multiple Outlook items with the same formatting and content. However, they cannot be used in applications that require a PNG image, such as web applications. Therefore, it is necessary to convert OFT files to PNG images in order to use them in such applications.

<h2>How Aspose.Total Helps for OFT to PNG Conversion</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It provides two APIs, Aspose.Words for Python via .NET and Aspose.Email for Python via .NET, which can be used to automate the conversion process from OFT to PNG. The conversion process is a two-step process. Firstly, the OFT file is loaded using Aspose.Email for Python via .NET and rendered into HTML. Secondly, the converted HTML is loaded using Aspose.Words for Python via .NET and saved into the respective Word PNG format. This makes the conversion process easy and efficient using Python.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert OFT to PNG in Python" %}}

- Open the source OFT file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your OFT file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the OFT is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For OFT to PNG conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save OFT To PNG in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}