---
title: Convert RTF to EML in Python
description: Save RTF to EML within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert RTF to EML using Python" h2="RTF to EML conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is an API package that can help Python developers automate the process of converting RTF to EML. It is a comprehensive package of various APIs that can be used to deal with different file formats, including Email, Images, and Microsoft Word. The conversion process is a two-step process, which involves using the "Aspose.Words for Python via .NET" and "Aspose.Email for Python via .NET" APIs. 
The first step involves loading the Word file and rendering it into HTML using the "Aspose.Words for Python via .NET" API. The second step involves loading the converted HTML using the "Aspose.Email for Python via .NET" API and saving it into the EML format. This process is made easier by the fact that both APIs are part of the "Aspose.Total for Python via .NET" package. 
The "Aspose.Total for Python via .NET" package is a great tool for Python developers who are looking to add a RTF to EML conversion feature to their application. It is a comprehensive package that makes the conversion process easy and efficient. With the help of this package, developers can quickly and easily convert RTF to EML without any hassle.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert RTF to EML in Python" %}}

- Open the source RTF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your RTF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the RTF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For RTF to EML conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save RTF To EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}