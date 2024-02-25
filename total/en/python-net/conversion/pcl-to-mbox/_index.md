---
title: Convert PCL to MBOX in Python
description: Save PCL to MBOX within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: PCL
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PCL to MBOX using Python" h2="PCL to MBOX conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PCL to MBOX</h2>

PCL (Printer Command Language) is a page description language developed by Hewlett-Packard (HP) to provide a way to control HP printers. It is a language used to describe the appearance of a printed page and is supported by a wide variety of printers. MBOX is a popular file format used to store email messages. It is used by many email clients such as Mozilla Thunderbird, Apple Mail, Eudora, etc. Converting PCL to MBOX can be useful for a Python developer who wants to add a PCL to MBOX conversion feature within an application.

<h2>How Aspose.Total helps for PCL to MBOX Conversion</h2>

Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It provides a comprehensive set of APIs to automate the conversion process. It includes [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) and [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) APIs that makes the conversion of PCL to MBOX easy using Python. It is a two step process, firstly load the Word file and render it into HTML via [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). Secondly load the converted HTML using [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) and save it into MBOX format. The API provides a simple and easy to use interface that can be used to convert PCL to MBOX with just a few lines of code. It also supports various other features such as setting the encoding type, setting the MIME type, etc. which makes it a powerful and reliable solution for PCL to MBOX conversion.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PCL to MBOX in Python" %}}

- Open the source PCL file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your PCL file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the PCL is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PCL to MBOX conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PCL To MBOX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}