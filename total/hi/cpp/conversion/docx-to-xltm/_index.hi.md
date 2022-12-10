---
title: C++ में DOCX को XLTM में बदलें
description: सी ++ एपीआई माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना डीओसी को सीएसवी में कनवर्ट करने के लिए

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: XLTM
otherformats: EXCEL XLTX TSV XLSB XLT XLS DIF FODS CSV XLAM SXC XLSX ODS XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOCX को C++ के माध्यम से XLTM में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप अपने C++ एप्लिकेशन में DOCX से XLTM रूपांतरण सुविधा को आसानी से शामिल कर सकते हैं। सुविधा संपन्न, शक्तिशाली और उपयोग में आसान दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) का उपयोग करके, आप HTML को DOCX निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) का उपयोग करके, आप HTML को XLTM में बदल सकते हैं। दोनों API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज के अंतर्गत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" %}}
1. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग संदर्भ का उपयोग करके DOCX फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) सदस्य फ़ंक्शन का उपयोग करके DOCX को HTML में बदलें
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) वर्ग संदर्भ का उपयोग करके HTML दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को XLTM प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="सी ++ के माध्यम से डीओसी दस्तावेज़ गुणों तक पहुंचें" %}}DocumentDocument
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) भी आपको DOCX फ़ाइल के दस्तावेज़ गुणों तक पहुंचने की अनुमति देता है और आपको रूपांतरण प्रक्रिया से पहले एक सूचित निर्णय लेने देता है। दस्तावेज़ गुणों तक पहुँचने के लिए आप [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) का उपयोग करके अंतर्निहित गुण प्राप्त कर सकते हैं और [CustomDocxumentProperties](https:// Reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) कस्टम गुण प्राप्त करने के लिए। निम्न कोड उदाहरण दिखाता है कि किसी दस्तावेज़ में सभी अंतर्निहित और कस्टम गुणों की गणना कैसे करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="सीएसवी फ़ाइल को सी++ के माध्यम से स्ट्रीम करने के लिए सहेजें" %}}
DOCX को XLTM में बदलने के बाद, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) आपको अपने दस्तावेज़ को स्ट्रीम में सहेजने में सक्षम बनाता है। फ़ाइलों को स्ट्रीम में सहेजने के लिए, एक मेमोरीस्ट्रीम या फ़ाइलस्ट्रीम ऑब्जेक्ट बनाएं और [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) पर कॉल करके फ़ाइल को उस स्ट्रीम ऑब्जेक्ट में सहेजें। ऑब्जेक्ट की [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) विधि। [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) एन्यूमरेशन का उपयोग करके [सेव](https://reference.aspose.com) एन्यूमरेशन का उपयोग करके वांछित फ़ाइल स्वरूप निर्दिष्ट करें) विधि।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-excel/" name="DOCX प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xltx/" name="DOCX प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-tsv/" name="DOCX प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xlsb/" name="DOCX प्रति XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xlt/" name="DOCX प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xls/" name="DOCX प्रति XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-dif/" name="DOCX प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-fods/" name="DOCX प्रति FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xltm/" name="DOCX प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xlam/" name="DOCX प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-sxc/" name="DOCX प्रति SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xlsx/" name="DOCX प्रति XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-ods/" name="DOCX प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/docx-to-xlsm/" name="DOCX प्रति XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}