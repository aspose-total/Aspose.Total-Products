---
title: Export OFT to TIFF via C++
description: C++ API to Convert OFT to TIFF without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-tiff/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: TIFF
otherformats: DOTX DOCX DOTM RTF XPS PDF DOCM EMF PCL DOT PS WORDML GIF JPEG DOC ODT MD TEXT OTT BMP SVG EPUB FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to TIFF" h2="Transform OFT to TIFF within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

Are you a C++ developer looking to add email conversion features to your applications? Aspose.Email for C++ is the perfect solution for you. This API allows you to convert OFT file format to HTML. After that, you can use Aspose.Words for C++ to export HTML to TIFF. Both of these APIs are part of the Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful and feature-rich API that enables you to convert OFT files to HTML. It supports a wide range of file formats, including MSG, EML, MHTML, and more. It also provides advanced features such as email conversion, message extraction, and more. With Aspose.Email for C++, you can easily convert OFT files to HTML with just a few lines of code.

Once you have converted the OFT file to HTML, you can use Aspose.Words for C++ to export the HTML to TIFF. Aspose.Words for C++ is a powerful API that enables you to create, edit, and convert documents in various formats. It supports a wide range of file formats, including DOC, DOCX, ODT, and more. With Aspose.Words for C++, you can easily export HTML to TIFF with just a few lines of code.

Both Aspose.Email for C++ and Aspose.Words for C++ are part of the Aspose.Total for C++ package. Aspose.Total for C++ is a comprehensive suite of APIs that enables you to create, edit, and convert documents in various formats. It includes APIs for email conversion, message extraction, document conversion, and more. With Aspose.Total for C++, you can easily add email conversion features to your applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to TIFF" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to TIFF format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Tiff as SaveFormat
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
// call save method while passing Tiff as save format
doc->Save(u"convertedFile.Tiff");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to TIFF, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict TIFF File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to TIFF. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
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

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}