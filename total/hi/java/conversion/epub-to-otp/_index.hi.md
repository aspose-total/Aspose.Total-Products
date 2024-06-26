---
title: जावा एपीआई के माध्यम से सीजीएम को ओडीपी में कनवर्ट करें
description: जावा एपीआई माइक्रोसॉफ्ट वर्ड का उपयोग किए बिना सीजीएम को ओडीपी में कनवर्ट करने के लिए
url_ignore: /hi/java/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: POTM PPT POT PPSX PPTM POTX PPSM POWERPOINT PPS XAML OTP SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="सीजीएम को ओडीपी में निर्यात करने के लिए जावा एपीआई" h2="Microsoft<sup>&reg;</sup> PowerPoint या Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना ऑन-प्रिमाइसेस Java API के माध्यम से OTP को EPUB निर्यात करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप किसी भी Java J2SE, J2EE, J2ME एप्लिकेशन में आसानी से EPUB को OTP में बदल सकते हैं। सबसे पहले, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) का उपयोग करके, आप PPTX को EPUB निर्यात कर सकते हैं। उसके बाद, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API का उपयोग करके, आप PPTX को OTP में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सीजीएम को ओडीपी में बदलने के लिए जावा एपीआई" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) पद्धति का उपयोग करके EPUB को PPTX में बदलें
3. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके PPTX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) विधि का उपयोग करके दस्तावेज़ को OTP प्रारूप में सहेजें और `OTP` SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) और [Aspose.Slides for Java](https://docs.aspose.com/slides/java/) शामिल करें स्थापना/) अपने pom.xml में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load EPUB file with an instance of Document class
Document document = new Document("template.epub");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
EPUB फ़ाइल स्वरूप लोड करते समय, आपका दस्तावेज़ पासवर्ड से सुरक्षित हो सकता है। [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) आपको एन्क्रिप्टेड दस्तावेज़ भी खोलने की अनुमति देता है। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) के नए इंस्टेंस को इनिशियलाइज़ कर सकते हैं .lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।  
{{% blocks/products/pf/feature-page-code %}}

```java
// open EPUB document
Document doc = new Document("input.epub", "Your@Password");
// save EPUB as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एन्क्रिप्टेड सीजीएम फ़ाइल खोलें" %}}
सीजीएम को ओडीपी में बदलने के बाद, आप अपनी प्रस्तुति के लिए पूर्वनिर्धारित दृश्य प्रकार भी जोड़ सकते हैं। [Aspose.Slides for Java](https://products.aspose.com/slides/java/) पावरपॉइंट में [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties) वर्ग। [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) प्रॉपर्टी का इस्तेमाल [ViewType](https:/) का इस्तेमाल करके व्यू टाइप सेट करने के लिए किया जाता है /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) एन्यूमरेटर। 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}