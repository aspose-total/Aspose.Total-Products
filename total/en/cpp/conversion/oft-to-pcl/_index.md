---
title: Export OFT to PCL via C++
description: C++ API to Convert OFT to PCL without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-pcl/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PCL
otherformats: DOTX SVG WORDML ODT TEXT PDF DOTM RTF XPS DOCM BMP OTT TIFF JPEG DOT FLATOPC PNG EPUB DOC GIF PS EMF MD DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to PCL" h2="Transform OFT to PCL within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

C++ developers often need to add email conversion features to their applications. This may involve converting OFT file format to HTML, and then exporting HTML to PCL.

<h2>How Aspose.Total Helps for OFT to PCL Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that provides developers with the tools they need to add powerful file format conversion features to their applications. It includes Aspose.Email for C++ and Aspose.Words for C++, two APIs that are specifically designed to help with OFT to PCL conversion.

Aspose.Email for C++ is an API that enables developers to convert OFT files to HTML. It supports a wide range of file formats, including Outlook MSG, EML, MHTML, and OFT. It also provides a range of features, such as the ability to read and write email messages, and to convert emails to different formats.

Aspose.Words for C++ is an API that enables developers to export HTML to PCL. It supports a wide range of file formats, including DOC, DOCX, RTF, HTML, and PCL. It also provides a range of features, such as the ability to create, edit, and convert documents, and to manipulate document elements.

By combining Aspose.Email for C++ and Aspose.Words for C++, developers can easily convert OFT files to HTML, and then export HTML to PCL. This makes it easy to add powerful email conversion features to their applications.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to PCL" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to PCL format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Pcl as SaveFormat
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
// call save method while passing Pcl as save format
doc->Save(u"convertedFile.Pcl");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to PCL, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict PCL File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to PCL. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Pcl");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}