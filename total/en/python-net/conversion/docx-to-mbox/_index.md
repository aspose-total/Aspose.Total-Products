---
title: Convert DOCX to MBOX in Python
description: Save DOCX to MBOX within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to MBOX using Python" h2="DOCX to MBOX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is a comprehensive package of APIs that can help a Python developer to automate the process of converting a DOCX file to MBOX format. It contains two APIs, namely Aspose.Words for Python via .NET and Aspose.Email for Python via .NET, which are specifically designed to facilitate the conversion process. The conversion process is a two-step process. Firstly, the Word file is loaded and rendered into HTML using Aspose.Words for Python via .NET. Secondly, the converted HTML is loaded using Aspose.Email for Python via .NET and saved into MBOX format.
The Aspose.Total for Python via .NET package is a great tool for developers who are looking to add DOCX to MBOX conversion feature within their application. It is easy to use and provides a reliable and efficient way to convert Word documents to MBOX format. Furthermore, the package also provides support for other formats such as Email, Images and Microsoft Word formats. This makes it a great choice for developers who are looking to add DOCX to MBOX conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOCX to MBOX in Python" %}}

- Open the source DOCX file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your DOCX file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the DOCX is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For DOCX to MBOX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save DOCX To MBOX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}