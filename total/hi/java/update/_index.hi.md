---
title: जावा का उपयोग करके एक्सेल फाइल को अपडेट करें 

description: जावा आधारित अनुप्रयोगों के भीतर Microsoft Office स्थापित किए बिना Microsoft Excel XLSX, XLS, CSV दस्तावेज़ों को संपादित करें।
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एक्सेल दस्तावेज़ों को अपडेट करें" h2="Microsoft Office<sup>&reg;</sup> को स्थापित किए बिना जावा आधारित अनुप्रयोगों के भीतर Microsoft Excel XLSX, XLS फ़ाइलों को संशोधित करें।" >}}

{{% blocks/products/pf/feature-page-summary %}}
कंपनी सॉफ़्टवेयर के माध्यम से छात्रों के डेटा, रोगियों के रिकॉर्ड और वेयरहाउस आइटम सूची आदि जैसे एक्सेल फ़ाइलों में संग्रहीत अपने डेटा को अपडेट करना संगठन के लिए सामान्य है। [Aspose.Total for Java](https://products.aspose.com/total/java/) API अपने स्वयं के सॉफ़्टवेयर का उपयोग करके स्प्रैडशीट को संशोधित करने की कार्यक्षमता प्रदान करता है। प्रोग्रामर केवल एपीआई कोड की कुछ पंक्तियाँ लिखकर सॉफ्टवेयर को संशोधन क्षमताओं के साथ बढ़ा सकते हैं। [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API जो [Aspose.Total for Java](https://products.aspose.com/total/java/) पैकेज का हिस्सा है, इस संशोधन प्रक्रिया को आसान बनाता है। नीचे बीएमपी दस्तावेज़ को अद्यतन करने की प्रक्रिया है।
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="जावा का उपयोग करके एक्सेल दस्तावेज़ों को अपडेट करें" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) वर्ग प्रदान करता है जो एक्सेल स्प्रेडशीट की लोडिंग को संभालता है। प्रक्रिया सरल है। स्रोत फ़ाइल को पैरामीटर के रूप में प्रदान करके वर्कबुक क्लास ऑब्जेक्ट बनाएं। [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)) विधि का उपयोग करके प्रासंगिक वर्कशीट और प्रासंगिक सेल तक पहुँचें। एक्सेस किए गए सेल में सामग्री को संशोधित करने के लिए [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) विधि का उपयोग करें और अंत में दस्तावेज़ को बचाने के लिए सेव () विधि को कॉल करें।

{{% blocks/products/pf/feature-page-code h3="जावा कोड - एक्सेल दस्तावेज़ों को अपडेट करें" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="अद्यतन">}}