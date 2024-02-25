---
title: Convert WORD to EML in Python
description: Save WORD to EML within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert WORD to EML using Python" h2="WORD to EML conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert Word to EML?</h2>

Word documents are widely used for creating and editing documents, but they are not suitable for emailing. EML is a file format used for storing emails, and it is supported by most email clients. Converting Word documents to EML format allows users to easily send emails with the content of the Word document.

<h2>How Aspose.Total Helps for Word to EML Conversion?</h2>

Aspose.Total for Python via .NET is a comprehensive package of APIs that can help developers to automate the conversion process from Word to EML. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs, which makes it easy to convert Word documents to EML format using Python. The conversion process is a two-step process, firstly loading the Word file and rendering it into HTML via Aspose.Words for Python via .NET. Secondly, loading the converted HTML using Aspose.Email for Python via .NET and saving it into EML format. This makes it easy for developers to add a Word to EML conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert WORD to EML in Python" %}}

- Open the source WORD file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your WORD file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the WORD is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For WORD to EML conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save WORD To EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}