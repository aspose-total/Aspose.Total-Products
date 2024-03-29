---
title: Export OFT to TEXT via C++
description: C++ API to Convert OFT to TEXT without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-text/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: TEXT
otherformats: DOTM MD GIF DOTX RTF JPEG ODT EMF BMP PDF PNG DOT DOCM SVG EPUB WORDML XPS FLATOPC DOCX PCL TIFF PS OTT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to TEXT" h2="Transform OFT to TEXT within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming emails from one format to another. This is necessary to ensure compatibility with different email clients and to make sure that the emails are readable and accessible.

<h2>How Aspose.Total helps for oft to text conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that provides a wide range of features for developers. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert OFT file format to HTML and then export HTML to TEXT. Aspose.Email for C++ provides a set of classes for working with email messages, attachments, and folders. It also supports various email formats such as MSG, EML, MHTML, and OFT. Aspose.Words for C++ is a powerful word processing API that enables developers to create, edit, and convert documents in various formats. It supports HTML, DOC, DOCX, RTF, and other popular formats.

Using these two APIs, developers can easily convert OFT file format to HTML and then export HTML to TEXT. This process is simple and straightforward, and it can be done in a few steps. First, the OFT file is converted to HTML using Aspose.Email for C++. Then, the HTML is exported to TEXT using Aspose.Words for C++. Both APIs are available in the Aspose.Total for C++ package, which makes it easy for developers to access and use them.

Aspose.Total for C++ is a great tool for developers who need to add email conversion features to their applications. It provides a comprehensive suite of APIs that can be used to convert OFT file format to HTML and then export HTML to TEXT. This makes it easy for developers to add email conversion features to their applications and ensure compatibility with different email clients.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to TEXT" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to TEXT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Text as SaveFormat
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
// call save method while passing Text as save format
doc->Save(u"convertedFile.Text");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to TEXT, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict TEXT File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to TEXT. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Text");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}