---
title: Export OFT to DOC via C++
description: C++ API to Convert OFT to DOC without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-doc/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOC
otherformats: XPS PCL DOTM OTT TIFF MD FLATOPC PDF ODT RTF PS TEXT DOCM BMP SVG EPUB DOCX WORDML EMF DOT GIF JPEG PNG DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to DOC" h2="Transform OFT to DOC within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. One of the most common conversions is from OFT file format to HTML. This conversion is necessary for a variety of reasons, such as to make the file easier to view, to make it compatible with other programs, or to make it easier to share with other users.

<h2>How Aspose.Total Helps for OFT to DOC Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that can help you with your email conversion needs. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, that can be used together to convert OFT file format to HTML and then export HTML to DOC. 

Aspose.Email for C++ is a powerful API that can be used to convert OFT files to HTML. It is a feature-rich API that supports a wide range of email file formats, including Outlook MSG, EML, MHTML, and OFT. It also provides a number of features that make it easy to work with email files, such as the ability to read and write email messages, extract attachments, and convert emails to different formats.

Aspose.Words for C++ is a powerful API that can be used to export HTML to DOC. It is a feature-rich API that supports a wide range of document formats, including DOC, DOCX, RTF, and HTML. It also provides a number of features that make it easy to work with documents, such as the ability to create, edit, and convert documents, as well as to insert, delete, and extract text and images.

By using Aspose.Total for C++, you can easily convert OFT file format to HTML and then export HTML to DOC. This makes it easy to add email conversion features to your applications, allowing you to quickly and easily convert emails to different formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to DOC" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOC format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Doc as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to DOC, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict DOC File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to DOC. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}