---
title: पीओटी को डीओसी में बदलने के लिए सी++ एपीआई
description: अपने सी ++ अनुप्रयोगों के भीतर डीओसी को पीओटी निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: PPTX
outformat: RTF
otherformats: OTT DOT WORD DOTM TEXT DOC WORDML DOCM DOTX FLATOPC DOCX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ एपीआई डीओसी को पॉट प्रस्तुत करने के लिए" h2="बिना किसी Microsoft PowerPoint या Word निर्भरता के C++ अनुप्रयोगों में RTF को PPTX निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) C++ फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी का पूरा पैकेज है। pacakge में उपलब्ध APIs की समृद्ध विशेषताओं का उपयोग करके, हम आसानी से PowerPoint PPTX को Word RTF में बदल सकते हैं। रूपांतरण करने के लिए, आप PPTX को HTML में बदलने के लिए पहले [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) API का उपयोग कर सकते हैं। उसके बाद सुविधा संपन्न वर्ड प्रोसेसिंग एपीआई [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके आप HTML को RTF में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पीओटी को डीओसी में बदलने के लिए सी++ एपीआई" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग संदर्भ का उपयोग करके PPTX फ़ाइल लोड करें
2. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) सदस्य funciton का उपयोग करके HTML को PPTX रेंडर करें और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string) सदस्य fucntion का उपयोग करके दस्तावेज़ को RTF प्रारूप में सहेजें
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
// load HTML with an instance of Rtfument
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"htmlOutput.html");
// save rtfument in RTF format
rtf->Save(u"output.rtf"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>बीएमपी से जीआईएफ के लिए मुफ्त ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=rtf&from=pptx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-ott/" name="PPTX प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dot/" name="PPTX प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-word/" name="PPTX प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotm/" name="PPTX प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-text/" name="PPTX प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-rtf/" name="PPTX प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-wordml/" name="PPTX प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-rtfm/" name="PPTX प्रति RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-dotx/" name="PPTX प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-flatopc/" name="PPTX प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-rtfx/" name="PPTX प्रति RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/pptx-to-odt/" name="PPTX प्रति ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}