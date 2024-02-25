---
title: Convert RTF to OFT in Python
description: Save RTF to OFT within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: OFT
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert RTF to OFT using Python" h2="RTF to OFT conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert RTF to OFT</h2>

RTF (Rich Text Format) is a document format developed by Microsoft that allows users to write and save documents with formatting options such as bold, italic, underline, font size, font color, etc. OFT (Outlook Template) is a file format used by Microsoft Outlook to store email messages, contacts, calendar items, tasks, and other Outlook items. It is used to create a template for emails, which can be used to quickly create emails with the same formatting and content. Converting RTF to OFT allows users to create Outlook templates from existing RTF documents.

<h2>How Aspose.Total helps for RTF to OFT Conversion</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that make it easy to convert RTF to OFT using Python. It is a two step process, firstly load the Word file and render it into HTML via Aspose.Words for Python via .NET. Secondly load the converted HTML using Aspose.Email for Python via .NET and save it into OFT format. This process can be automated using Python, making it easier for developers to add the RTF to OFT conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert RTF to OFT in Python" %}}

- Open the source RTF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your RTF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the RTF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For RTF to OFT conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save RTF To OFT in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}