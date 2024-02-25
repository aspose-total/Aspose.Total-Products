---
title: Convert DOCX to PST in Python
description: Save DOCX to PST within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOCX to PST using Python" h2="DOCX to PST conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is a comprehensive package of APIs that can help a Python developer to automate the process of converting a DOCX file to PST format. It includes two APIs, namely Aspose.Words for Python via .NET and Aspose.Email for Python via .NET, which make the conversion process easy. The conversion process is a two-step process. Firstly, the Word file is loaded and rendered into HTML using Aspose.Words for Python via .NET. Secondly, the converted HTML is loaded using Aspose.Email for Python via .NET and saved into PST format. 
The APIs provided by Aspose.Total for Python via .NET are easy to use and provide a reliable and efficient way to convert DOCX to PST format. It also offers a wide range of features such as support for various file formats, support for different versions of Microsoft Office, and support for various programming languages. Furthermore, the APIs are highly secure and provide a high level of data integrity. Therefore, Aspose.Total for Python via .NET is an ideal choice for a Python developer who is looking to add a DOCX to PST conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOCX to PST in Python" %}}

- Open the source DOCX file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your DOCX file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the DOCX is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For DOCX to PST conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save DOCX To PST in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}