---
title: Export EMAIL to PDF via C++
description: C++ API to Convert EMAIL to PDF without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/email-to-pdf/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOCX TIFF DOTM PNG MD SVG GIF DOTX OTT PCL PS FLATOPC EMF EPUB TEXT DOT DOC RTF DOCM ODT XPS JPEG WORDML BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EMAIL to PDF" h2="Transform EMAIL to PDF within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming an email file format into another format. This process is useful for archiving emails, creating backups, or for other purposes.

<h2>How Aspose.Total Helps for Email to PDF Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that provides developers with the ability to create, manipulate, and convert various file formats. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert an EMAIL file format to HTML and then export HTML to PDF. 

Aspose.Email for C++ is a powerful API that enables developers to read, write, and convert email file formats such as MSG, EML, EMLX, MHTML, and MBOX. It also provides features to manipulate email messages, such as adding attachments, setting headers, and adding recipients.

Aspose.Words for C++ is a powerful API that enables developers to create, manipulate, and convert various document formats such as DOC, DOCX, ODT, HTML, and PDF. It also provides features to manipulate documents, such as adding images, text, and tables.

Using Aspose.Total for C++, developers can easily convert an EMAIL file format to HTML and then export HTML to PDF. This makes it easy to add email conversion features to C++ applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EMAIL to PDF" %}}
1. Open EMAIL file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EMAIL to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to PDF format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Pdf as SaveFormat
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
// call save method while passing Pdf as save format
doc->Save(u"convertedFile.Pdf");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EMAIL File via C++" %}}
Not only you can convert your EMAIL to PDF, but you can read, manipulate, and parse EMAIL document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict PDF File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EMAIL to PDF. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
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