---
title: Convert DOC to PST in Python
description: Save DOC to PST within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOC to PST using Python" h2="DOC to PST conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert DOC to PST?</h2>

For a Python developer, who is trying to add a DOC to PST conversion feature within application, it is important to understand why this conversion is necessary. DOC is a file format used by Microsoft Word to store documents, while PST is a file format used by Microsoft Outlook to store emails, contacts, calendar items, tasks, notes, journals, etc. Converting DOC to PST allows the user to access the content of the document in Outlook, which is a widely used email client.

<h2>How Aspose.Total helps for DOC to PST Conversion?</h2>

Aspose.Total for Python via .NET API can help to automate the conversion process. It is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that are part of Aspose.Total for Python via .NET package makes this conversion easy using Python. It is a two step process, firstly load the Word file and render it into HTML via Aspose.Words for Python via .NET. Secondly load the converted HTML using Aspose.Email for Python via .NET and save it into PST format. This process is simple and efficient, and can be easily integrated into the application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOC to PST in Python" %}}

- Open the source DOC file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your DOC file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the DOC is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For DOC to PST conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save DOC To PST in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}