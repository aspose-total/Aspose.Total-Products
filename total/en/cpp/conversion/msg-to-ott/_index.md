---
title: Export MSG to OTT via C++
description: C++ API to Convert MSG to OTT without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/msg-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: OTT
otherformats: DOTM DOC PNG SVG PS TEXT BMP RTF DOTX EMF MD GIF FLATOPC XPS DOT DOCX EPUB ODT WORDML PDF PCL TIFF DOCM JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export MSG to OTT" h2="Transform MSG to OTT within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is the process of converting emails from one format to another. This is done to make the emails compatible with different email clients and applications.

<h2>How Aspose.Total helps for MSG to OTT Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for manipulating emails, documents, images, and other file formats. Using Aspose.Email for C++, you can convert MSG file format to HTML. After that, by using Aspose.Words for C++ API, you can export HTML to OTT. Both APIs come under Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful API that enables developers to create, read, and manipulate emails in various formats. It supports a wide range of email formats such as MSG, EML, MHTML, and more. It also provides features to convert emails from one format to another. Using this API, you can easily convert MSG file format to HTML.

Aspose.Words for C++ is a powerful API that enables developers to create, read, and manipulate documents in various formats. It supports a wide range of document formats such as DOC, DOCX, ODT, and more. It also provides features to convert documents from one format to another. Using this API, you can easily export HTML to OTT.

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, and convert various file formats. It includes APIs for manipulating emails, documents, images, and other file formats. Using Aspose.Total for C++, you can easily convert MSG file format to HTML and then export HTML to OTT. It is a cost-effective solution that helps developers save time and effort.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert MSG to OTT" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert MSG to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to OTT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Ott as SaveFormat
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
// call save method while passing Ott as save format
doc->Save(u"convertedFile.Ott");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse MSG File via C++" %}}
Not only you can convert your MSG to OTT, but you can read, manipulate, and parse MSG document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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
You can also add document protection features in your app while exporting the document from MSG to OTT. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
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