---
title: C++ में DOTX को XLSM में बदलें
description: सी ++ एपीआई माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना डीओसी को सीएसवी में कनवर्ट करने के लिए
url: /hi/cpp/conversion/dotx-to-xlsm/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: XLSM
otherformats: XLT EXCEL ODS XLTM TSV XLAM SXC DIF XLS XLSB XLTX XLSX CSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOTX को C++ के माध्यम से XLSM में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप अपने C++ एप्लिकेशन में DOTX से XLSM रूपांतरण सुविधा को आसानी से शामिल कर सकते हैं। सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके, आप HTML को DOTX निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) का उपयोग करके, आप HTML को XLSM में बदल सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" %}}
1. [दस्तावेज़](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) वर्ग संदर्भ का उपयोग करके DOTX फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string_saveformat) सदस्य फ़ंक्शन का उपयोग करके DOTX को HTML में बदलें
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) वर्ग संदर्भ का उपयोग करके HTML दस्तावेज़ लोड करें
4. [सहेजें](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को XLSM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ के माध्यम से डीओसी दस्तावेज़ गुणों तक पहुंचें" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) भी आपको DOTX फ़ाइल के दस्तावेज़ गुणों तक पहुंचने की अनुमति देता है और आपको रूपांतरण प्रक्रिया से पहले एक सूचित निर्णय लेने देता है। दस्तावेज़ गुणों तक पहुँचने के लिए आप [BuiltInDotxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotxument_properties) का उपयोग करके अंतर्निहित गुण प्राप्त कर सकते हैं और [CustomDotxumentProperties](https:// Reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotxument_properties) कस्टम गुण प्राप्त करने के लिए। निम्न कोड उदाहरण दिखाता है कि किसी दस्तावेज़ में सभी अंतर्निहित और कस्टम गुणों की गणना कैसे करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotxument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सीएसवी फ़ाइल को सी++ के माध्यम से स्ट्रीम करने के लिए सहेजें" %}}
DOTX को XLSM में बदलने के बाद, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) आपको अपने दस्तावेज़ को स्ट्रीम में सहेजने में सक्षम बनाता है। फ़ाइलों को स्ट्रीम में सहेजने के लिए, एक मेमोरीस्ट्रीम या फ़ाइलस्ट्रीम ऑब्जेक्ट बनाएं और [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) पर कॉल करके फ़ाइल को उस स्ट्रीम ऑब्जेक्ट में सहेजें। ऑब्जेक्ट की [सहेजें](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) विधि। [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) एन्यूमरेशन का उपयोग करके [सेव](https://reference.aspose.com) एन्यूमरेशन का उपयोग करके वांछित फ़ाइल स्वरूप निर्दिष्ट करें) विधि।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xlt/" name="DOTX प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-excel/" name="DOTX प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-ods/" name="DOTX प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xltm/" name="DOTX प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-tsv/" name="DOTX प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xlam/" name="DOTX प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-sxc/" name="DOTX प्रति SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-dif/" name="DOTX प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xls/" name="DOTX प्रति XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xlsb/" name="DOTX प्रति XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xltx/" name="DOTX प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xlsx/" name="DOTX प्रति XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-xlsm/" name="DOTX प्रति XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/dotx-to-fods/" name="DOTX प्रति FODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}