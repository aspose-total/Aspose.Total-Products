---
title: सीजीएम को ओडीपी में बदलने के लिए सी++ एपीआई
description: माइक्रोसॉफ्ट वर्ड या एडोब एक्रोबेट रीडर का उपयोग किए बिना सीजीएम को सी ++ के माध्यम से ओडीपी में कनवर्ट करें

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: POT
otherformats: POWERPOINT ODP XAML OTP PPSM POTX PPTM POTM PPT PPS SWF PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ अनुप्रयोगों के भीतर POT को SVG प्रदान करें" h2="Microsoft<sup>&reg;</sup> PowerPoint का उपयोग किए बिना अपने C++ अनुप्रयोगों में SVG को POT में कनवर्ट करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
क्या आप एक C++ डेवलपर हैं जो अपने C++ अनुप्रयोगों के अंदर SVG को POT रूपांतरण सुविधा में एकीकृत करने के लिए जोड़ना चाहते हैं? आप इसे दो सरल चरणों में कर सकते हैं। आप [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) का इस्तेमाल करके पीपीटीएक्स को सीजीएम एक्सपोर्ट कर सकते हैं। दूसरे, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) का उपयोग करके, आप PPTX को POT में बदल सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="ओडीपी को सीजीएम निर्यात करने के लिए सी++ एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) मेथड फंक्शन का उपयोग करके SVG को PPTX में बदलें
3. [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग संदर्भ का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को POT प्रारूप में सहेजें और `Pot` को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class
auto doc = MakeObject<Document>(u"template.svg");
// save SVG as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pot format
prs->Save(u"output.pot", Aspose::Slides::Export::SaveFormat::Pot);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से SVG दस्तावेज़ का पासवर्ड बदलें" %}}
POT को SVG प्रदान करने की प्रक्रिया में, आप पासवर्ड से सुरक्षित SVG खोल सकते हैं और उसका पासवर्ड भी बदल सकते हैं। SVG फ़ाइल का पासवर्ड बदलने के लिए, आपको उस दस्तावेज़ के स्वामी का पासवर्ड पता होना चाहिए। आप पासवर्ड से सुरक्षित PDF दस्तावेज़ को [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) के साथ लोड कर सकते हैं और पासवर्ड बदलने के लिए ChangePasswords पद्धति का उपयोग कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="वेब से छवियों को POT फ़ाइल में C++ के माध्यम से जोड़ें" %}}
SVG को POT में बदलने के बाद, आप अपने आउटपुट दस्तावेज़ में वेब से चित्र भी जोड़ सकते हैं। [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) इन लोकप्रिय प्रारूपों में छवियों के साथ संचालन का समर्थन करता है: जेपीईजी, पीएनजी, बीएमपी, जीआईएफ, और अन्य। आप किसी प्रस्तुतिकरण में स्लाइड पर अपने कंप्यूटर पर एक या अधिक छवियाँ जोड़ सकते हैं। C++ में यह नमूना कोड आपको दिखाता है कि किसी POT फ़ाइल में छवि कैसे जोड़ें
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POT file
auto pres = System::MakeObject<Presentation>("output.pot");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.pot", SaveFormat::Pot);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-powerpoint/" name="SVG प्रति POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-pot/" name="SVG प्रति POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-xaml/" name="SVG प्रति XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-otp/" name="SVG प्रति OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-ppsm/" name="SVG प्रति PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-potx/" name="SVG प्रति POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-pptm/" name="SVG प्रति PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-potm/" name="SVG प्रति POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-ppt/" name="SVG प्रति PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-pps/" name="SVG प्रति PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-swf/" name="SVG प्रति SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/svg-to-ppsx/" name="SVG प्रति PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}