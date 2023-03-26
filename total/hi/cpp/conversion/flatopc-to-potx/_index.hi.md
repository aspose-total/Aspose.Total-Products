---
title: FLATOPC को C++ के माध्यम से POTX में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: PowerPoint के Microsoft Word का उपयोग किए बिना अपने C++ अनुप्रयोगों में FLATOPC को POTX में निर्यात करें या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।

family: total
platformtag: cpp
feature: conversion
informat: FLATOPC
outformat: POTX
otherformats: POTM PPSM POWERPOINT PPSX ODP PPTX PPTM POT PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="FLATOPC को POTX में बदलने के लिए C++ API या ऑनलाइन ऐप" h2="Microsoft Word का उपयोग किए बिना अपने C++ अनुप्रयोगों में FLATOPC को POTX में निर्यात करें&reg; या पावरपॉइंट" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) में शक्तिशाली फ़ाइल ऑटोमेशन API शामिल हैं जो अपने दो API का उपयोग करते हुए FLATOPC से POTX रूपांतरण को स्वचालित करने की अनुमति देता है। [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके अपना FLATOPC लोड करें और इसे HTML में बदलें, फिर HTML को PowerPoint मैनिपुलेशन C++ API [Aspose.Slides for C++] के माध्यम से लोड करें। https://products.aspose.com/slides/cpp/) एक नई प्रस्तुति बनाने के लिए, और इसे POTX के रूप में सहेजें। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी++ पर डीओसी से ओडीपी रूपांतरण" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument) वर्ग संदर्भ का उपयोग करके FLATOPC फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_stdbasicostream_saveoptions) सदस्य फ़ंक्शन का उपयोग करके FLATOPC को HTML में बदलें
3. एक नया [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)  शुरू करें वस्तु
4. अपनी स्लाइड में एक ऑटोशेप जोड़ें, और उसमें AddTextFrame जोड़ें
5. HTML सामग्री लोड करें और इसे अपनी प्रस्तुति फ़ाइल में लिखें
6. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) विधि का उपयोग करके दस्तावेज़ को POTX प्रारूप में सहेजें और POTX को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load FLATOPC file with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("template.flatopc");
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"sourceFile.flatopc");
// save the flatopcument in HTML file format
flatopc->Save(u"HtmlOutput.HTML");
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>बीएमपी से जीआईएफ के लिए मुफ्त ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=flatopc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से पासवर्ड संरक्षित FLATOPC दस्तावेज़ लोड करें" %}}
दस्तावेज़ रूपांतरण के अलावा, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API, C++ डेवलपर्स के लिए कई दस्तावेज़ हेरफेर सुविधाओं की अनुमति देता है। यदि आपका Microsoft Word FLATOPC फ़ाइल स्वरूप पासवर्ड से सुरक्षित है, तब भी आप इसे API का उपयोग करके खोल सकते हैं। एन्क्रिप्ट किए गए दस्तावेज़ को लोड करने के लिए, आप एक विशेष कंस्ट्रक्टर ओवरलोड का उपयोग कर सकते हैं, जो एक [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) ऑब्जेक्ट को स्वीकार करता है। इस ऑब्जेक्ट में पासवर्ड गुण है, जो पासवर्ड स्ट्रिंग को निर्दिष्ट करता है।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected flatopcument, the password is passed to the flatopcument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"flatopcPassword");
// load the flatopcument from the local file system by filename:
SharedPtr<Flatopcument> flatopc = MakeObject<Flatopcument>(u"Encrypted.flatopc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से POTX दस्तावेज़ में टिप्पणियाँ जोड़ें" %}}
FLATOPC को POTX के रूप में सहेजते समय, आप अपने POTX दस्तावेज़ में और सुविधाएँ जोड़ने के लिए [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) का भी उपयोग कर सकते हैं। उदाहरण के लिए, आप अपनी प्रस्तुति में टिप्पणियाँ जोड़ सकते हैं। प्रेजेंटेशन स्लाइड कमेंट किसी खास लेखक से जुड़ा होता है। प्रस्तुति वर्ग ICommentAuthorCollection में लेखकों का संग्रह रखता है जो स्लाइड टिप्पणियों को जोड़ने के लिए जिम्मेदार हैं। प्रत्येक लेखक के लिए, ICommentCollection में टिप्पणियों का एक संग्रह है।
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}