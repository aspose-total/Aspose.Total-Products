---
title: C++ API to Export XPS to MHTML
description: Convert XPS to MHTML within C++ applications.
url_ignore: /cpp/conversion/xps-to-mhtml/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: MHTML
otherformats: DOTM XAMLFLOW DOT RTF MARKDOWN OTT WORDML DOTX FLATOPC PS ODT PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Export XPS to MHTML" h2="Render XPS to MHTML within C++ applications without requiring any third party application" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert XPS to MHTML?</h2>

XPS (XML Paper Specification) is a document format developed by Microsoft that is used to store documents in a fixed layout. It is similar to PDF, but is not as widely used. MHTML (MIME HTML) is a web page archive format used to save web pages for offline viewing. It is a combination of HTML code and resources such as images, audio, and video. Converting XPS to MHTML allows users to view the documents offline, and also to share them with others.

<h2>How Aspose.Total Helps for XPS to MHTML Conversion?</h2>

Aspose.Total for C++ is a suite of file format automation libraries that enables C++ developers to easily convert XPS to MHTML in two simple steps. Firstly, the Aspose.PDF for C++ API can be used to convert XPS file format to DOC. Secondly, the advanced Word Document Processing API Aspose.Words for C++ can be used to export DOC to MHTML. This makes it easy for developers to quickly and easily convert XPS to MHTML without having to write complex code. Aspose.Total for C++ also provides a range of other features such as document manipulation, conversion, and rendering. It is a comprehensive suite of libraries that makes it easy for developers to work with a variety of file formats.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API to Render XPS to MHTML" %}}
1. Open XPS file using [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) class reference
2. Convert XPS to DOC by using [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) member function
3. Load DOC file by using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference of Aspose.Words API
4. Save the document to MHTML format using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) member function
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Automation APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load XPS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.xps");
// save XPS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Mhtml
wordDoc->Save(u"output.Mhtml");  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Change Password of XPS Document via C++" %}}
In the process of rendering XPS to MHTML, you can open a password protected XPS and also change its password. In order to change the password of a XPS file, you must know the owner password of that document. You can load password protected PDF document with [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) by specifying its owner password and use ChangePasswords method to change the password.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restrict MHTML File Editing via C++" %}}
You can also restrict MHTML file editing using using [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API. Sometimes you may need to limit the ability to edit a document and only allow certain actions with it. API enables you to control the way you restrict the content using the [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) enumeration parameter. The following code example demonstrates how to restrict editing in a document so only editing in form fields is possible.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Mhtml");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}