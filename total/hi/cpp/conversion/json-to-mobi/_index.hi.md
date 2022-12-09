---
title: जेएसओएन प्रारूप को सी ++ के माध्यम से सीएचएम में कनवर्ट करें
description: C++ API t0 Microsoft Word का उपयोग किए बिना JSON को MOBI में पार्स करें

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: WORD FLATOPC DOT RTF DOCM WORDML CHM OTT PS DOTX EPUB ODT PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जेएसओएन प्रारूप को सी ++ के माध्यम से सीएचएम में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> Word का उपयोग किए बिना C++ अनुप्रयोगों में JSON को MOBI में पार्स करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) का उपयोग करके आप दो आसान चरणों में अपने C++ ऐप्लिकेशन में JSON को MOBI में पार्स कर सकते हैं। सबसे पहले, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) का उपयोग करके, आप JSON को PDF में निर्यात कर सकते हैं। उसके बाद, [Aspose.Words for C++](https://products.aspose.com/words/cppp/) का उपयोग करके, आप PDF को MOBI में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="JSON फॉर्मेट को C++ में MOBI में बदलें" %}}
1. एक नया [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ऑब्जेक्ट बनाएं और फ़ाइल से मान्य JSON डेटा पढ़ें
2. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) विधि का उपयोग करके JSON को PDF के रूप में सहेजें
3. [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग का उपयोग करके पीडीएफ दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) विधि का उपयोग करके दस्तावेज़ को MOBI प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से `` `इंस्टॉल-पैकेज Aspose.Total.Cpp`` के साथ इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="लेआउट सेट करें और JSON फॉर्मेट को C++ में MOBI में बदलें" %}}
JSON को MOBI में पार्स करते समय, आप JSON को [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) क्लास के साथ लोड करके पंक्तियों और स्तंभों का आकार भी सेट कर सकते हैं। यदि आपको वर्कशीट में सभी पंक्तियों के लिए समान पंक्ति ऊंचाई सेट करने की आवश्यकता है, तो आप इसे [सेटस्टैंडर्डहाइट](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a1e3f1467f) का उपयोग करके कर सकते हैं। ) [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) संग्रह की विधि। इसी तरह, वर्कशीट में सभी कॉलम के लिए समान कॉलम चौड़ाई सेट करने के लिए, ICells संग्रह की [सेटस्टैंडर्डविड्थ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) विधि का उपयोग करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जेएसओएन प्रारूप को सी ++ में वॉटरमार्क के साथ सीएचएम में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप जेएसओएन को सीएचएम को वॉटरमार्क के साथ भी पार्स कर सकते हैं। अपने सीएचएम दस्तावेज़ में वॉटरमार्क जोड़ने के लिए, आप पहले JSON को PDF में बदल सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) वर्ग का उपयोग करके नई बनाई गई पीडीएफ फाइल को लोड करें, टेक्स्ट वॉटरमार्क के लिए अलग-अलग गुण सेट करें,
SetText विधि को कॉल करें और वॉटरमार्क टेक्स्ट और TextWatermarkOptions का ऑब्जेक्ट पास करें। वॉटरमार्क जोड़ने के बाद, आप दस्तावेज़ को सीएचएम में सहेज सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-word/" name="JSON प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-flatopc/" name="JSON प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-dot/" name="JSON प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-rtf/" name="JSON प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-docm/" name="JSON प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-wordml/" name="JSON प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-mobi/" name="JSON प्रति MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-ott/" name="JSON प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-ps/" name="JSON प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-dotx/" name="JSON प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-epub/" name="JSON प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-odt/" name="JSON प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-pcl/" name="JSON प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/json-to-doc/" name="JSON प्रति DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}