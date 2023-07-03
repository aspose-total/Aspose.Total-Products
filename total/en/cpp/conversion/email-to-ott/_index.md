---
title: Export EMAIL to OTT via C++
description: C++ API to Convert EMAIL to OTT without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/email-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: OTT
otherformats: GIF FLATOPC ODT MD XPS JPEG RTF TIFF DOTX DOCX PCL DOCM TEXT WORDML PNG DOT PDF EPUB DOTM PS BMP EMF DOC SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EMAIL to OTT" h2="Transform EMAIL to OTT within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Email conversion is an important task for C++ developers who need to add email conversion features inside their applications. Email conversion is the process of transforming an email file format into another format, such as HTML. This is useful for a variety of tasks, such as archiving emails, creating backups, and more.

<h2>How Aspose.Total Helps for Email to OTT Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that provides developers with the tools they need to add powerful features to their applications. It includes two APIs that are specifically designed to help with email conversion: Aspose.Email for C++ and Aspose.Words for C++. 

Aspose.Email for C++ is an API that enables developers to convert EMAIL file formats to HTML. This API is easy to use and provides developers with a wide range of features, such as the ability to convert emails to HTML, MHTML, and other formats.

Aspose.Words for C++ is an API that enables developers to export HTML to OTT. This API provides developers with a wide range of features, such as the ability to convert HTML to OTT, DOCX, and other formats.

By using Aspose.Total for C++, developers can easily add powerful email conversion features to their applications. This suite of APIs provides developers with the tools they need to quickly and easily convert emails to HTML and then export HTML to OTT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EMAIL to OTT" %}}
1. Open EMAIL file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EMAIL to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to OTT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Ott as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Ott as save format
doc->Save(u"convertedFile.Ott");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMAIL File via C++" %}}
Not only you can convert your EMAIL to OTT, but you can read, manipulate, and parse EMAIL document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict OTT File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EMAIL to OTT. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Ott");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}