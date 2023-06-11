---
title: Convert PDF to PST in Python
description: Save PDF to PST within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PDF to PST using Python" h2="PDF to PST conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is an API package that provides a comprehensive solution for developers who are looking to add a PDF to PST conversion feature within their application. It is a full package of various APIs that deal with different formats such as Email, Images, and Microsoft Word formats. The two APIs that are part of the package, Aspose.Words for Python via .NET and Aspose.Email for Python via .NET, make the conversion process easy and efficient. 
The process of converting a PDF to PST format is a two-step process. Firstly, the Word file is loaded and rendered into HTML using Aspose.Words for Python via .NET. Secondly, the converted HTML is loaded using Aspose.Email for Python via .NET and saved into PST format. The APIs provide a wide range of features that make the conversion process easier and more efficient. For example, the APIs provide support for various file formats, including DOC, DOCX, HTML, and PDF. Additionally, the APIs also provide support for various image formats, such as JPEG, PNG, and TIFF. 
Overall, Aspose.Total for Python via .NET is an ideal solution for developers who are looking to add a PDF to PST conversion feature within their application. The APIs provide a comprehensive solution that makes the conversion process easier and more efficient. With the help of the APIs, developers can easily convert PDF files to PST format with just a few lines of code.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PDF to PST in Python" %}}

- Open the source PDF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your PDF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the PDF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PDF to PST conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PDF To PST in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}