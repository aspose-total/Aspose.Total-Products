---
title: C++ API to Export PDF to OTT
description: Convert PDF to OTT within C++ applications.
url_ignore: /cpp/conversion/pdf-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: OTT
otherformats: RTF FLATOPC DOT MARKDOWN XAMLFLOW WORDML DOTM PCL PS ODT DOCM MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export PDF to OTT" h2="Render PDF to OTT within C++ applications without requiring any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert PDF to OTT?</h2>

OTT (OpenDocument Text) is an open standard for word processing documents, spreadsheets, presentations, and graphics. It is an XML-based file format that is used for creating and storing documents. OTT is supported by many applications, including Microsoft Office, LibreOffice, OpenOffice, and Google Docs. It is also supported by many mobile devices, making it an ideal format for sharing documents across different platforms.

<h2>How Aspose.Total Helps for PDF to OTT Conversion?</h2>

Aspose.Total for C++ is a comprehensive suite of file format automation libraries that enables C++ developers to easily convert PDF to OTT in two simple steps. Firstly, you can use Aspose.PDF for C++ API to convert PDF file format to DOC. Secondly, by using advanced Word Document Processing API Aspose.Words for C++, you can export DOC to OTT. 

Aspose.PDF for C++ is a powerful PDF manipulation API that enables developers to create, edit, convert, and print PDF documents. It supports a wide range of features, including text extraction, document manipulation, page manipulation, and more. Aspose.Words for C++ is a powerful Word document processing API that enables developers to create, edit, convert, and print Word documents. It supports a wide range of features, including text extraction, document manipulation, page manipulation, and more.

Aspose.Total for C++ is a comprehensive suite of file format automation libraries that enables C++ developers to easily convert PDF to OTT. It provides a simple and efficient way to convert PDF to OTT without any manual intervention. The API is easy to use and provides a wide range of features that make it an ideal choice for developers who need to convert PDF to OTT.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Render PDF to OTT" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to DOC by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) member function
3. Load DOC file by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference of Aspose.Words API
4. Save the document to OTT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Ott
wordDoc->Save(u"output.Ott");  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of PDF Document via C++" %}}
In the process of rendering PDF to OTT, you can open a password protected PDF and also change its password. In order to change the password of a PDF file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict OTT File Editing via C++" %}}
You can also restrict OTT file editing using using [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. API enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) enumeration parameter. The following code example demonstrates how to restrict editing in a document so only editing in form fields is possible.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Ott");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}