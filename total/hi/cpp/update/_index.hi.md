---
title: C++ का उपयोग करके एक्सेल फाइल को अपडेट करें 

description: C++ आधारित अनुप्रयोगों के साथ Microsoft Office स्थापित किए बिना Microsoft Excel XLSX, XLS, CSV दस्तावेज़ों को संपादित करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ के माध्यम से एक्सेल दस्तावेज़ों को अपडेट करें" h2="Microsoft Excel XLSX, XLS फ़ाइलों को C++ आधारित अनुप्रयोगों में बिना Microsoft Office<sup>&reg;</sup> इंस्टॉल किए संशोधित करें।" >}}

{{% blocks/products/pf/feature-page-summary %}}
कंपनी सॉफ़्टवेयर के माध्यम से छात्रों के डेटा, रोगियों के रिकॉर्ड और वेयरहाउस आइटम सूची आदि जैसे एक्सेल फ़ाइलों में संग्रहीत अपने डेटा को अपडेट करना संगठन के लिए सामान्य है। [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API सॉफ़्टवेयर का उपयोग करके स्प्रैडशीट को संशोधित करने की कार्यक्षमता प्रदान करता है। प्रोग्रामर केवल एपीआई कोड की कुछ पंक्तियाँ लिखकर सॉफ्टवेयर को संशोधन क्षमताओं के साथ बढ़ा सकते हैं। [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API जो [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज का हिस्सा है, इस संशोधन प्रक्रिया को आसान बनाता है। नीचे बीएमपी दस्तावेज़ को अद्यतन करने की प्रक्रिया है।
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="C++ का उपयोग करके एक्सेल दस्तावेज़ों को अपडेट करें" %}}

[Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API का उपयोग करके, [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) का उपयोग करके स्रोत दस्तावेज़ लोड करें। GetIWorksheets()->GetObjectByIndex(0) का उपयोग करके [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) और GetICells()->GetObjectByIndex का उपयोग करके आवश्यक सेल तक पहुँचें। PutValue पद्धति का उपयोग करके, एक्सेस किए गए सेल में सामग्री को संशोधित करें। दस्तावेज़ को सहेजने के लिए अंतिम रूप से सेव () विधि का आह्वान करें।

{{% blocks/products/pf/feature-page-code h3="सी ++ कोड - एक्सेल दस्तावेज़ों को अपडेट करें" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="अद्यतन">}}