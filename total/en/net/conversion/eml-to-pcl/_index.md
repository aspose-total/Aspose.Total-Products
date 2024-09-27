---
title: C# API to Export EML to PCL
description: Convert EML to PCL without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/eml-to-pcl/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PCL
otherformats: MD DOCX RTF WORDML ODT BMP SVG DOT DOC XPS DOTM JPEG OTT PDF EPUB PS TIFF GIF TEXT PNG DOTX DOCM FLATOPC EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export EML to PCL via .NET" h2=".NET API to Render EML to PCL on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


As a .NET developer, you may need to add EML to PCL conversion features to your applications. To do this, you can use the powerful file format manipulation APIs provided by Aspose.Total for .NET. Aspose.Email for .NET is a comprehensive library that allows you to convert EML files to HTML. Once the conversion is complete, you can use Aspose.Words for .NET to render the HTML to PCL.

Aspose.Total for .NET is a suite of APIs that provides a wide range of features for manipulating file formats. It includes APIs for manipulating Microsoft Office documents, PDFs, images, and emails. Aspose.Email for .NET is a powerful library that enables you to read, write, and convert emails in various formats, including EML. It also provides features for managing email attachments, creating and sending emails, and more.

Aspose.Words for .NET is a library that enables you to create, read, and manipulate documents in various formats, including HTML. It provides features for creating, editing, and converting documents, as well as for rendering documents to various formats, such as PCL. With Aspose.Words for .NET, you can easily render HTML to PCL.

By using Aspose.Total for .NET, you can easily add EML to PCL conversion features to your applications. Aspose.Email for .NET allows you to convert EML files to HTML, and Aspose.Words for .NET enables you to render HTML to PCL. With these powerful APIs, you can quickly and easily add EML to PCL conversion features to your applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert EML to PCL" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to PCL format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Pcl as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
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
// call save method while passing SaveFormat.Pcl
document.Save("output.pcl", SaveFormat.Pcl); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via .NET" %}}
Before converting EML to PCL, if you want to make sure that you are converting the correct email, you can load EML document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
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

{{% blocks/products/pf/feature-page-section  h2="Restrict PCL Document Editing via .NET" %}}
While saving the document from EML to PCL, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
{{% blocks/products/pf/feature-page-code %}}
```cs// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Pcl
document.Save("output.pcl", SaveFormat.Pcl);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}