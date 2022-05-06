---
title: Convert WORDML to ODP via C++
description: Export WORDML to ODP in your C++ applications without using Microsoft Word of PowerPoint 
url_ignore: /cpp/conversion/wordml-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: ODP   
otherformats: PPT PPTX PPSM POT PPSX POTM POWERPOINT PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Convert WORDML to ODP" h2="Export WORDML to ODP within your C++ applications without using Microsoft Word&reg; or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consists of powerful file automation APIs that allows to automate WORDML to ODP conversion while using two of it's APIs. Load your WORDML using [Aspose.Words for C++](https://products.aspose.com/words/cpp/) and convert it to HTML, then load the HTML via PowerPoint manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) to create a new presentation, and save it as ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="WORDML to ODP Conversion on C++" %}}
1. Open WORDML file using [Document](https://apireference.aspose.com/words/cpp/class/aspose.words.document) class reference
2. Convert WORDML to HTML by using [Save](https://apireference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions) member function
3. Initialize a new [Presentation](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Add an AutoShape in your slide, and add AddTextFrame in it
5. Load the HTML content and write it in your Presentation file
6. Save the document to ODP format using [Save](https://apireference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) method and set Odp as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load WORDML file with an instance of Document
Document document = new Document("template.wordml");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.wordml");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);                  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Load Password Protected WORDML Document via C++" %}}
Apart from document conversion, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API allows tons of document manipulation features for C++ developers. In case your Microsoft Word WORDML file format is password protected, you can still open it using the API. In order to load the encrypted document, you can use a special constructor overload, which accepts a [LoadOptions](https://apireference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object. This object contains the Password property, which specifies the password string.  
{{% blocks/products/pf/feature-page-code %}}
```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.wordml", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Comments in ODP Document via C++" %}}
While saving WORDML as ODP, you can also use [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) to add further features in your ODP document. For instance, you can add comments in your presentation. The presentation slide comment are associated with a particular author. The Presentation class holds the collection of authors in ICommentAuthorCollection that are responsible for adding slide comments. For each author, there is a collection of comments in ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}
```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}