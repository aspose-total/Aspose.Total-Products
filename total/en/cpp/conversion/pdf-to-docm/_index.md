---
title: C++ API to Export PDF to DOCM
description: Convert PDF to DOCM within C++ applications.
url_ignore: /cpp/conversion/pdf-to-docm/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: DOCM
otherformats: OTT MARKDOWN FLATOPC DOTM WORDML DOTX MHTML XAMLFLOW RTF PCL ODT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export PDF to DOCM" h2="Render PDF to DOCM within C++ applications without requiring any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>

Converting PDF to DOCM is a common requirement for many C++ developers. DOCM is a Microsoft Word Open XML Macro-Enabled Document file format which is used to store documents with macros. It is a combination of XML and binary files which makes it more secure than other document formats. It is also used to store documents with embedded objects, such as charts, diagrams, and images.

<h2>How Aspose.Total Helps for PDF to DOCM Conversion</h2>

Aspose.Total for C++ is a comprehensive suite of file format automation libraries which allows C++ developers to easily convert PDF to DOCM in two simple steps. Firstly, you can use Aspose.PDF for C++ API to convert PDF file format to DOC. Secondly, by using advanced Word Document Processing API Aspose.Words for C++, you can export DOC to DOCM. 

Aspose.PDF for C++ is a powerful PDF manipulation API which enables developers to create, edit, convert, and print PDF documents from within their own applications. It also allows developers to extract text, images, and other content from PDF documents. Aspose.Words for C++ is a powerful Word document processing API which enables developers to create, edit, and convert Word documents from within their own applications. It also allows developers to extract text, images, and other content from Word documents.

Aspose.Total for C++ is a comprehensive suite of file format automation libraries which makes it easy for C++ developers to convert PDF to DOCM. It provides a simple and efficient way to convert PDF to DOCM without any manual intervention. Aspose.Total for C++ is a reliable and cost-effective solution for C++ developers who need to convert PDF to DOCM.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Render PDF to DOCM" %}}
1. Open PDF file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert PDF to DOC by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) member function
3. Load DOC file by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference of Aspose.Words API
4. Save the document to DOCM format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) member function
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
// save document as Docm
wordDoc->Save(u"output.Docm");  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of PDF Document via C++" %}}
In the process of rendering PDF to DOCM, you can open a password protected PDF and also change its password. In order to change the password of a PDF file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
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

{{% blocks/products/pf/feature-page-section  h2="Restrict DOCM File Editing via C++" %}}
You can also restrict DOCM file editing using using [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. API enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) enumeration parameter. The following code example demonstrates how to restrict editing in a document so only editing in form fields is possible.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Docm");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}