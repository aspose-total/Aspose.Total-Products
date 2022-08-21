---
title: Android में EPUB को PPS में निर्यात करें
description: माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना सीजीएम को ओडीपी में बदलने के लिए एंड्रॉइड एपीआई
url: /hi/android-java/conversion/epub-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPS
otherformats: PPSM POTM ODP OTP XAML SWF POTX POT POWERPOINT PPTM PPT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंड्रॉइड पर सीजीएम को ओडीपी में कनवर्ट करें" h2="Microsoft<sup>&reg;</sup> PowerPoint या Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना अपने Android ऐप्लिकेशन में EPUB को PPS में रूपांतरित करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
आप दो सरल चरणों का उपयोग करके अपने Android एप्लिकेशन के अंदर EPUB से PPS रूपांतरण सुविधा को एकीकृत कर सकते हैं। पहले चरण में आप [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) का उपयोग करके PPTX को EPUB निर्यात कर सकते हैं। उसके बाद, [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) का उपयोग करके, आप PPTX को PPS में बदल सकते हैं। दोनों एपीआई [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) पैकेज के तहत आते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को ओडीपी में निर्यात करने के लिए एंड्रॉइड एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) पद्धति का उपयोग करके EPUB को PPTX में बदलें
3. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) पद्धति का उपयोग करके दस्तावेज़ को PPS प्रारूप में सहेजें और ` PPS` SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) और [Aspose.Slides for Android via Java](https://docs.aspose.com/slides) इंस्टॉल करें /androidjava/install-aspose-slides-for-android-via-java/) आपके अनुप्रयोगों में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में पासवर्ड संरक्षित EPUB फ़ाइल खोलें" %}}
EPUB फ़ाइल स्वरूप लोड करते समय, आपका दस्तावेज़ पासवर्ड से सुरक्षित हो सकता है। [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) आपको एन्क्रिप्ट किए गए दस्तावेज़ भी खोलने की अनुमति देता है। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) के नए इंस्टेंस को इनिशियलाइज़ कर सकते हैं .lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Android एप्लिकेशन में PPS फ़ाइल की थंबनेल छवि बनाएं" %}}
EPUB को PPS में बदलने के बाद, आप अपने आउटपुट दस्तावेज़ की थंबनेल इमेज भी बना सकते हैं। रिच इन फीचर [Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/) का उपयोग करके आप [प्रेजेंटेशन]( https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग। उसके बाद, आप किसी भी वांछित स्लाइड का संदर्भ उसकी आईडी या अनुक्रमणिका का उपयोग करके प्राप्त कर सकते हैं और निर्दिष्ट पैमाने पर संदर्भित स्लाइड की थंबनेल छवि प्राप्त कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("output.pps");
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
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-ppsm/" name="EPUB प्रति PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-potm/" name="EPUB प्रति POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-pps/" name="EPUB प्रति PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-otp/" name="EPUB प्रति OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-xaml/" name="EPUB प्रति XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-swf/" name="EPUB प्रति SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-potx/" name="EPUB प्रति POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-pot/" name="EPUB प्रति POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-powerpoint/" name="EPUB प्रति POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-pptm/" name="EPUB प्रति PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-ppt/" name="EPUB प्रति PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/epub-to-ppsx/" name="EPUB प्रति PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}