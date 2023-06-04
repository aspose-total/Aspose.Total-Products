---
title: C# API to Export OFT to DOC
description: Convert OFT to DOC without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/oft-to-doc/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOC
otherformats: PS SVG XPS MD TEXT PDF OTT DOTX EMF DOCX RTF BMP PCL ODT JPEG GIF EPUB FLATOPC TIFF DOCM DOTM PNG DOT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export OFT to DOC via .NET" h2=".NET API to Render OFT to DOC on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

As a .NET developer, you may need to add OFT to DOC conversion features to your applications. Aspose.Total for .NET is the perfect solution for this. It is a comprehensive suite of file format manipulation APIs that can help you achieve this goal. 

Aspose.Email for .NET is the first step in the process. It allows you to convert OFT file format to HTML. This is done by using the MailMessage.Save(string, SaveOptions) method. This method takes two parameters, the first being the file name and the second being the SaveOptions object. The SaveOptions object contains the SaveFormat property which can be set to Html. 

The next step is to render the HTML to DOC. This is done by using Aspose.Words for .NET. The Document.Save(string, SaveOptions) method can be used to save the HTML as a DOC file. The SaveOptions object contains the SaveFormat property which can be set to Doc. 

In conclusion, Aspose.Total for .NET is the perfect solution for .NET developers who need to add OFT to DOC conversion features to their applications. Aspose.Email for .NET can be used to convert OFT file format to HTML and Aspose.Words for .NET can be used to render HTML to DOC.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert OFT to DOC" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to DOC format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cs// load the OFT file to be converted
MailMessage message = MailMessage.Load("sourceFile.oft");
// save OFT as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Doc
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via .NET" %}}
Before converting OFT to DOC, if you want to make sure that you are converting the correct email, you can load OFT document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
{{% blocks/products/pf/feature-page-code %}}
```cs// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
// check for SenderName 
if(outlookMessageFile.SenderName == "John"){
    //proceed with conversion process
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict DOC Document Editing via .NET" %}}
While saving the document from OFT to DOC, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
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
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}