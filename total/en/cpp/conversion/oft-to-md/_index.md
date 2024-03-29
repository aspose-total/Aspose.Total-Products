---
title: Export OFT to MD via C++
description: C++ API to Convert OFT to MD without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-md/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: MD
otherformats: PDF DOTX RTF PNG PCL DOT DOTM EPUB EMF ODT WORDML PS XPS TEXT BMP OTT FLATOPC TIFF DOCM JPEG SVG DOC DOCX GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to MD" h2="Transform OFT to MD within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is a process of transforming emails from one format to another. This process is necessary to ensure that emails are compatible with different email clients and applications.

<h2>How Aspose.Total helps for oft to md conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that helps developers to work with various file formats. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert OFT file format to HTML and then export HTML to MD. 

Aspose.Email for C++ is a powerful API that enables developers to convert emails from one format to another. It supports a wide range of email formats, including OFT, EML, MSG, MHTML, and HTML. With this API, you can easily convert OFT file format to HTML.

Aspose.Words for C++ is a powerful API that enables developers to work with documents in various formats. It supports a wide range of document formats, including DOC, DOCX, ODT, HTML, and MD. With this API, you can easily export HTML to MD.

Both APIs come under Aspose.Total for C++ package. This package provides developers with a comprehensive set of APIs to work with various file formats. It includes APIs for working with emails, documents, images, and other file formats. With this package, developers can easily convert OFT file format to HTML and then export HTML to MD.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to MD" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to MD format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Md as SaveFormat
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
// call save method while passing Md as save format
doc->Save(u"convertedFile.Md");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to MD, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict MD File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to MD. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Md");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}