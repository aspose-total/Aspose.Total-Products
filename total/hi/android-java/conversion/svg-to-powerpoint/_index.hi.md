---
title: Android में SVG को POWERPOINT में निर्यात करें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना सीजीएम को ओडीपी में बदलने के लिए एंड्रॉइड एपीआई

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: POWERPOINT
otherformats: PPSX PPSM PPS POTM XAML OTP ODP PPTM SWF POTX PPT POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड पर सीजीएम को ओडीपी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> PowerPoint या Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना अपने Android ऐप्लिकेशन में SVG को POWERPOINT में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप दो सरल चरणों का उपयोग करके अपने Android एप्लिकेशन के अंदर SVG से POWERPOINT रूपांतरण सुविधा को एकीकृत कर सकते हैं। पहले चरण में आप [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) का उपयोग करके PPTX को SVG निर्यात कर सकते हैं। उसके बाद, [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) का उपयोग करके, आप PPTX को POWERPOINT में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) पैकेज के तहत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को ओडीपी में निर्यात करने के लिए एंड्रॉइड एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) पद्धति का उपयोग करके SVG को PPTX में बदलें
3. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) पद्धति का उपयोग करके दस्तावेज़ को POWERPOINT प्रारूप में सहेजें और ` POWERPOINT` SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) और [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) इंस्टॉल करें /androidjava/install-aspose-slides-for-android-via-java/) आपके अनुप्रयोगों में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Ppt format
presentation.save("output.ppt", SaveFormat.Ppt);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में पासवर्ड संरक्षित SVG फ़ाइल खोलें" %}}
SVG फ़ाइल स्वरूप लोड करते समय, आपका दस्तावेज़ पासवर्ड से सुरक्षित हो सकता है। [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) आपको एन्क्रिप्ट किए गए दस्तावेज़ भी खोलने की अनुमति देता है। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) के नए इंस्टेंस को इनिशियलाइज़ कर सकते हैं .lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।
{{% blocks/products/pf/feature-page-code %}}

```java
// open SVG document
Document doc = new Document("input.svg", "Your@Password");
// save SVG as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
](https://
{{% blocks/products/pf/feature-page-section  h2="Android एप्लिकेशन में POWERPOINT फ़ाइल की थंबनेल छवि बनाएं" %}}
SVG को POWERPOINT में बदलने के बाद, आप अपने आउटपुट दस्तावेज़ की थंबनेल इमेज भी बना सकते हैं। रिच इन फीचर [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) का उपयोग करके आप [प्रेजेंटेशन]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग। उसके बाद, आप किसी भी वांछित स्लाइड का संदर्भ उसकी आईडी या अनुक्रमणिका का उपयोग करके प्राप्त कर सकते हैं और निर्दिष्ट पैमाने पर संदर्भित स्लाइड की थंबनेल छवि प्राप्त कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a POWERPOINT file
Presentation presentation = new Presentation("output.powerpoint");
// access the first slide
ISlide sld = pres.getSlides().get_Item(0);
// create a full scale image
BufferedImage image = sld.getThumbnail(1f, 1f);
 // save the image to disk in PNG format
ImageIO.write(image, "PNG", new java.io.File("Thumbnail_out.png"));
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}