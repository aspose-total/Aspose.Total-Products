---
title: Export EML to XPS via C++
description: C++ API to Convert EML to XPS without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/eml-to-xps/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: XPS
otherformats: DOTM PNG TEXT PDF PCL EMF JPEG PS DOTX FLATOPC OTT EPUB DOT DOCM SVG ODT WORDML GIF RTF MD DOCX BMP TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EML to XPS" h2="Transform EML to XPS within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming emails from one format to another. This process is useful for archiving emails, migrating emails from one platform to another, or for creating backups.

<h2>How Aspose.Total helps for eml to xps conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that can help you with email conversion. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++. Aspose.Email for C++ can be used to convert EML file format to HTML. After that, Aspose.Words for C++ API can be used to export HTML to XPS. Both APIs come under Aspose.Total for C++ package.

Using Aspose.Email for C++, you can easily convert EML to HTML. The API provides a simple and straightforward way to convert emails from EML to HTML format. It also supports various other email formats such as MSG, MHTML, and EMLX. After converting EML to HTML, you can use Aspose.Words for C++ to export HTML to XPS. The API provides a simple and efficient way to convert HTML to XPS. It also supports various other document formats such as DOC, DOCX, and PDF.

Aspose.Total for C++ is a comprehensive suite of APIs that can help you with email conversion. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++. Aspose.Email for C++ can be used to convert EML file format to HTML. After that, Aspose.Words for C++ API can be used to export HTML to XPS. Both APIs come under Aspose.Total for C++ package. With the help of these APIs, you can easily convert emails from EML to XPS format. The APIs provide a simple and straightforward way to convert emails from one format to another. Moreover, they also support various other email and document formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EML to XPS" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to XPS format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Xps as SaveFormat
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
// call save method while passing Xps as save format
doc->Save(u"convertedFile.Xps");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via C++" %}}
Not only you can convert your EML to XPS, but you can read, manipulate, and parse EML document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict XPS File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EML to XPS. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Xps");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}