---
title: Export EML to DOCX via C++
description: C++ API to Convert EML to DOCX without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/eml-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: DOCX
otherformats: TEXT WORDML PDF SVG ODT DOTM DOT MD XPS TIFF DOCM JPEG PNG PS BMP GIF PCL RTF EPUB OTT EMF FLATOPC DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export EML to DOCX" h2="Transform EML to DOCX within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

As a C++ developer, you may need to add email conversion features inside your applications. Email conversion is the process of changing the format of an email message from one type to another. For example, you may need to convert an email message from EML to HTML or from HTML to DOCX.

<h2>How Aspose.Total Helps for EML to DOCX Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of APIs that provides developers with the tools they need to create, manipulate, and convert documents. It includes two APIs that are specifically designed to help with email conversion: Aspose.Email for C++ and Aspose.Words for C++.

Using Aspose.Email for C++, you can convert an EML file format to HTML. After that, you can use Aspose.Words for C++ to export the HTML to DOCX. Both APIs come under the Aspose.Total for C++ package, so you don't need to purchase them separately.

Aspose.Total for C++ also includes other APIs that can help you with document conversion, such as Aspose.PDF for C++, Aspose.Cells for C++, and Aspose.Slides for C++. With these APIs, you can convert documents from one format to another, such as from PDF to DOCX, from XLSX to HTML, and from PPTX to JPG.

In addition to document conversion, Aspose.Total for C++ also provides APIs for creating, manipulating, and converting images, emails, and barcodes. With these APIs, you can create images from scratch, manipulate existing images, convert images from one format to another, create and send emails, and generate and read barcodes.

Aspose.Total for C++ is a comprehensive suite of APIs that provides developers with the tools they need to create, manipulate, and convert documents. It includes APIs specifically designed to help with email conversion, as well as APIs for creating, manipulating, and converting images, emails, and barcodes. With Aspose.Total for C++, you can easily convert EML to HTML and then export the HTML to DOCX.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert EML to DOCX" %}}
1. Open EML file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert EML to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to DOCX format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Docx as SaveFormat
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
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse EML File via C++" %}}
Not only you can convert your EML to DOCX, but you can read, manipulate, and parse EML document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict DOCX File Format Editing" %}}
You can also add document protection features in your app while exporting the document from EML to DOCX. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
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