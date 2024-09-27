---
title: C# API to Export EML to RTF
description: Convert EML to RTF without using Microsoft Word or Outlook on .NET
url_ignore: /net/conversion/eml-to-rtf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: RTF
otherformats: PCL JPEG SVG OTT PNG GIF MD DOTM TIFF DOTX DOCX WORDML XPS DOCM TEXT BMP EPUB PDF PS FLATOPC ODT EMF DOT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Export EML to RTF via .NET" h2=".NET API to Render EML to RTF on Windows, macOS, and Linux without using Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

As a .NET developer, you may need to add EML to RTF conversion features to your applications. To do this, you can use the powerful file format manipulation APIs from Aspose.Total for .NET. Aspose.Email for .NET provides the ability to convert EML files to HTML. With Aspose.Words for .NET, you can then render the HTML to RTF. This two-step process is simple and efficient, allowing you to quickly and easily add the desired features to your applications.

Aspose.Total for .NET is a comprehensive suite of APIs that provides a wide range of features for manipulating file formats. Aspose.Email for .NET is a powerful API for working with email messages, allowing you to read, write, and convert emails in various formats. It also provides the ability to convert EML files to HTML. Aspose.Words for .NET is a powerful API for working with documents, allowing you to create, edit, and convert documents in various formats. It also provides the ability to render HTML to RTF.

By using Aspose.Total for .NET, you can quickly and easily add EML to RTF conversion features to your applications. The two-step process of converting EML to HTML with Aspose.Email for .NET and then rendering HTML to RTF with Aspose.Words for .NET is simple and efficient. With the powerful APIs from Aspose.Total for .NET, you can easily add the desired features to your applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API to Convert EML to RTF" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) class
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) method
3. Load HTML by using [Document](https://reference.aspose.com/words/net/aspose.words/document) class 
4. Save the document to RTF format using [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) method and set Rtf as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion Requirements" %}}
Install from command line as ```nuget install Aspose.Total``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via .NET" %}}
Before converting EML to RTF, if you want to make sure that you are converting the correct email, you can load EML document, parse it and have a look at your desired property. By using [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) class of [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, you can get sender and recipients information. For example, you can check for a specific sender email for the conversion by using [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) property. 
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict RTF Document Editing via .NET" %}}
While saving the document from EML to RTF, you might need to protect your output document. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. This can be useful to prevent other people from editing sensitive and confidential information in your document. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) enumeration parameter. You can set your document to read-only by using the following lines of code. 
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