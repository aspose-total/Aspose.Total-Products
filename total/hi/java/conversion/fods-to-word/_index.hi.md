---
title: जावा का उपयोग करके FODS को WORD में बदलें
description: जावा एपीआई एक्सेल या वर्ड का उपयोग करके सीएसवी को डीओसी में निर्यात करने के लिए
url: /hi/java/conversion/fods-to-word/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: WORD
otherformats: PPTX WORD WORDX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सीएसवी को डीओसी में निर्यात करने के लिए जावा एपीआई" h2="माइक्रोसॉफ्ट एक्सेल पर भरोसा किए बिना सीएसवी को डीओसी में निर्यात करने के लिए परिसर जावा एपीआई पर&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
सीएसवी को डीओसी को प्रस्तुत करना दो चरणों वाली प्रक्रिया है। दिए गए FODS दस्तावेज़ को PDF में बदलने के लिए आप पहले [Aspose.Cells for Java](https://products.aspose.com/cells/java) API का इस्तेमाल करेंगे और फिर [जावा के लिए Aspose.Pdf](https) का इस्तेमाल करेंगे ://products.aspose.com/pdf/java) एपीआई, आप आसानी से अपने पीडीएफ दस्तावेज़ को डीओसी में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Java](https://products.aspose.com/total/java/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी के संग्रह में आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा एपीआई के माध्यम से सीएसवी को डीओसी में कैसे बदलें" %}}
1. [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके FODS फ़ाइल खोलें
2. FODS को PDF में बदलें और SaveFormat को AUTO पर सेट करें
3. [दस्तावेज़](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Wordument) वर्ग का उपयोग करके परिवर्तित पीडीएफ फाइल को लोड करें
4. दस्तावेज़ को [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Wordument#save-java.lang.String-com.aspose.pdf.SaveOptions का उपयोग करके WORD प्रारूप में सहेजें।-) विधि और डॉक को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आपको [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे जावा के लिए Aspose.Total का उपयोग करना होगा। और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Wordument class
Wordument wordument = new Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/fods-to-wordx/" name="FODS सेवा WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/fods-to-pptx/" name="FODS सेवा PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/fods-to-powerpoint/" name="FODS सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/fods-to-word/" name="FODS सेवा WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}