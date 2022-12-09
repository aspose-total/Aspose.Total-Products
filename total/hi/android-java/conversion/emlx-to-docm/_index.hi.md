---
title: Andorid ऐप में DOCM को EMLX रेंडर करें
description: आप Andorid अनुप्रयोगों में Microsoft Word या Outlook का उपयोग किए बिना EMLX को DOCM में निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOCM
otherformats: EMF BMP XPS ODT DOCX SVG JPEG DOT PS PNG DOTM FLATOPC RTF DOTX DOC EPUB PCL MD TIFF PDF TEXT WORDML OTT GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid ऐप्स में EMLX को DOCM में बदलें" h2="जावा एपीआई के माध्यम से Andorid का उपयोग करके DOCM को EMLX निर्यात करने के लिए Andorid अनुप्रयोगों को तैयार करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid ऐप्स दैनिक आधार पर अंतिम उपयोगकर्ताओं के लिए उपयोग करना आसान है। दिन पर दिन Andorid फोन यूजर्स की संख्या बढ़ती जा रही है। शक्तिशाली [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) फ़ाइल फ़ॉर्मेट ऑटोमेशन लाइब्रेरी का उपयोग करके आप ईमेल हेरफेर और रूपांतरण एप्लिकेशन विकसित कर सकते हैं। आप [एंड्रॉइड जावा के लिए Aspose.Emlx](https://products.aspose.com/emlx/android-java/) और [Aspose.Words for Andorid Java](https:// के संयोजन से EMLX को DOCM में बदल सकते हैं) products.aspose.com/words/android-java/)। पहले API का उपयोग करके आप EMLX फ़ाइल स्वरूप को HTML में बदल सकते हैं और दूसरे API का उपयोग करके, आप HTML को DOCM के रूप में प्रस्तुत कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid में EMLX को DOCM में बदलें" %}}
1. [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage) वर्ग का उपयोग करके EMLX फ़ाइल खोलें
2. [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions) का उपयोग करके EMLX को HTML में बदलें )) तरीका
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) का उपयोग करके दस्तावेज़ को DOCM प्रारूप में सहेजें )) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [जावा के माध्यम से Android के लिए Aspose.Emlx](https://docs.aspose.com/emlx/androidjava/installation/) और [Aspose.Words for Andorid by Java](https://docs.aspose.com/words) इंस्टॉल करें /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCM
document.save("output.docm", SaveFormat.DOCM); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-emf/" name="EMLX प्रति EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-docm/" name="EMLX प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-xps/" name="EMLX प्रति XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-odt/" name="EMLX प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-docx/" name="EMLX प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-svg/" name="EMLX प्रति SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-jpeg/" name="EMLX प्रति JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-dot/" name="EMLX प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-ps/" name="EMLX प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-png/" name="EMLX प्रति PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-dotm/" name="EMLX प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-flatopc/" name="EMLX प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-rtf/" name="EMLX प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-dotx/" name="EMLX प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-doc/" name="EMLX प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-epub/" name="EMLX प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-pcl/" name="EMLX प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-md/" name="EMLX प्रति MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-tiff/" name="EMLX प्रति TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-pdf/" name="EMLX प्रति PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-text/" name="EMLX प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-wordml/" name="EMLX प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-ott/" name="EMLX प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/emlx-to-gif/" name="EMLX प्रति GIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}