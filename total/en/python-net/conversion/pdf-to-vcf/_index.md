---
title: Convert PDF to VCF in Python
description: Save PDF to VCF within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: VCF
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to VCF using Python" h2="PDF to VCF conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is a comprehensive package of APIs that can help a Python developer automate the process of converting PDF to VCF. It includes APIs for dealing with different formats such as Email, Images and Microsoft Word. The conversion process is a two-step process. Firstly, the Word file needs to be loaded and rendered into HTML using the "Aspose.Words for Python via .NET" API. Secondly, the converted HTML needs to be loaded using the "Aspose.Email for Python via .NET" API and saved into VCF format.
The "Aspose.Total for Python via .NET" package makes the conversion process easy and efficient. It provides a comprehensive set of APIs that can be used to convert PDF to VCF quickly and accurately. The APIs are easy to use and can be integrated into any existing application. Furthermore, the package is regularly updated to ensure that it is compatible with the latest versions of Python. This makes it an ideal choice for developers who are looking to add a PDF to VCF conversion feature within their application.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to VCF in Python" %}}

- Open the source PDF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your PDF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the PDF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PDF to VCF conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PDF To VCF in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}