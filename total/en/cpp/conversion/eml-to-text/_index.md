---
title: Export EML to TEXT via C++
description: C++ API to Convert EML to TEXT without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/eml-to-text/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: TEXT
otherformats: EMF JPEG OTT XPS DOTX PNG BMP SVG EPUB DOT FLATOPC PS GIF MD PCL DOCX DOC ODT PDF TIFF DOTM WORDML RTF DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EML to TEXT" h2="Transform EML to TEXT within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

Are you a C++ developer looking to add email conversion features to your applications? Aspose.Email for C++ is the perfect solution for you. This API allows you to convert EML file format to HTML. After that, you can use Aspose.Words for C++ to export HTML to TEXT. Both of these APIs are part of the Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful API that enables you to easily convert EML file format to HTML. It supports a wide range of features such as email message conversion, email message manipulation, and email message extraction. With this API, you can easily convert EML files to HTML with just a few lines of code.

Aspose.Words for C++ is a powerful API that enables you to export HTML to TEXT. It supports a wide range of features such as document conversion, document manipulation, and document extraction. With this API, you can easily convert HTML to TEXT with just a few lines of code.

Both of these APIs are part of the Aspose.Total for C++ package. This package provides you with a comprehensive set of APIs that enable you to easily add email conversion features to your applications. With this package, you can easily convert EML files to HTML and then export HTML to TEXT with just a few lines of code.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EML to TEXT" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to TEXT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Text as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Text as save format
doc->Save(u"convertedFile.Text");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via C++" %}}
Not only you can convert your EML to TEXT, but you can read, manipulate, and parse EML document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
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
You can also add document protection features in your app while exporting the document from EML to TEXT. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
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