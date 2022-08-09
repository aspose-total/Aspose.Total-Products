---
title: जावा के माध्यम से Andorid पर DOTX को POTX निर्यात करें
description: बिना किसी सॉफ्टवेयर को इंस्टॉल किए मोबाइल ऐप्स में POTX को DOTX में बदलें
url: /hi/android-java/conversion/potx-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOTX
otherformats: OTT TEXT WORD RTF DOCM DOTM FLATOPC WORDML DOT DOC DOCX ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंडोरिड पर पीओटी को डीओसी को प्रस्तुत करना" h2="Microsoft PowerPoint या Word पर निर्भर किए बिना Android ऐप्स के भीतर POTX को DOTX में बदलने के लिए फ़ाइल स्वरूप API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android by Java](https://products.aspose.com/total/android-java/) Android ऐप्लिकेशन के भीतर फ़ाइल स्वरूपों में हेरफेर करने की अनुमति देता है। पैकेज में दिए गए API का उपयोग करके आप अपने ऐप्स में PowerPoint POTX से Word DOTX रूपांतरण प्रक्रिया को स्वचालित कर सकते हैं।
आप अपने दिए गए दस्तावेज़ को दो चरणों में बदल सकते हैं। आप [Aspose.Slides for Andorid by Java](https://products.aspose.com/slides/android-java/) का उपयोग कर सकते हैं जो कि HTML को POTX रेंडर करने के लिए Android एप्लिकेशन के लिए एक PowerPoint API है। उसके बाद दस्तावेज़ संसाधन API [Aspose.Words for Android by Java](https://products.aspose.com/words/android-java/) का उपयोग करके आप HTML को DOTX में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में POTX से DOTX रेंडरिंग" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके POTX फ़ाइल खोलें
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)  का उपयोग करके POTX को HTML में बदलें।ISaveOptions-) विधि और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [दस्तावेज़](https://reference.aspose.com/words/java/com.aspose.words/Dotxument) वर्ग का उपयोग करके लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को DOTX प्रारूप में सहेजें और Dotx सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे जावा के माध्यम से Android के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और स्थापित करें [जावा के माध्यम से Android के लिए Aspose.Slides](https://dotxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) और [Aspose.Words for Andorid by Java](https://dotxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके अनुप्रयोग।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Dotxument
Dotxument dotxument = new Dotxument("htmlOutput.html");
// save dotxument in DOTX format
dotxument.save("output.dotx",SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-ott/" name="POTX प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-text/" name="POTX प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-word/" name="POTX प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-rtf/" name="POTX प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotxm/" name="POTX प्रति DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotm/" name="POTX प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-flatopc/" name="POTX प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-wordml/" name="POTX प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dot/" name="POTX प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotx/" name="POTX प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotxx/" name="POTX प्रति DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-odt/" name="POTX प्रति ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}