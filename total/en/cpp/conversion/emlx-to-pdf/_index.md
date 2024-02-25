---
title: Export EMLX to PDF via C++
description: C++ API to Convert EMLX to PDF without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/emlx-to-pdf/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: PDF
otherformats: TIFF DOCX FLATOPC EPUB DOT RTF EMF DOTX DOTM XPS GIF PNG PS OTT WORDML ODT DOCM BMP MD TEXT PCL SVG DOC JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EMLX to PDF" h2="Transform EMLX to PDF within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming emails from one format to another. This process is necessary to make emails compatible with different email clients and applications.

<h2>How Aspose.Total helps for emlx to pdf conversion</h2>

Aspose.Total for C++ is a comprehensive package of APIs that provides developers with the tools to create, manipulate, and convert documents, images, and emails. It includes Aspose.Email for C++ and Aspose.Words for C++.

Using Aspose.Email for C++, you can convert EMLX file format to HTML. After that, by using Aspose.Words for C++ API, you can export HTML to PDF. Both APIs come under Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful email processing API that enables developers to create, read, and manipulate emails in various formats. It supports a wide range of email formats, including EMLX, MSG, EML, MHTML, and HTML. It also provides features to convert emails from one format to another.

Aspose.Words for C++ is a powerful document processing API that enables developers to create, read, and manipulate documents in various formats. It supports a wide range of document formats, including DOC, DOCX, ODT, RTF, HTML, and PDF. It also provides features to convert documents from one format to another.

By combining the features of Aspose.Email for C++ and Aspose.Words for C++, you can easily convert EMLX file format to PDF. This makes Aspose.Total for C++ a great choice for developers who need to add email conversion features inside their applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EMLX to PDF" %}}
1. Open EMLX file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EMLX to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to PDF format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Pdf as SaveFormat
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
// call save method while passing Pdf as save format
doc->Save(u"convertedFile.Pdf");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMLX File via C++" %}}
Not only you can convert your EMLX to PDF, but you can read, manipulate, and parse EMLX document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict PDF File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EMLX to PDF. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Pdf");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}