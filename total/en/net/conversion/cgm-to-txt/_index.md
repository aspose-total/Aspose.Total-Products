---
title: Convert CGM to TXT via C# API
description: C# API to Convert CGM File to TXT without using Microsoft Excel or Adobe Reader
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS CSV EXCEL
semantic: true
page_type: generated_detail
hero:
  h1: C# API to Render CGM to TXT
  h2: Export CGM File to TXT via C# without using Microsoft<sup>&reg;</sup> Excel or Adobe<sup>&reg;</sup> Acrobat Reader
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'With Aspose.Total for .NET, converting CGM files to TXT format within .NET, C#, ASP.NET, and VB.NET applications is made easy. The process involves two simple steps using the powerful capabilities of Aspose.PDF for .NET and Aspose.Cells for .NET Spreadsheet Programming API.


        Firstly, using Aspose.PDF for .NET, you can export CGM files to XLSX (Excel) format. Aspose.PDF for .NET provides a robust API for working with PDF documents, allowing seamless CGM to XLSX conversion.


        Next, by leveraging Aspose.Cells for .NET, the Spreadsheet Programming API, you can easily convert the XLSX file to TXT format. Aspose.Cells for .NET offers a comprehensive range of features and tools to manipulate Excel files, facilitating efficient XLSX to TXT conversion.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: .NET API to Convert CGM to TXT
      items:
      - Open CGM file using [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class
      - Convert CGM to XLSX by using [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) method
      - Load XLSX document by using [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
      - Save the document to TXT format using [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) method and set `Txt` as SaveFormat
  - width: 6
    blocks:
    - type: markdown
      title: Conversion Requirements
      markdown: 'Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.


        Two [Aspose.Total for .NET](https://products.aspose.com/total/net/) child APIs, [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) and [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)  will be used.


        Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).'
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 0739adc8c301dc024f48b96d37b23dd7
        file: convert-pdf-to-excel.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: If your CGM document is password protected, you cannot convert it to TXT without the password. Using the API, you can first open the protected document using a valid password and convert it after it.  In order to open the encrypted file, you can initialize a new instance of the [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) class and pass the filename and password as arguments.
      title: Convert Protected CGM to TXT via C#
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 0739adc8c301dc024f48b96d37b23dd7
        file: convert-password-protected-pdf-to-excel.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: While converting CGM file to TXT, you can also add watermark to your output TXT file format. In order to add a watermark, you can create a new Workbook object and open the converted XLSX document, select Worksheet via its index, create a Shape and use its AddTextEffect function. After that you can save your XLSX document as TXT with Watermark.
      title: Convert CGM File to TXT with Watermark via C#
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 0739adc8c301dc024f48b96d37b23dd7
        file: convert-pdf-to-excel-with-watermark.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'CGM (Computer Graphics Metafile) files are used to store vector graphics information, making them ideal for creating static graphics and illustrations. However, when working with dynamic data, text editors like Notepad become essential for basic text manipulation and documentation.


        The conversion of CGM files into plain text formats is necessary to unlock the full potential of your text editing capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Data Documentation**: Convert CGM files to create human-readable documentation, enabling easier understanding and sharing of graphics information.

        *   **Text Manipulation**: Use Notepad to edit and manipulate plain text data extracted from CGM files, making it suitable for basic text editing tasks.

        *   **ASCII Art Creation**: Convert CGM files to ASCII art, creating simple, text-based representations of graphics for artistic or decorative purposes.

        *   **Data Import for Other Tools**: Use plain text conversion to import graphics data into other text editors or word processing software, expanding your text manipulation capabilities.

        *   **Basic Reporting and Debugging**: Convert CGM files to create basic reports and debug logs, aiding in the identification of errors and issues during the development process.'
      title: 'Transforming CGM File to TXT Programmatically : Use Cases'
- type: autogen_total
---

