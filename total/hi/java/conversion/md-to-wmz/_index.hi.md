---
title: जावा के माध्यम से सीजीएम को एपीएनजी में कनवर्ट करें
description: किसी भी तृतीय पक्ष एप्लिकेशन का उपयोग किए बिना अपने जावा एप्लिकेशन में MD फ़ाइल को WMZ में निर्यात करें
url_ignore: /hi/java/conversion/md-to-wmz/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: WMZ
otherformats: IMAGE  JPEG2000 TGA WMZ SVGZ PSD DXF WMF EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से सीजीएम को एपीएनजी में कनवर्ट करें" h2="Adobe<sup>&reg;</sup> Acrobat Reader का उपयोग किए बिना किसी भी Java J2SE, J2EE, J2ME एप्लिकेशन के भीतर WMZ को MD फ़ाइल निर्यात करें" >}}
{{% blocks/products/pf/feature-page-summary %}}
आप जावा में सीजीएम फ़ाइल को एपीएनजी छवि में दो सरल चरणों में परिवर्तित कर सकते हैं। सबसे पहले, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) का उपयोग करके, आप JPEG को MD निर्यात कर सकते हैं। उसके बाद, [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) इमेज प्रोसेसिंग API का उपयोग करके, आप WMZ को JPEG रेंडर कर सकते हैं। दोनों एपीआई [Aspose.Total for Java](https://products.aspose.com/total/java/) पैकेज के तहत आते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से एपीएनजी को सीजीएम निर्यात करें" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. क्लास ऑब्जेक्ट को इनिशियलाइज़ करें और [Process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com) का उपयोग करके JPEG को MD रेंडर करें। aspose.pdf.Page-java.io.OutputStream-) विधि
3. [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) क्लास का इस्तेमाल करके JPEG फ़ाइल लोड करें
4. [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase का उपयोग करके दस्तावेज़ को WMZ प्रारूप में सहेजें-) तरीका
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और अपने pom.xml में पुस्तकालयों को शामिल करें।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एक ही फाइल में सीजीएम को एपीएनजी में कनवर्ट करें" %}}
एपीआई आपको सीजीएम फ़ाइल को एपीएनजी को एक फ़ाइल में निर्यात करने की भी अनुमति देता है। सभी पृष्ठों को बदलने के लिए, आप पहले अपने सीजीएम दस्तावेज़ को एक टीआईएफएफ फ़ाइल में प्रस्तुत कर सकते हैं और उसके बाद, आप टीआईएफएफ फ़ाइल को एपीएनजी में निर्यात कर सकते हैं। आप [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके इनपुट फ़ाइल खोल सकते हैं और रिज़ॉल्यूशन, टिफ़सेटिंग और टीआईएफएफ डिवाइस ऑब्जेक्ट बना सकते हैं। आप [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice) वर्ग की विधि। अंत में, आप [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) वर्ग का उपयोग करके TIFF फ़ाइल लोड कर सकते हैं और [save](https://) का उपयोग करके इसे WMZ प्रारूप में सहेज सकते हैं। apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) विधि।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से वॉटरमार्क के साथ सीजीएम को एपीएनजी में कनवर्ट करें" %}}
एपीआई का उपयोग करके, आप अपने एपीएनजी दस्तावेज़ में वॉटरमार्क के साथ एपीएनजी को सीजीएम फ़ाइल भी निर्यात कर सकते हैं। वॉटरमार्क जोड़ने के लिए आप पहले सीजीएम को जेपीईजी में बदल सकते हैं और उसमें वॉटरमार्क जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) क्लास का इस्तेमाल करके इमेज फ़ाइल लोड करें, [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) क्लास और इमेज ऑब्जेक्ट के साथ इसे इनिशियलाइज़ करें, एक नया बनाएं [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) ऑब्जेक्ट और अनुवाद और रूपांतरण को वांछित कोण पर सेट करें और [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics.drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-) विधि। अपनी छवि में वॉटरमार्क जोड़ने के बाद, आप JPEG को WMZ प्रारूप के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से सीजीएम को एपीएनजी फ़ाइल में कनवर्ट और घुमाएं" %}}
एपीआई का उपयोग करके, आप अपनी आवश्यकताओं के अनुसार आउटपुट एपीएनजी छवि को घुमा भी सकते हैं। Image.rotateFlip विधि का उपयोग छवि को 90/180/270-डिग्री तक घुमाने और छवि को क्षैतिज या लंबवत रूप से फ़्लिप करने के लिए किया जा सकता है। पुस्तकालय सभी बदसूरत विवरणों को समाहित करते हुए जटिल संचालन करने के लिए सरल तरीके प्रदान करता है। आप रोटेशन के प्रकार को निर्दिष्ट कर सकते हैं और छवि पर लागू करने के लिए फ्लिप कर सकते हैं। छवि को घुमाने और फ़्लिप करने के लिए, आप [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) वर्ग का उपयोग करके परिवर्तित JPEG छवि को लोड कर सकते हैं और छवि को कॉल कर सकते हैं। उपयुक्त [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType) निर्दिष्ट करते हुए रोटेटफ्लिप विधि। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}