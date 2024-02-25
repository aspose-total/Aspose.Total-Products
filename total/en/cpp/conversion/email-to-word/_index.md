---
title: Export EMAIL to WORD via C++
description: C++ API to Convert EMAIL to WORD without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/email-to-word/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOCX
otherformats: EMF TIFF SVG DOCX DOTM MD XPS BMP FLATOPC PNG PDF WORDML OTT DOT RTF DOCM TEXT DOTX PCL DOC ODT EPUB GIF JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EMAIL to WORD" h2="Transform EMAIL to WORD within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming an email file format to another format. For example, you may need to convert an EMAIL file format to HTML.

<h2>How Aspose.Total helps for email to word conversion</h2>

Aspose.Total for C++ is a comprehensive package of APIs that helps developers to work with various file formats. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert EMAIL file format to HTML and then export HTML to WORD. Aspose.Email for C++ API provides the capability to convert EMAIL file format to HTML. It supports various email file formats such as MSG, EML, EMLX, MHTML, and Outlook PST. Aspose.Words for C++ API provides the capability to export HTML to WORD. It supports various document file formats such as DOC, DOCX, ODT, RTF, and HTML.

Using Aspose.Total for C++ package, you can easily convert EMAIL file format to HTML and then export HTML to WORD. It is a simple and efficient way to add email conversion features inside your applications. Moreover, Aspose.Total for C++ package also provides other APIs to work with various file formats such as PDF, Excel, PowerPoint, and Barcode.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EMAIL to WORD" %}}
1. Open EMAIL file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EMAIL to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOCX format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Docx as SaveFormat
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
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMAIL File via C++" %}}
Not only you can convert your EMAIL to WORD, but you can read, manipulate, and parse EMAIL document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict WORD File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EMAIL to WORD. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}