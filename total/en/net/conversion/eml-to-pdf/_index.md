---
title: C# API to Export EML to PDF
description: Convert EML to PDF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/eml-to-pdf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PDF
otherformats: DOCX DOC SVG FLATOPC WORDML MD PNG TIFF DOTM DOT XPS TEXT EPUB DOCM JPEG GIF PS DOTX RTF BMP OTT EMF ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export EML to PDF via .NET" h2=".NET API to Render EML to PDF on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


As a .NET developer, you may need to add EML to PDF conversion features to your applications. To do this, you can use the powerful file format manipulation APIs from Aspose.Total for .NET. Aspose.Email for .NET is the ideal solution for converting EML file format to HTML. This API is designed to make the process of converting EML to HTML as easy and straightforward as possible. Once you have the HTML, you can use Aspose.Words for .NET to render it to PDF. This API is designed to provide you with the best possible results when converting HTML to PDF.

Aspose.Total for .NET is a comprehensive suite of APIs that can help you with a wide range of file format manipulation tasks. Aspose.Email for .NET is a powerful API that can help you convert EML to HTML quickly and easily. It is designed to make the process of converting EML to HTML as simple and straightforward as possible. Once you have the HTML, you can use Aspose.Words for .NET to render it to PDF. This API is designed to provide you with the best possible results when converting HTML to PDF.

Aspose.Total for .NET is a great choice for .NET developers who need to add EML to PDF conversion features to their applications. With Aspose.Email for .NET, you can quickly and easily convert EML to HTML. And with Aspose.Words for .NET, you can render HTML to PDF with the best possible results. So if you are a .NET developer looking to add EML to PDF conversion features to your applications, Aspose.Total for .NET is the way forward.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert EML to PDF" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PDF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pdf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load the EML file to be converted
MailMessage message = MailMessage.Load("sourceFile.eml");
// save EML as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Pdf
document.Save("output.pdf", SaveFormat.Pdf); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via .NET" %}}
Before converting EML to PDF, if you want to make sure that you are converting the correct email, you can load EML document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
{{% blocks/products/pf/feature-page-code %}}
```cs// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
// check for SenderName 
if(outlookMessageFile.SenderName == "John"){
    //proceed with conversion process
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict PDF Document Editing via .NET" %}}
While saving the document from EML to PDF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
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