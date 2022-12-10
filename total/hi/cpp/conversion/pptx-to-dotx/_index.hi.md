---
title: पीओटी को डीओसी में बदलने के लिए सी++ एपीआई
description: अपने सी ++ अनुप्रयोगों के भीतर डीओसी को पीओटी निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: DOTX
otherformats: DOCX OTT ODT FLATOPC WORD WORDML DOC DOCM DOT TEXT DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ एपीआई डीओसी को पॉट प्रस्तुत करने के लिए" h2="बिना किसी Microsoft PowerPoint या Word निर्भरता के C++ अनुप्रयोगों में DOTX को PPTX निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) C++ फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी का पूरा पैकेज है। pacakge में उपलब्ध APIs की समृद्ध विशेषताओं का उपयोग करके, हम आसानी से PowerPoint PPTX को Word DOTX में बदल सकते हैं। रूपांतरण करने के लिए, आप PPTX को HTML में बदलने के लिए पहले [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API का उपयोग कर सकते हैं। उसके बाद सुविधा संपन्न वर्ड प्रोसेसिंग एपीआई [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके आप HTML को DOTX में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पीओटी को डीओसी में बदलने के लिए सी++ एपीआई" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग संदर्भ का उपयोग करके PPTX फ़ाइल लोड करें
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) सदस्य funciton का उपयोग करके HTML को PPTX रेंडर करें और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string) सदस्य fucntion का उपयोग करके दस्तावेज़ को DOTX प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotxument
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"htmlOutput.html");
// save dotxument in DOTX format
dotx->Save(u"output.dotx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotxx/" name="PPTX प्रति DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-ott/" name="PPTX प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-odt/" name="PPTX प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-flatopc/" name="PPTX प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-word/" name="PPTX प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-wordml/" name="PPTX प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotx/" name="PPTX प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotxm/" name="PPTX प्रति DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dot/" name="PPTX प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-text/" name="PPTX प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotm/" name="PPTX प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-rtf/" name="PPTX प्रति RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}