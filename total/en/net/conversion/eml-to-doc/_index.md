---
title: C# API to Export EML to DOC
description: Convert EML to DOC without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/eml-to-doc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOC
otherformats: EPUB PCL PDF JPEG DOCM BMP TEXT DOT MD RTF EMF DOTM SVG WORDML PS GIF TIFF XPS OTT ODT DOTX FLATOPC DOCX PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export EML to DOC via .NET" h2=".NET API to Render EML to DOC on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
If you are a .NET developer looking to add EML to DOC conversion features inside your applications, [Aspose.Total for .NET](https://products.aspose.com/total/net/) file format manipulation APIs are the way forward. By using [Aspose.Email for .NET](https://products.aspose.com/email/net/), you can convert EML file format to HTML. After that, by using [Aspose.Words for .NET](https://products.aspose.com/words/net/), you can render HTML to DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert EML to DOC" %}}
1. Open EML file using [MailMessage](https://apireference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert EML to HTML by using [Save](https://apireference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://apireference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to DOC format using [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load the EML file to be converted
MailMessage message = MailMessage.Load("sourceFile.eml");
// save EML as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Doc
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via .NET" %}}
Before converting EML to DOC, if you want to make sure that you are converting the correct email, you can load EML document, parse it and have a look at your desired property. By using [MapiMessage](https://apireference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://apireference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
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

{{% blocks/products/pf/feature-page-section  h2="Restrict DOC Document Editing via .NET" %}}
While saving the document from EML to DOC, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Doc
document.Save("output.doc", SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}