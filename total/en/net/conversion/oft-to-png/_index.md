---
title: C# API to Export OFT to PNG
description: Convert OFT to PNG without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/oft-to-png/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PNG
otherformats: EPUB DOCX SVG JPEG FLATOPC TIFF RTF PS WORDML PCL ODT GIF TEXT MD DOTM BMP DOC DOTX PDF OTT XPS EMF DOCM DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export OFT to PNG via .NET" h2=".NET API to Render OFT to PNG on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

Aspose.Total for .NET is a comprehensive suite of APIs that enables .NET developers to add powerful file format manipulation features to their applications. With Aspose.Total for .NET, you can easily convert OFT files to PNG. The process involves two steps. First, you need to use Aspose.Email for .NET to convert the OFT file format to HTML. Then, you can use Aspose.Words for .NET to render the HTML to PNG.

Aspose.Email for .NET is a powerful API that enables you to manipulate Outlook message files. It provides a wide range of features that allow you to read, write, and convert Outlook message files. It also supports a variety of file formats, including OFT. With Aspose.Email for .NET, you can easily convert OFT files to HTML.

Aspose.Words for .NET is a powerful API that enables you to manipulate Word documents. It provides a wide range of features that allow you to read, write, and convert Word documents. It also supports a variety of file formats, including HTML. With Aspose.Words for .NET, you can easily render HTML to PNG.

In conclusion, Aspose.Total for .NET is the perfect solution for .NET developers who need to add OFT to PNG conversion features to their applications. With Aspose.Email for .NET, you can convert OFT files to HTML. Then, with Aspose.Words for .NET, you can render HTML to PNG.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert OFT to PNG" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PNG format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Png as SaveFormat
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
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via .NET" %}}
Before converting OFT to PNG, if you want to make sure that you are converting the correct email, you can load OFT document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
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

{{% blocks/products/pf/feature-page-section  h2="Restrict PNG Document Editing via .NET" %}}
While saving the document from OFT to PNG, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}