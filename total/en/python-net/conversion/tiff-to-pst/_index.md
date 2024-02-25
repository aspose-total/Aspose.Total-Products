---
title: Convert TIFF to PST in Python
description: Save TIFF to PST within Python applications without using Microsoft Word or Outlook

family: total
platformtag: Python
feature: conversion
informat: TIFF
outformat: PST
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert TIFF to PST using Python" h2="TIFF to PST conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
TIFF (Tagged Image File Format) is a raster graphics image format used for storing images. It is widely used for storing images and is supported by almost all image editing applications. PST (Personal Storage Table) is a file format used by Microsoft Outlook to store emails, contacts, notes, tasks, journals, and calendar items. It is a popular file format used by many organizations for archiving emails. Therefore, it is important to convert TIFF to PST for archiving emails and other Outlook items.

<h2>How Aspose.Total helps for tiff to pst conversion</h2>
Aspose.Total for Python via .NET is a full package of various APIs dealing different formats including Email, Images and Microsoft Word formats. It helps to automate the conversion process of TIFF to PST. It is a two step process, firstly load the Word file and render it into HTML via Aspose.Words for Python via .NET. Secondly load the converted HTML using Aspose.Email for Python via .NET and save it into PST format. Aspose.Words for Python via .NET and Aspose.Email for Python via .NET APIs that are part of Aspose.Total for Python via .NET package makes this conversion easy using Python.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert TIFF to PST in Python" %}}

- Open the source TIFF file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your TIFF file is converted to HTML at the specified path
- Now Load the saved HTML file using MailMessage.load
- Call the save method with relevant file path. So finally the TIFF is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For TIFF to PST conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save TIFF To PST in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}