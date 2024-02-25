---
title: Export OFT to SVG via C++
description: C++ API to Convert OFT to SVG without using Microsoft Word or Outlook
url_ignore: /cpp/conversion/oft-to-svg/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: SVG
otherformats: DOCM TIFF PCL OTT WORDML EMF FLATOPC ODT PDF BMP DOTM XPS JPEG GIF DOTX DOCX RTF EPUB DOT PNG MD DOC TEXT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export OFT to SVG" h2="Transform OFT to SVG within C++ application without requiring Microsoft Word or Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}

Are you a C++ developer looking to add email conversion features to your applications? Aspose.Email for C++ is the perfect solution for you. This API allows you to convert OFT file format to HTML. After that, you can use Aspose.Words for C++ to export HTML to SVG. Both of these APIs are included in the Aspose.Total for C++ package.

Aspose.Email for C++ is a powerful API that enables you to convert OFT file format to HTML. It is easy to use and provides a wide range of features. It supports a variety of file formats, including MSG, EML, MHTML, and HTML. It also provides features such as email attachment extraction, email address extraction, and email header manipulation.

Aspose.Words for C++ is a powerful API that enables you to export HTML to SVG. It is easy to use and provides a wide range of features. It supports a variety of file formats, including DOC, DOCX, RTF, HTML, and PDF. It also provides features such as document conversion, document manipulation, and document comparison.

Aspose.Total for C++ is a comprehensive package that includes both Aspose.Email for C++ and Aspose.Words for C++. It is a cost-effective solution that provides all the features of both APIs in one package. It is easy to use and provides a wide range of features. It supports a variety of file formats, including MSG, EML, MHTML, HTML, DOC, DOCX, RTF, and PDF. It also provides features such as email attachment extraction, email address extraction, email header manipulation, document conversion, document manipulation, and document comparison.

With Aspose.Total for C++, you can easily add email conversion features to your applications. It is a cost-effective solution that provides all the features of both Aspose.Email for C++ and Aspose.Words for C++ in one package. It is easy to use and provides a wide range of features. It supports a variety of file formats, including MSG, EML, MHTML, HTML, DOC, DOCX, RTF, and PDF. It also provides features such as email attachment extraction, email address extraction, email header manipulation, document conversion, document manipulation, and document comparison.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Convert OFT to SVG" %}}
1. Open OFT file using [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) class reference
2. Convert OFT to HTML by using [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) member function 
3. Load HTML by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class 
4. Save the document to SVG format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) method and set Svg as SaveFormat
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
// call save method while passing Svg as save format
doc->Save(u"convertedFile.Svg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Parse OFT File via C++" %}}
Not only you can convert your OFT to SVG, but you can read, manipulate, and parse OFT document. You can get subject, address, body, recipients information of the email by using MapiMessage class of [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API.  For example, you can check for a specific sender email for the conversion by using get_SenderEmailAddress() property. 
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

{{% blocks/products/pf/feature-page-section  h2="C++ API to Restrict SVG File Format Editing" %}}
You can also add document protection features in your app while exporting the document from OFT to SVG. Adding protection to your document is a simple process, as all you need to do is apply the protection method to your document. You can set protection type to ReadOnly to restrict the user to edit the document.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Svg");
```
{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}