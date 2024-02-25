---
title: Export MSG to JPEG via C++
description: C++ API to Convert MSG to JPEG without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/msg-to-jpeg/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: JPEG
otherformats: DOCX PS TIFF XPS DOT FLATOPC PDF WORDML ODT DOC DOCM SVG PNG GIF DOTM BMP TEXT RTF MD PCL EPUB DOTX EMF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export MSG to JPEG" h2="Transform MSG to JPEG within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. This could be for a variety of reasons, such as to make the emails easier to read, to make them more accessible, or to make them more compatible with other applications.

<h2>How Aspose.Total Helps for MSG to JPEG Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that can help you to easily add email conversion features to your applications. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert MSG file format to HTML and then export HTML to JPEG. 

Using Aspose.Email for C++, you can easily convert MSG files to HTML. This API provides a wide range of features, such as the ability to read and write MSG files, convert MSG to HTML, and more. It also supports a variety of file formats, including EML, MHTML, and Outlook PST.

Once you have converted the MSG file to HTML, you can use Aspose.Words for C++ to export the HTML to JPEG. This API provides a range of features, such as the ability to read and write a variety of document formats, including DOC, DOCX, RTF, and HTML. It also supports a variety of image formats, including JPEG, PNG, and TIFF.

By using Aspose.Total for C++, you can easily add email conversion features to your applications. It provides two powerful APIs that can be used to convert MSG files to HTML and then export HTML to JPEG. This makes it easy to add email conversion features to your applications, allowing you to quickly and easily add the features you need.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert MSG to JPEG" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert MSG to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to JPEG format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Jpeg as SaveFormat
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
// call save method while passing Jpeg as save format
doc->Save(u"convertedFile.Jpeg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse MSG File via C++" %}}
Not only you can convert your MSG to JPEG, but you can read, manipulate, and parse MSG document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict JPEG File Format Editing" %}}
You can also add document protection features in your app while exporting the document from MSG to JPEG. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Jpeg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}