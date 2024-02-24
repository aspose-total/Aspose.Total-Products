---
title: C# API to Export OFT to RTF
description: Convert OFT to RTF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/oft-to-rtf/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: RTF
otherformats: PNG WORDML JPEG OTT BMP TEXT MD DOT XPS EMF PCL SVG PS DOCM PDF DOCX DOTX TIFF DOTM EPUB GIF DOC FLATOPC ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export OFT to RTF via .NET" h2=".NET API to Render OFT to RTF on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


As a .NET developer, you may need to add OFT to RTF conversion features inside your applications. To do this, you can use the powerful file format manipulation APIs provided by Aspose.Total for .NET. Aspose.Total for .NET is a suite of APIs that allow you to manipulate various file formats, including OFT and RTF.

Using Aspose.Email for .NET, you can easily convert OFT file format to HTML. Aspose.Email for .NET is a powerful API that allows you to manipulate emails and other message formats. It provides a wide range of features, including the ability to convert OFT to HTML.

Once you have converted the OFT file to HTML, you can use Aspose.Words for .NET to render the HTML to RTF. Aspose.Words for .NET is a powerful API that allows you to manipulate documents in various formats, including RTF. It provides a wide range of features, including the ability to render HTML to RTF.

By using Aspose.Total for .NET, you can easily add OFT to RTF conversion features to your applications. Aspose.Total for .NET provides a suite of powerful APIs that allow you to manipulate various file formats, including OFT and RTF. With Aspose.Email for .NET, you can convert OFT to HTML, and with Aspose.Words for .NET, you can render HTML to RTF.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert OFT to RTF" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to RTF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Rtf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with .NET File Format APIs" %}}
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
// call save method while passing SaveFormat.Rtf
document.Save("output.rtf", SaveFormat.Rtf); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via .NET" %}}
Before converting OFT to RTF, if you want to make sure that you are converting the correct email, you can load OFT document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
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

{{% blocks/products/pf/feature-page-section  h2="Restrict RTF Document Editing via .NET" %}}
While saving the document from OFT to RTF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Rtf
document.Save("output.rtf", SaveFormat.Rtf);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}