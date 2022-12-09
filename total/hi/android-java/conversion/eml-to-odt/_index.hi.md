---
title: Andorid ऐप में ODT को EML रेंडर करें
description: आप Andorid अनुप्रयोगों में Microsoft Word या Outlook का उपयोग किए बिना EML को ODT में निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: ODT
otherformats: DOT EMF PS WORDML FLATOPC RTF TIFF BMP MD DOCX OTT EPUB SVG DOCM GIF PCL DOTM JPEG DOC PNG DOTX XPS TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid ऐप्स में EML को ODT में बदलें" h2="जावा एपीआई के माध्यम से Andorid का उपयोग करके ODT को EML निर्यात करने के लिए Andorid अनुप्रयोगों को तैयार करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid ऐप्स दैनिक आधार पर अंतिम उपयोगकर्ताओं के लिए उपयोग करना आसान है। दिन पर दिन Andorid फोन यूजर्स की संख्या बढ़ती जा रही है। शक्तिशाली [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) फ़ाइल फ़ॉर्मेट ऑटोमेशन लाइब्रेरी का उपयोग करके आप ईमेल हेरफेर और रूपांतरण एप्लिकेशन विकसित कर सकते हैं। आप [एंड्रॉइड जावा के लिए Aspose.Eml](https://products.aspose.com/eml/android-java/) और [Aspose.Words for Andorid Java](https:// के संयोजन से EML को ODT में बदल सकते हैं) products.aspose.com/words/android-java/)। पहले API का उपयोग करके आप EML फ़ाइल स्वरूप को HTML में बदल सकते हैं और दूसरे API का उपयोग करके, आप HTML को ODT के रूप में प्रस्तुत कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid में EML को ODT में बदलें" %}}
1. [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage) वर्ग का उपयोग करके EML फ़ाइल खोलें
2. [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions) का उपयोग करके EML को HTML में बदलें )) तरीका
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) का उपयोग करके दस्तावेज़ को ODT प्रारूप में सहेजें )) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [जावा के माध्यम से Android के लिए Aspose.Eml](https://docs.aspose.com/eml/androidjava/installation/) और [Aspose.Words for Andorid by Java](https://docs.aspose.com/words) इंस्टॉल करें /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-dot/" name="EML प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-emf/" name="EML प्रति EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-ps/" name="EML प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-wordml/" name="EML प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-flatopc/" name="EML प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-rtf/" name="EML प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-tiff/" name="EML प्रति TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-odt/" name="EML प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-md/" name="EML प्रति MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-docx/" name="EML प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-ott/" name="EML प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-epub/" name="EML प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-svg/" name="EML प्रति SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-docm/" name="EML प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-gif/" name="EML प्रति GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-pcl/" name="EML प्रति PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-dotm/" name="EML प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-jpeg/" name="EML प्रति JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-doc/" name="EML प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-png/" name="EML प्रति PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-dotx/" name="EML प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-xps/" name="EML प्रति XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-text/" name="EML प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/eml-to-pdf/" name="EML प्रति PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}