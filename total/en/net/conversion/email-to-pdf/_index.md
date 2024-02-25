---
title: C# API to Export EMAIL to PDF
description: Convert EMAIL to PDF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML BMP EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export EMAIL to PDF via .NET" h2=".NET API to Render EMAIL to PDF on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of file format manipulation APIs that can be used by .NET developers to add EMAIL to PDF conversion features to their applications. Aspose.Email for .NET is a powerful API that enables developers to convert EMAIL file format to HTML. Once the EMAIL file is converted to HTML, Aspose.Words for .NET can be used to render the HTML to PDF. This way, developers can easily add EMAIL to PDF conversion features to their applications.

The Aspose.Total for .NET suite offers a wide range of features that make it easy for developers to manipulate various file formats. It includes APIs for manipulating Word, Excel, PowerPoint, PDF, Outlook, and other file formats. Aspose.Email for .NET is a powerful API that enables developers to read, write, and convert EMAIL file formats. It supports a wide range of EMAIL file formats, including MSG, EML, EMLX, and MHT. It also provides features for managing attachments, managing message headers, and more.

Aspose.Words for .NET is a powerful API that enables developers to create, edit, and convert documents in various file formats. It supports a wide range of document formats, including DOC, DOCX, RTF, HTML, and PDF. It also provides features for manipulating document elements, such as text, images, tables, and more. With Aspose.Words for .NET, developers can easily render HTML to PDF.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert EMAIL to PDF" %}}
1. Open EMAIL file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert EMAIL to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PDF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pdf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load the EMAIL file to be converted
MailMessage message = MailMessage.Load("sourceFile.msg");
// save EMAIL as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Pdf
document.Save("output.pdf", SaveFormat.Pdf); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMAIL File via .NET" %}}
Before converting EMAIL to PDF, if you want to make sure that you are converting the correct email, you can load EMAIL document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
{{% blocks/products/pf/feature-page-code %}}
```cs// instantiate MapiMessage to load an MSG file from disk
var outlookMessageFile = MapiMessage.FromFile("message.msg");
// check for SenderName 
if(outlookMessageFile.SenderName == "John"){
    //proceed with conversion process
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict PDF Document Editing via .NET" %}}
While saving the document from EMAIL to PDF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Pdf
document.Save("output.pdf", SaveFormat.Pdf);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}