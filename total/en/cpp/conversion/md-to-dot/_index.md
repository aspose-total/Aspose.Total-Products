---
title: C++ API to Export MD to DOT
description: Convert MD to DOT within C++ applications.
url_ignore: /cpp/conversion/md-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: MD
outformat: DOT
otherformats: PCL MARKDOWN XAMLFLOW MHTML OTT ODT WORDML PS DOTX DOTM DOCM FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export MD to DOT" h2="Render MD to DOT within C++ applications without requiring any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert MD to DOT?</h2>

Converting MD to DOT is a useful process for C++ developers who need to automate the conversion of file formats. MD is a markdown language used to create documents with plain text formatting, while DOT is a graph description language used to create diagrams. Converting MD to DOT allows developers to create diagrams from markdown documents, making it easier to visualize and share data.

<h2>How Aspose.Total Helps for MD to DOT Conversion?</h2>

Aspose.Total for C++ is a file format automation library that makes it easy for C++ developers to convert MD to DOT. The library consists of two components: Aspose.PDF for C++ and Aspose.Words for C++. Aspose.PDF for C++ is used to convert MD files to DOC, while Aspose.Words for C++ is used to export DOC to DOT. This two-step process makes it easy to convert MD to DOT quickly and accurately. Aspose.Total for C++ also offers a range of other features, such as the ability to create, edit, and convert PDF files, as well as the ability to manipulate Word documents.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Render MD to DOT" %}}
1. Open MD file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert MD to DOC by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) member function
3. Load DOC file by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference of Aspose.Words API
4. Save the document to DOT format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load MD file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.md");
// save MD as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dot
wordDoc->Save(u"output.Dot");  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of MD Document via C++" %}}
In the process of rendering MD to DOT, you can open a password protected MD and also change its password. In order to change the password of a MD file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing MD Document
auto doc = MakeObject<Document>(L"input.md", L"owner");
// change password of MD Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict DOT File Editing via C++" %}}
You can also restrict DOT file editing using using [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. API enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) enumeration parameter. The following code example demonstrates how to restrict editing in a document so only editing in form fields is possible.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dot");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}