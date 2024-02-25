---
title: C# API to Export MSG to PDF
description: Convert MSG to PDF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOT ODT WORDML JPEG PCL EMF TEXT RTF EPUB FLATOPC BMP SVG GIF OTT PS DOCX MD TIFF DOTM PNG DOCM XPS DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export MSG to PDF via C# .NET Core" h2=".NET API to Render MSG as PDF on Windows, macOS, and Linux without using Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Why Convert MSG to PDF format?</h2>

Converting MSG files to PDF through .NET or an application is essential for universal compatibility, data security, email archiving, professional presentation, reduced storage space, and easy printing. PDF's universality ensures seamless sharing across devices, while robust security features protect sensitive information. PDFs preserve email formatting for professional presentations and efficient archiving, reducing storage requirements and facilitating hassle-free printing, making it a versatile choice for various use cases.

<h2 class="heading-border">How Aspose.Total can help in MSG to PDF Conversion?</h2>

If you are a .NET developer seeking to seamlessly integrate MSG to PDF conversion capabilities within your applications, [Aspose.Total for .NET](https://products.aspose.com/total/net/) provides a powerful solution. Utilizing Aspose.Email for .NET, you can efficiently transform MSG files into HTML. Subsequently, leverage Aspose.Words for .NET to effortlessly render HTML content into high-quality PDFs. This comprehensive approach ensures a smooth and effective transition of MSG documents to PDF format, enhancing the document management capabilities of your applications.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Convert MSG to PDF via C#" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert MSG to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PDF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pdf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="MSG to PDF Converter API" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```. Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load the MSG file to be converted
MailMessage message = MailMessage.Load("sourceFile.msg");
// save MSG as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Pdf
document.Save("output.pdf", SaveFormat.Pdf); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse MSG File via .NET" %}}
Before converting MSG to PDF, if you want to make sure that you are converting the correct email, you can load MSG document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
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
While saving the document from MSG to PDF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
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