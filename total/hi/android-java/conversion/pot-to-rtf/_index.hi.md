---
title: जावा के माध्यम से Andorid पर RTF को POT निर्यात करें
description: बिना किसी सॉफ्टवेयर को इंस्टॉल किए मोबाइल ऐप्स में POT को RTF में बदलें
url: /hi/android-java/conversion/pot-to-rtf/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: RTF
otherformats: DOTX FLATOPC DOC DOCX DOT DOCM OTT WORD DOTM TEXT ODT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंडोरिड पर पीओटी को डीओसी को प्रस्तुत करना" h2="Microsoft PowerPoint या Word पर निर्भर किए बिना Android ऐप्स के भीतर POT को RTF में बदलने के लिए फ़ाइल स्वरूप API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android by Java](https://products.aspose.com/total/android-java/) Android ऐप्लिकेशन के भीतर फ़ाइल स्वरूपों में हेरफेर करने की अनुमति देता है। पैकेज में दिए गए API का उपयोग करके आप अपने ऐप्स में PowerPoint POT से Word RTF रूपांतरण प्रक्रिया को स्वचालित कर सकते हैं।
आप अपने दिए गए दस्तावेज़ को दो चरणों में बदल सकते हैं। आप [Aspose.Slides for Andorid by Java](https://products.aspose.com/slides/android-java/) का उपयोग कर सकते हैं जो कि HTML को POT रेंडर करने के लिए Android एप्लिकेशन के लिए एक PowerPoint API है। उसके बाद दस्तावेज़ संसाधन API [Aspose.Words for Android by Java](https://products.aspose.com/words/android-java/) का उपयोग करके आप HTML को RTF में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में POT से RTF रेंडरिंग" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके POT फ़ाइल खोलें
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)  का उपयोग करके POT को HTML में बदलें।ISaveOptions-) विधि और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [दस्तावेज़](https://reference.aspose.com/words/java/com.aspose.words/Rtfument) वर्ग का उपयोग करके लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को RTF प्रारूप में सहेजें और Rtf सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे जावा के माध्यम से Android के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और स्थापित करें [जावा के माध्यम से Android के लिए Aspose.Slides](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) और [Aspose.Words for Andorid by Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके अनुप्रयोग।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POT file
Presentation presentation = new Presentation("input.pot");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dotx/" name="POT प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-flatopc/" name="POT प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-rtf/" name="POT प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-rtfx/" name="POT प्रति RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dot/" name="POT प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-rtfm/" name="POT प्रति RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-ott/" name="POT प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-word/" name="POT प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-dotm/" name="POT प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-text/" name="POT प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-odt/" name="POT प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pot-to-wordml/" name="POT प्रति WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}