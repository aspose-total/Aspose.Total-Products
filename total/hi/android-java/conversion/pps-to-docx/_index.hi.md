---
title: जावा के माध्यम से Andorid पर DOCX को PPS निर्यात करें
description: बिना किसी सॉफ्टवेयर को इंस्टॉल किए मोबाइल ऐप्स में PPS को DOCX में बदलें

family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: DOCX
otherformats: DOTX FLATOPC TEXT DOCM DOTM OTT WORD DOT DOC WORDML ODT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंडोरिड पर पीओटी को डीओसी को प्रस्तुत करना" h2="Microsoft PowerPoint या Word पर निर्भर किए बिना Android ऐप्स के भीतर PPS को DOCX में बदलने के लिए फ़ाइल स्वरूप API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Android ऐप्लिकेशन के भीतर फ़ाइल स्वरूपों में हेरफेर करने की अनुमति देता है। पैकेज में दिए गए API का उपयोग करके आप अपने ऐप्स में PowerPoint PPS से Word DOCX रूपांतरण प्रक्रिया को स्वचालित कर सकते हैं।
आप अपने दिए गए दस्तावेज़ को दो चरणों में बदल सकते हैं। आप [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) का उपयोग कर सकते हैं जो कि HTML को PPS रेंडर करने के लिए Android एप्लिकेशन के लिए एक PowerPoint API है। उसके बाद दस्तावेज़ संसाधन API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके आप HTML को DOCX में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में PPS से DOCX रेंडरिंग" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPS फ़ाइल खोलें
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)  का उपयोग करके PPS को HTML में बदलें।ISaveOptions-) विधि और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को DOCX प्रारूप में सहेजें और Docx सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और स्थापित करें [Aspose.Slides for Android via Java](https://docxs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) और [Aspose.Words for Andorid by Java](https://docxs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके अनुप्रयोग।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOCX format
document.save("output.docx",SaveFormat.Docxx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-dotx/" name="PPS प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-flatopc/" name="PPS प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-text/" name="PPS प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-docxm/" name="PPS प्रति DOCXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-dotm/" name="PPS प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-ott/" name="PPS प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-word/" name="PPS प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-dot/" name="PPS प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-docx/" name="PPS प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-wordml/" name="PPS प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-odt/" name="PPS प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/pps-to-rtf/" name="PPS प्रति RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}