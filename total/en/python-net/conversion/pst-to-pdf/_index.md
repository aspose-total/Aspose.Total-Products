---
title: Convert PST to PDF in Python
description: Save PST to PDF in your Python applications without using Microsoft Outlook or Word 

family: total
platformtag: Python
feature: conversion
informat: PST
outformat: PDF
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convert PST to PDF using Python" h2="PST to PDF conversion in your Python Applications without installing Microsoft Word<sup>&reg;</sup> or Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}
Aspose.Total for Python via .NET" is an API package that can help Python developers automate the process of converting PST to PDF. It is a comprehensive package of APIs that can handle various formats, including Email, Images, and Microsoft Word. The conversion process is a two-step process. Firstly, the Email is loaded and rendered into HTML using the "Aspose.Email for Python via .NET" API. Secondly, the converted HTML is loaded using the "Aspose.Words for Python via .NET" API and saved into the respective Word PDF format.
The "Aspose.Total for Python via .NET" package is easy to use and provides a reliable and efficient way to convert PST to PDF. It is a great tool for developers who need to add a PST to PDF conversion feature to their applications. The APIs are well-documented and provide detailed instructions on how to use them. Furthermore, the package is regularly updated with new features and bug fixes, ensuring that the conversion process is always up-to-date.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert PST to PDF in Python" %}}

- Open the source PST file using MailMessage.load class
- Call the `save` method while specifying output HTML file path and relevant HTML Save options as parameter. So your PST file is converted to HTML at the specified path
- Now Load the saved HTML file using [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Call the save method with relevant file path. So finally the PST is converted

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}

- For PST to PDF conversion, Python 3.5 or later is required
- Reference APIs within the project directly from PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) and [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Or use the following pip command ```pip install aspose.words``` and ```pip install Aspose.Email-for-Python-via-NET``` 
- Moreover, Microsoft Windows or Linux based OS (see more for [Words](https://docs.aspose.com/words/python-net/system-requirements/) and [Email](https://docs.aspose.com/email/python-net/system-requirements/)) and for Linux check additional requirements for gcc and libpython and follow step by step instructions [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Save PST To PDF in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}