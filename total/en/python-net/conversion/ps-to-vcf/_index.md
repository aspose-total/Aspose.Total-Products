---
title: Convert PS to VCF in Python
description: Save PS to VCF within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: PS
outformat: VCF
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PS to VCF using Python" h2="PS to VCF conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PS to VCF?</h2>

The Portable Document Format (PDF) is a popular file format used for documents that need to be shared and printed. However, it is not suitable for storing contact information. The vCard (VCF) format is a standard for storing contact information, such as names, addresses, phone numbers, and email addresses. It is a much more efficient way to store contact information than PDF. Therefore, it is necessary to convert PDF to VCF in order to store contact information in a more efficient way.

<h2>How Aspose.Total Helps for PS to VCF Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It is a great tool for Python developers who are looking to add a PS to VCF conversion feature within their application. Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that are part of Aspose.Total for Python via .NET package makes this conversion easy using Python. It is a two step process, firstly load the Word file and render it into HTML via Aspose.Words for Python via .NET. Secondly load the converted HTML using Aspose.Email for Python via .NET and save it into VCF format. This process is automated and makes it easier for developers to add this feature to their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PS to VCF in Python" %}}

- Open the source PS file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your PS file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the PS is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PS to VCF conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PS To VCF in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}