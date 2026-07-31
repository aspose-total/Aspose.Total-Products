---
title: C# API to Export MSG to RTF
description: Convert MSG to RTF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/msg-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: RTF
otherformats: DOCX SVG DOTM WORDML JPEG GIF PS XPS DOT DOTX MD BMP DOC PCL OTT TIFF EMF EPUB PNG FLATOPC DOCM PDF ODT TEXT
semantic: true
page_type: generated_detail
hero:
  h1: Export MSG to RTF via .NET
  h2: .NET API to Render MSG to RTF on Windows, macOS, and Linux without using Word or Outlook
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'Aspose.Total for .NET is a comprehensive suite of file format manipulation APIs that can help .NET developers add MSG to RTF conversion features to their applications. Aspose.Email for .NET provides the ability to convert MSG files to HTML, while Aspose.Words for .NET can render HTML to RTF. This combination of APIs makes it easy to add MSG to RTF conversion features to any .NET application.


        Aspose.Email for .NET is a powerful API that allows developers to read, write, and convert MSG files. It supports a wide range of features, including the ability to convert MSG files to HTML. This makes it easy to convert MSG files to a format that can be used with Aspose.Words for .NET.


        Aspose.Words for .NET is a powerful API that allows developers to create, edit, and convert documents in a variety of formats. It supports a wide range of features, including the ability to render HTML to RTF. This makes it easy to convert HTML documents to the RTF format, which can then be used in any .NET application.


        By combining Aspose.Email for .NET and Aspose.Words for .NET, .NET developers can easily add MSG to RTF conversion features to their applications. This makes it easy to convert MSG files to RTF, which can then be used in any .NET application. Aspose.Total for .NET makes it easy to add MSG to RTF conversion features to any .NET application.'
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: C# API to Convert MSG to RTF
      items:
      - Open MSG file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
      - Convert MSG to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
      - Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class
      - Save the document to RTF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Rtf as SaveFormat
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
      gist:
        user: aspose-com-gists
        id: 5a9fece649991cb4d3f82988b0979ef7
        file: convert-email-formats-to-word.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: Before converting MSG to RTF, if you want to make sure that you are converting the correct email, you can load MSG document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property.
      title: Parse MSG File via .NET
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code example
      gist:
        user: aspose-com-gists
        id: 5a9fece649991cb4d3f82988b0979ef7
        file: parse-email-files.cs
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: While saving the document from MSG to RTF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code.
      title: Restrict RTF Document Editing via .NET
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

        // call save method while passing SaveFormat.Rtf

        document.Save("output.rtf", SaveFormat.Rtf);'
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: 'The conversion of MSG files into RTF formats is necessary to unlock the full potential of your document editing capabilities. This conversion enables you to:


        **Use Cases:**


        *   **Document Editing and Review**: Convert MSG files to review, edit, and manage documents more efficiently in Microsoft Office applications.

        *   **Business Communication Optimization**: Use RTF to create professional-looking business correspondence, meeting notes, and reports that can be easily shared with colleagues and clients.

        *   **Legacy System Compatibility**: Convert MSG files to ensure compatibility with older systems, allowing you to access and work with historical documents seamlessly.

        *   **Language Translation and Localization**: Utilize RTF to translate and localize documents for global audiences, ensuring culturally sensitive and accurate content delivery.

        *   **Archival and Preservation**: Convert MSG files to archived formats like RTF, enabling long-term preservation of important business documents and minimizing data loss risks.'
      title: 'Transforming MSG File to RTF Programmatically : Use Cases'
- type: autogen_total
---

