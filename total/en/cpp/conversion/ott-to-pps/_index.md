---
title: Convert OTT to PPS via C++ or with free Online Converter
description: Export OTT to PPS in your C++ applications without using Microsoft Word of PowerPoint or online. Test free OTT to PPS online converter quickly before integrating the code. 
url_ignore: /cpp/conversion/ott-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: OTT
outformat: PPS   
otherformats: POTX POT PPTM PPSX PPTX PPSM PPT ODP POTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API to Convert OTT to PPS or Online App" h2="Export OTT to PPS within your C++ applications without using Microsoft Word&reg; or PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}


<h2>Why to Convert</h2>
OTT (OpenDocument Text) is a file format used for documents created by OpenOffice or LibreOffice. It is an open standard for office documents, and is used by many organizations and individuals. PPS (PowerPoint Show) is a file format used by Microsoft PowerPoint to store presentations. It is a proprietary format, and is used by many organizations and individuals. Converting OTT to PPS allows users to view and edit their documents in the PowerPoint format.

<h2>How Aspose.Total helps for ott to pps conversion</h2>
Aspose.Total for C++ is a powerful suite of file automation APIs that allows users to automate the conversion of OTT to PPS. It consists of two APIs: Aspose.Words for C++ and Aspose.Slides for C++. Aspose.Words for C++ can be used to load an OTT file and convert it to HTML. Aspose.Slides for C++ can then be used to load the HTML and create a new presentation in the PPS format. This process allows users to quickly and easily convert their OTT documents to the PPS format.

{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OTT to PPS Conversion on C++" %}}
1. Open OTT file using [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class reference
2. Convert OTT to HTML by using [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions) member function
3. Initialize a new [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) object
4. Add an AutoShape in your slide, and add AddTextFrame in it
5. Load the HTML content and write it in your Presentation file
6. Save the document to PPS format using [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) method and set Pps as SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ File Format APIs" %}}
Install from command line as ```nuget install Aspose.Total.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
```cpp
// load OTT file with an instance of Document
Document document = new Document("template.ott");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.ott");
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Free Online Converter for OTT to PPS</h3>

<iframe title="Free ott to pps Conversion Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Load Password Protected OTT Document via C++" %}}
Apart from document conversion, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API allows tons of document manipulation features for C++ developers. In case your Microsoft Word OTT file format is password protected, you can still open it using the API. In order to load the encrypted document, you can use a special constructor overload, which accepts a [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) object. This object contains the Password property, which specifies the password string.  
{{% blocks/products/pf/feature-page-code %}}
```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.ott", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Add Comments in PPS Document via C++" %}}
While saving OTT as PPS, you can also use [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) to add further features in your PPS document. For instance, you can add comments in your presentation. The presentation slide comment are associated with a particular author. The Presentation class holds the collection of authors in ICommentAuthorCollection that are responsible for adding slide comments. For each author, there is a collection of comments in ICommentCollection.
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
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>FAQ</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>How can I convert OTT to PPS Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">You can find the online app for OTT conversion above. To start the conversion process, you can add the OTT file either by dragging and dropping it or by clicking inside the white area to import the document. Once you have added the file, you can simply click the "Convert" button. After the OTT to PPS conversion is completed, you can download your converted file with just one click.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>How long does it take to convert OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">The speed of this online converter depends largely on the size of the OTT file being converted. Small OTT files can be converted to PPS in just a few seconds. If you are using the conversion code within a C++ application, the conversion speed will depend on how well you have optimized your application.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Is it safe to convert OTT to PPS using free Aspose.Total converter?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Of course! After your OTT file is converted to PPS using our online converter, the download link for the PPS file will be immediately available. We take the security and privacy of your uploaded files seriously and delete them 24 hours after the conversion process is complete. Rest assured, no one will have access to your files. Our conversion process, including OTT conversion, is completely safe. We provide a free app for testing purposes so that you can verify the results before integrating the code.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>What browser should I use to convert OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">For online OTT conversion, you can use any modern browser, such as Google Chrome, Firefox, Opera, or Safari. However, if you're developing a desktop application, Aspose.Total OTT Conversion API is recommended for smooth performance.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}