---
title: Convert DOTM to VCF in Python
description: Save DOTM to VCF within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: DOTM
outformat: VCF
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert DOTM to VCF using Python" h2="DOTM to VCF conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


Why to Convert

There can be various reasons for wanting to convert a DOTM file to a VCF file. For example, a user may want to share their contact information with someone who only uses VCF files, or they may want to import their contacts into a new application that only supports the VCF file format. Whatever the reason, Aspose.Total for Python via .NET can help to automate the conversion process.

How Aspose.Total Helps for DOTM to VCF Conversion

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats, including Email, Images, and Microsoft Word formats. The [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) APIs that are part of the [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) package make this conversion easy using Python.

The conversion process is a two-step process. First, load the Word file and render it into HTML via [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Secondly, load the converted HTML using [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) and save it into VCF format.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert DOTM to VCF in Python" %}}

- Open the source DOTM file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your DOTM file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the DOTM is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For DOTM to VCF conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save DOTM To VCF in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}