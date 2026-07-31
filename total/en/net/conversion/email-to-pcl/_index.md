---
title: C# API to Export EMAIL to PCL
description: Convert EMAIL to PCL without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/email-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PCL
otherformats: DOTX EPUB ODT RTF GIF DOCX FLATOPC DOC TIFF JPEG EMF SVG PS BMP MD DOT PDF OTT PNG TEXT DOCM XPS WORDML DOTM
semantic: true
page_type: generated_detail
hero:
  h1: Export EMAIL to PCL via .NET
  h2: .NET API to Render EMAIL to PCL on Windows, macOS, and Linux without using Word or Outlook
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'As a .NET developer, you may need to add EMAIL to PCL conversion features to your applications. To do this, you can use the powerful file format manipulation APIs provided by Aspose.Total for .NET. Aspose.Email for .NET is a comprehensive API that allows you to convert EMAIL file format to HTML. Once you have the HTML, you can use Aspose.Words for .NET to render it to PCL.


        Aspose.Total for .NET is a suite of APIs that provides a comprehensive set of features for manipulating file formats. It includes APIs for manipulating Microsoft Office documents, PDFs, images, and other file formats. Aspose.Email for .NET is a powerful API that allows you to convert EMAIL file format to HTML. It supports a wide range of EMAIL file formats, including MSG, EML, MHTML, and EMLX. It also provides features for managing attachments, extracting message headers, and more.


        Once you have the HTML, you can use Aspose.Words for .NET to render it to PCL. Aspose.Words for .NET is a powerful API that allows you to create, edit, and convert documents in a variety of formats. It supports a wide range of document formats, including DOC, DOCX, RTF, HTML, and PCL. It also provides features for manipulating document elements, such as paragraphs, tables, and images.


        By using Aspose.Total for .NET, you can easily add EMAIL to PCL conversion features to your applications. Aspose.Email for .NET allows you to convert EMAIL file format to HTML, and Aspose.Words for .NET allows you to render HTML to PCL. With these powerful APIs, you can quickly and easily add EMAIL to PCL conversion features to your applications.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: C# API to Convert EMAIL to PCL
      items:
      - Open EMAIL file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
      - Convert EMAIL to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
      - Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
      - Save the document to PCL format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pcl as SaveFormat
  - width: 6
    blocks:
    - type: markdown
      title: Conversion Requirements
      markdown: 'Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.


        Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).'
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      language: cs// load the email file to be converted
      code: "MailMessage message = MailMessage.Load(\"sourceFile.msg\");\n// save EMAIL as a HTML \nmessage.Save(\"HtmlOutput.html\", SaveOptions.DefaultHtml);\n// load HTML with an instance of Document\nDocument document = new Document(\"HtmlOutput.html\");\n// call save method while passing SaveFormat.Pcl\ndocument.Save(\"output.pcl\", SaveFormat.Pcl);"
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: Before converting EMAIL to PCL, if you want to make sure that you are converting the correct email, you can load EMAIL document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property.
      title: Parse EMAIL File via .NET
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      language: cs// instantiate mapimessage to load an msg file from disk
      code: "var outlookMessageFile = MapiMessage.FromFile(\"message.msg\");\n// check for SenderName \nif(outlookMessageFile.SenderName == \"John\"){\n    //proceed with conversion process\n}"
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: While saving the document from EMAIL to PCL, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code.
      title: Restrict PCL Document Editing via .NET
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      language: cs// load html with an instance of document
      code: 'Document document = new Document("HtmlOutput.html");

        // apply document protection and set protection password

        doc.Protect(ProtectionType.ReadOnly, "password");

        // call save method while passing SaveFormat.Pcl

        document.Save("output.pcl", SaveFormat.Pcl);'
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'Converting Email Files into PCL Formats is Necessary to Unlock the Full Potential of Your Printing Capabilities.


        The conversion of email files into PCL (Printer Control Language) formats is essential to unlock the full potential of your printing capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Automated Print Job Scheduling**: Convert email files to schedule print jobs automatically, ensuring that documents are printed on time and reducing manual effort.

        *   **Customized Print Settings**: Use PCL formats to apply customized print settings, such as paper size, orientation, and font styles, to enhance the printing experience.

        *   **Real-time Print Monitoring**: Convert email files into real-time print monitoring systems, enabling instant tracking of print jobs and optimizing print resources.

        *   **Secure Document Printing**: Use PCL formats to implement secure document printing features, such as encryption and authentication, to protect sensitive information.

        *   **Streamlined Print Workflow**: Convert email files to streamline print workflow processes, reducing the time spent on manual print job preparation and increasing productivity.'
      title: 'Transforming EMAIL File to PCL Programmatically : Use Cases'
- type: autogen_total
---

