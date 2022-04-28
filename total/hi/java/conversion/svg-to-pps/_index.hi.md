---
title: जावा एपीआई के माध्यम से सीजीएम को ओडीपी में कनवर्ट करें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना सीजीएम को ओडीपी में कनवर्ट करने के लिए
url: /hi/java/conversion/svg-to-pps/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: PPS
otherformats: PPT POT POWERPOINT PPSX PPSM POTM XAML PPS SWF OTP PPTM POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सीजीएम को ओडीपी में निर्यात करने के लिए जावा एपीआई" h2="Microsoft<sup>&reg;</sup> PowerPoint या Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना ऑन-प्रिमाइसेस Java API के माध्यम से PPS को SVG निर्यात करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप किसी भी Java J2SE, J2EE, J2ME एप्लिकेशन में आसानी से SVG को PPS में बदल सकते हैं। सबसे पहले, [जावा के लिए Aspose.PDF](https://products.aspose.com/pdf/java/) का उपयोग करके, आप PPTX को SVG निर्यात कर सकते हैं। उसके बाद, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API का उपयोग करके, आप PPTX को PPS में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को ओडीपी में बदलने के लिए जावा एपीआई" %}}
1. [दस्तावेज़](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) पद्धति का उपयोग करके SVG को PPTX में बदलें
3. [प्रस्तुति](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) विधि का उपयोग करके दस्तावेज़ को PPS प्रारूप में सहेजें और ` PPS` SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [जावा के लिए Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) और [Aspose.Slides for Java](https://docs.aspose.com/slides/java/) शामिल करें स्थापना/) अपने pom.xml में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}](
SVG फ़ाइल स्वरूप लोड करते समय, आपका दस्तावेज़ पासवर्ड से सुरक्षित हो सकता है। [जावा के लिए Aspose.PDF](https://products.aspose.com/pdf/java/) आपको एन्क्रिप्टेड दस्तावेज़ भी खोलने की अनुमति देता है। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [दस्तावेज़](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) के नए इंस्टेंस को इनिशियलाइज़ कर सकते हैं .lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।  
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एन्क्रिप्टेड सीजीएम फ़ाइल खोलें" %}}
सीजीएम को ओडीपी में बदलने के बाद, आप अपनी प्रस्तुति के लिए पूर्वनिर्धारित दृश्य प्रकार भी जोड़ सकते हैं। [Aspose.Slides for Java](https://products.aspose.com/slides/java/) पावरपॉइंट में [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) वर्ग। [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) प्रॉपर्टी का इस्तेमाल [ViewType](https:/) का इस्तेमाल करके व्यू टाइप सेट करने के लिए किया जाता है /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) एन्यूमरेटर। 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-pps/" name="SVG सेवा PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-swf/" name="SVG सेवा SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-potx/" name="SVG सेवा POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-ppsx/" name="SVG सेवा PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-potm/" name="SVG सेवा POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-ppt/" name="SVG सेवा PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-ppsm/" name="SVG सेवा PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-xaml/" name="SVG सेवा XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-otp/" name="SVG सेवा OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-pptm/" name="SVG सेवा PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-pot/" name="SVG सेवा POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/svg-to-powerpoint/" name="SVG सेवा POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}