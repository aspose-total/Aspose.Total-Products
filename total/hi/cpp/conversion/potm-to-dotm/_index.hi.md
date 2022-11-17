---
title: पीओटी को डीओसी में बदलने के लिए सी++ एपीआई
description: अपने सी ++ अनुप्रयोगों के भीतर डीओसी को पीओटी निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: DOTM
otherformats: DOC TEXT WORDML DOT FLATOPC RTF DOCM WORD DOCX ODT OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ एपीआई डीओसी को पॉट प्रस्तुत करने के लिए" h2="बिना किसी Microsoft PowerPoint या Word निर्भरता के C++ अनुप्रयोगों में DOTM को POTM निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) C++ फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी का पूरा पैकेज है। pacakge में उपलब्ध APIs की समृद्ध विशेषताओं का उपयोग करके, हम आसानी से PowerPoint POTM को Word DOTM में बदल सकते हैं। रूपांतरण करने के लिए, आप POTM को HTML में बदलने के लिए पहले [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API का उपयोग कर सकते हैं। उसके बाद सुविधा संपन्न वर्ड प्रोसेसिंग एपीआई [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके आप HTML को DOTM में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पीओटी को डीओसी में बदलने के लिए सी++ एपीआई" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग संदर्भ का उपयोग करके POTM फ़ाइल लोड करें
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) सदस्य funciton का उपयोग करके HTML को POTM रेंडर करें और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string) सदस्य fucntion का उपयोग करके दस्तावेज़ को DOTM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotmument
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"htmlOutput.html");
// save dotmument in DOTM format
dotm->Save(u"output.dotm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-dotm/" name="POTM प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-text/" name="POTM प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-wordml/" name="POTM प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-dot/" name="POTM प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-flatopc/" name="POTM प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-rtf/" name="POTM प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-dotmm/" name="POTM प्रति DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-word/" name="POTM प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-dotmx/" name="POTM प्रति DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-odt/" name="POTM प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-ott/" name="POTM प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/potm-to-dotx/" name="POTM प्रति DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}