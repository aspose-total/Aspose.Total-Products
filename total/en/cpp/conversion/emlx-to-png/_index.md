---
title: Export EMLX to PNG via C++
description: C++ API to Convert EMLX to PNG without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/emlx-to-png/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PNG
otherformats: DOTM FLATOPC DOC BMP PCL EMF RTF TEXT DOCM PS DOTX DOCX PDF GIF SVG EPUB DOT TIFF WORDML OTT XPS ODT JPEG MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EMLX to PNG" h2="Transform EMLX to PNG within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. This could be for a variety of reasons, such as to make the emails easier to read, to make them more accessible, or to make them easier to store and share.

<h2>How Aspose.Total Helps for EMLX to PNG Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that can help you to easily add email conversion features to your applications. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert EMLX file format to HTML and then export HTML to PNG. 

Using Aspose.Email for C++, you can easily convert EMLX files to HTML. This API supports a wide range of email file formats, including EML, MSG, MHTML, and EMLX. It also provides a range of features, such as the ability to read and write email messages, convert emails to different formats, and extract attachments from emails.

Once you have converted the EMLX file to HTML, you can use Aspose.Words for C++ to export the HTML to PNG. This API provides a range of features for working with documents, including the ability to create, edit, and convert documents to different formats. It also supports a wide range of document formats, including DOC, DOCX, HTML, and PDF.

By using Aspose.Total for C++, you can easily add email conversion features to your applications. This suite of APIs makes it easy to convert EMLX files to HTML and then export HTML to PNG.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EMLX to PNG" %}}
1. Open EMLX file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EMLX to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to PNG format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Png as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMLX File via C++" %}}
Not only you can convert your EMLX to PNG, but you can read, manipulate, and parse EMLX document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict PNG File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EMLX to PNG. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}