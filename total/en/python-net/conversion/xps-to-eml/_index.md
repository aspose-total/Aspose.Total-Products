---
title: Convert XPS to EML in Python
description: Save XPS to EML within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert XPS to EML using Python" h2="XPS to EML conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to EML?</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft for printing and viewing documents. It is similar to PDF format but is more structured and can be easily edited. EML (Electronic Mail) is a file format used for storing emails. It is widely used by email clients like Outlook, Thunderbird, etc. for storing emails. Converting XPS to EML format can be useful for developers who want to add a feature of converting XPS documents to EML format within their application.

<h2>How Aspose.Total helps for XPS to EML Conversion?</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It includes [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) APIs that can be used for XPS to EML conversion. It is a two step process, firstly load the Word file and render it into HTML via [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Secondly load the converted HTML using [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) and save it into EML format. This process can be automated using Python and Aspose.Total for Python via .NET API. It is a reliable and efficient way to convert XPS to EML format.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert XPS to EML in Python" %}}

- Open the source XPS file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your XPS file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the XPS is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For XPS to EML conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save XPS To EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}