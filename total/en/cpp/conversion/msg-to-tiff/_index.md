---
title: Export MSG to TIFF via C++
description: C++ API to Convert MSG to TIFF without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/msg-to-tiff/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: TIFF
otherformats: EMF TEXT JPEG FLATOPC PS MD DOCM XPS GIF PDF RTF EPUB SVG DOT DOTM WORDML DOC PCL OTT BMP DOCX PNG DOTX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export MSG to TIFF" h2="Transform MSG to TIFF within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Email conversion is an important task for C++ developers. It helps to add features to applications and make them more user-friendly. Converting MSG file format to HTML is one of the most popular email conversion tasks. It helps to view emails in a web browser and also makes it easier to share emails with other users.

<h2>How Aspose.Total Helps for MSG to TIFF Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that helps developers to add features to their applications. It includes two APIs, Aspose.Email for C++ and Aspose.Words for C++, which can be used to convert MSG file format to HTML and then export HTML to TIFF. Aspose.Email for C++ API helps to convert MSG file format to HTML. It supports a wide range of features such as reading, writing, and manipulating MSG files. It also supports various email clients such as Microsoft Outlook, Exchange Server, and Office 365. Aspose.Words for C++ API helps to export HTML to TIFF. It supports a wide range of features such as creating, editing, and converting documents. It also supports various document formats such as DOC, DOCX, HTML, and PDF. 

Using Aspose.Total for C++, developers can easily convert MSG file format to HTML and then export HTML to TIFF. It helps to add features to applications and make them more user-friendly. Moreover, it helps to save time and effort as developers don’t have to write code for each task. Aspose.Total for C++ is a comprehensive suite of APIs that helps developers to add features to their applications quickly and easily.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert MSG to TIFF" %}}
1. Open MSG file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert MSG to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to TIFF format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Tiff as SaveFormat
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
// call save method while passing Tiff as save format
doc->Save(u"convertedFile.Tiff");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse MSG File via C++" %}}
Not only you can convert your MSG to TIFF, but you can read, manipulate, and parse MSG document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict TIFF File Format Editing" %}}
You can also add document protection features in your app while exporting the document from MSG to TIFF. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Tiff");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}