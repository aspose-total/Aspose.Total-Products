---
title: Convert RTF to EMLX in Python
description: Save RTF to EMLX within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert RTF to EMLX using Python" h2="RTF to EMLX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert RTF to EMLX?</h2>

RTF (Rich Text Format) is a document file format developed by Microsoft Corporation. It is used to store formatted text and graphics and is supported by a wide range of word processing applications. EMLX is an email file format used by Apple Mail. It is used to store emails in a single file. Converting RTF to EMLX can be useful for a Python developer who wants to add a feature to their application that allows users to convert RTF documents to EMLX format.

<h2>How Aspose.Total helps for RTF to EMLX Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing with different formats including Email, Images and Microsoft Word formats. It includes Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs which makes the conversion of RTF to EMLX easy using Python. The conversion process is a two-step process. Firstly, the Word file is loaded and rendered into HTML via Aspose.Words for Python via .NET. Secondly, the converted HTML is loaded using Aspose.Email for Python via .NET and saved into EMLX format. This process can be automated using the Aspose.Total for Python via .NET API.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert RTF to EMLX in Python" %}}

- Open the source RTF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your RTF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the RTF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For RTF to EMLX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save RTF To EMLX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}