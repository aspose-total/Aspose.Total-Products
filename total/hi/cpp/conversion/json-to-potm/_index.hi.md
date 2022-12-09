---
title: जेएसओएन प्रारूप को सी ++ के माध्यम से ओडीपी में कनवर्ट करें
description: Microsoft PowerPoint का उपयोग किए बिना JSON को POTM में C++ में पार्स करें

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTX OTP ODP PPT PPTM PPSM PPSX POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जेएसओएन प्रारूप को सी ++ के माध्यम से ओडीपी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> PowerPoint का उपयोग किए बिना JSON को POTM में पार्स करने के लिए C++ API" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप किसी भी C++ एप्लिकेशन में JSON को POTM में दो सरल चरणों में बदल सकते हैं। सबसे पहले, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) का उपयोग करके, आप JSON को PPTX में पार्स कर सकते हैं। उसके बाद, [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) का उपयोग करके, आप PPTX को POTM में बदल सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जेएसओएन प्रारूप को सी ++ के माध्यम से ओडीपी में कनवर्ट करें" %}}
1. एक नया [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) विधि का उपयोग करके JSON को PPTX के रूप में सहेजें
3. [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) विधि का उपयोग करके दस्तावेज़ को POTM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से `` `इंस्टॉल-पैकेज Aspose.Total.Cpp`` के साथ इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="लेआउट सेट करें और JSON फॉर्मेट को C++ के जरिए POTM में बदलें" %}}
JSON को POTM में पार्स करते समय, आप JSON को [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) वर्ग के साथ लोड करके पंक्तियों और स्तंभों का आकार भी सेट कर सकते हैं। यदि आपको वर्कशीट में सभी पंक्तियों के लिए समान पंक्ति ऊंचाई सेट करने की आवश्यकता है, तो आप इसे [सेटस्टैंडर्डहाइट](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a1e3f1467f) का उपयोग करके कर सकते हैं। ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) संग्रह की विधि। इसी तरह, वर्कशीट में सभी कॉलम के लिए समान कॉलम चौड़ाई सेट करने के लिए, ICells संग्रह की [सेटस्टैंडर्डविड्थ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) विधि का उपयोग करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जेएसओएन प्रारूप को सी ++ में वॉटरमार्क के साथ ओडीपी में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप JSON को वॉटरमार्क के साथ POTM में भी बदल सकते हैं। अपने POTM दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON को PPTX में पार्स कर सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [प्रस्तुति](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) वर्ग का उपयोग करके नई बनाई गई PPTX फ़ाइल लोड करें, पहली स्लाइड प्राप्त करें, एक जोड़ें आयत प्रकार का ऑटोशेप, आयत में टेक्स्टफ़्रेम जोड़ें, टेक्स्ट फ़्रेम के लिए पैराग्राफ़ ऑब्जेक्ट बनाएँ, पैराग्राफ़ के लिए भाग ऑब्जेक्ट बनाएँ, set_Text() का उपयोग करके वॉटरमार्क जोड़ें और, दस्तावेज़ को POTM में सहेज सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-potx/" name="JSON प्रति POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-otp/" name="JSON प्रति OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-potm/" name="JSON प्रति POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-ppt/" name="JSON प्रति PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-pptm/" name="JSON प्रति PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-ppsm/" name="JSON प्रति PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-ppsx/" name="JSON प्रति PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-powerpoint/" name="JSON प्रति POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-pot/" name="JSON प्रति POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-pps/" name="JSON प्रति PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}