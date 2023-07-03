---
title: Export EML to EPUB via C++
description: C++ API to Convert EML to EPUB without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/eml-to-epub/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOT WORDML GIF DOTX DOCM BMP TEXT XPS PNG PDF MD DOTM PCL EMF RTF OTT TIFF JPEG SVG DOC ODT DOCX PS FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EML to EPUB" h2="Transform EML to EPUB within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is the process of transforming emails from one format to another. This is often done to make the emails more accessible, or to make them compatible with other applications.

<h2>How Aspose.Total Helps for EML to EPUB Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that enables developers to create, manipulate, and convert a wide range of file formats. It includes two APIs that are particularly useful for email conversion: Aspose.Email for C++ and Aspose.Words for C++.

Using Aspose.Email for C++, you can convert EML file format to HTML. After that, by using Aspose.Words for C++ API, you can export HTML to EPUB. Both APIs come under Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful email processing API that enables developers to create, read, and manipulate emails in a variety of formats. It supports a wide range of email formats, including EML, MSG, MHTML, and more. It also provides features for managing attachments, extracting email headers, and more.

Aspose.Words for C++ is a powerful document processing API that enables developers to create, read, and manipulate documents in a variety of formats. It supports a wide range of document formats, including DOC, DOCX, HTML, PDF, and more. It also provides features for managing document elements, extracting text, and more.

By combining the features of Aspose.Email for C++ and Aspose.Words for C++, you can easily convert emails from one format to another. This makes it easy to add email conversion features to your applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EML to EPUB" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to EPUB format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Epub as SaveFormat
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
// call save method while passing Epub as save format
doc->Save(u"convertedFile.Epub");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via C++" %}}
Not only you can convert your EML to EPUB, but you can read, manipulate, and parse EML document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict EPUB File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EML to EPUB. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Epub");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}