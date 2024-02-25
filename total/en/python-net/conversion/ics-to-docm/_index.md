---
title: Convert ICS to DOCM in Python
description: Save ICS to DOCM in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: ICS
outformat: DOCM
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert ICS to DOCM using Python" h2="ICS to DOCM conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert ICS to DOCM?</h2>

ICS (iCalendar) is a popular file format used to store calendar information such as events, to-dos, and other calendar related data. It is widely used by many calendar applications such as Google Calendar, Apple Calendar, Microsoft Outlook, etc. DOCM is a Microsoft Word document format that supports macros. It is used to store documents that contain macros and scripts. Converting ICS to DOCM allows users to access calendar information in a Word document format.

<h2>How Aspose.Total Helps for ICS to DOCM Conversion?</h2>

Aspose.Total for Python via .NET is a comprehensive package of APIs that helps developers to automate the conversion process of ICS to DOCM. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that makes the conversion easy using Python. It is a two step process, firstly load Email and render it into HTML via Aspose.Email for Python via .NET. Secondly load the converted HTML using Aspose.Words for Python via .NET and save it into respective Word DOCM format. Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It helps developers to easily integrate ICS to DOCM conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert ICS to DOCM in Python" %}}

- Open the source ICS file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your ICS file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the ICS is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For ICS to DOCM conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save ICS To DOCM in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}