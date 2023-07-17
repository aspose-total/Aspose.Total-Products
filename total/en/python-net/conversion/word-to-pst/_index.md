---
title: Convert WORD to PST in Python
description: Save WORD to PST within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert WORD to PST using Python" h2="WORD to PST conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert Word to PST?</h2>

For a Python developer, who is trying to add a WORD to PST conversion feature within application, it is important to understand why this conversion is necessary. PST is a file format used by Microsoft Outlook to store emails, contacts, tasks, and other items. It is a popular format for archiving emails and other data. Converting Word documents to PST format allows users to access the documents in Outlook, making it easier to share and collaborate on documents.

<h2>How Aspose.Total Helps for Word to PST Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It provides a comprehensive set of APIs to help developers automate the conversion process. The [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) APIs that are part of [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) package makes this conversion easy using Python. It's a two step process, firstly load the Word file and render it into HTML via [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Secondly load the converted HTML using [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) and save it into PST format. The APIs provide a wide range of features to help developers customize the conversion process. For example, developers can set the PST file size limit, set the PST password, and set the PST encryption type. Additionally, developers can also add attachments to the PST file, set the PST file name, and set the PST folder structure.

Overall, Aspose.Total for Python via .NET is an ideal solution for developers who need to add a WORD to PST conversion feature within their application. It provides a comprehensive set of APIs to help developers automate the conversion process and customize it according to their needs.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert WORD to PST in Python" %}}

- Open the source WORD file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your WORD file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the WORD is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For WORD to PST conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save WORD To PST in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}