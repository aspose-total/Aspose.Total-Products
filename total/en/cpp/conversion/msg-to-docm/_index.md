---
title: Export MSG to DOCM via C++
description: C++ API to Convert MSG to DOCM without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/msg-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOCM
otherformats: RTF GIF DOC TEXT OTT JPEG MD DOTM XPS PNG EPUB PS PDF PCL BMP WORDML DOCX DOTX SVG EMF TIFF DOT ODT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export MSG to DOCM" h2="Transform MSG to DOCM within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Email conversion is an important task for C++ developers. It allows them to add features to their applications that can convert emails from one format to another. This is especially useful when the emails need to be converted to a format that can be used in other applications.

<h2>How Aspose.Total Helps for MSG to DOCM Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that can help C++ developers to easily convert emails from one format to another. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert MSG file format to HTML and then export HTML to DOCM.

Aspose.Email for C++ is a powerful API that can be used to convert MSG files to HTML. It supports a wide range of features such as reading and writing MSG files, converting MSG files to HTML, and more. It also supports a variety of email formats such as Outlook, Exchange, and Office 365.

Aspose.Words for C++ is a powerful API that can be used to export HTML to DOCM. It supports a wide range of features such as reading and writing DOCM files, converting HTML to DOCM, and more. It also supports a variety of document formats such as Word, PDF, and HTML.

By using Aspose.Total for C++, C++ developers can easily convert MSG files to HTML and then export HTML to DOCM. This makes it easy for them to add email conversion features to their applications. Moreover, Aspose.Total for C++ also provides a wide range of other features such as document conversion, document manipulation, and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert MSG to DOCM" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert MSG to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOCM format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Docm as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docm as save format
doc->Save(u"convertedFile.Docm");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse MSG File via C++" %}}
Not only you can convert your MSG to DOCM, but you can read, manipulate, and parse MSG document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict DOCM File Format Editing" %}}
You can also add document protection features in your app while exporting the document from MSG to DOCM. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docm");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}