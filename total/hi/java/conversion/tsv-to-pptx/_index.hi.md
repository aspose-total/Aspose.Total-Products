---
title: जावा का उपयोग करके TSV को PPTX में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: जावा एपीआई एक्सेल या वर्ड का उपयोग करके सीएसवी को डीओसी में निर्यात करने के लिए या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।
url_ignore: /hi/java/conversion/tsv-to-pptx/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: PPTX
otherformats: PPTX WORD POWERPOINT PPTXX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सीएसवी को डीओसी में निर्यात करने के लिए जावा एपीआई या ऑनलाइन" h2="माइक्रोसॉफ्ट एक्सेल पर भरोसा किए बिना सीएसवी को डीओसी में निर्यात करने के लिए परिसर जावा एपीआई पर&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
सीएसवी को डीओसी को प्रस्तुत करना दो चरणों वाली प्रक्रिया है। दिए गए TSV दस्तावेज़ को PDF में बदलने के लिए आप पहले [Aspose.Cells for Java](https://products.aspose.com/cells/java) API का इस्तेमाल करेंगे और फिर [Aspose.PDF for Java](https) का इस्तेमाल करेंगे ://products.aspose.com/pdf/java) एपीआई, आप आसानी से अपने पीडीएफ दस्तावेज़ को डीओसी में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Java](https://products.aspose.com/total/java/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी के संग्रह में आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा एपीआई के माध्यम से सीएसवी को डीओसी में कैसे बदलें" %}}
1. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके TSV फ़ाइल खोलें
2. TSV को PDF में बदलें और SaveFormat को AUTO पर सेट करें
3. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके परिवर्तित पीडीएफ फाइल को लोड करें
4. दस्तावेज़ को [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions का उपयोग करके PPTX प्रारूप में सहेजें।-) विधि और डॉक को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आपको [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे जावा के लिए Aspose.Total का उपयोग करना होगा। और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>बीएमपी से जीआईएफ के लिए ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=tsv" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/tsv-to-pptx/">बीएमपी से जीआईएफ रूपांतरण के लिए हमारे मुफ्त ऐप का प्रयास करें</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tsv-to-pptxx/" name="TSV सेवा PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tsv-to-pptx/" name="TSV सेवा PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tsv-to-powerpoint/" name="TSV सेवा POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/tsv-to-word/" name="TSV सेवा WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}