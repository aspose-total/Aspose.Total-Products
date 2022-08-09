---
title: Andorid ऐप में XPS को MSG रेंडर करें
description: आप Andorid अनुप्रयोगों में Microsoft Word या Outlook का उपयोग किए बिना MSG को XPS में निर्यात करें
url: /hi/android-java/conversion/msg-to-xps/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: XPS
otherformats: EPUB DOT BMP DOC PDF DOTM ODT OTT MD DOTX RTF DOCM PNG EMF WORDML JPEG GIF TIFF SVG TEXT FLATOPC DOCX PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid ऐप्स में MSG को XPS में बदलें" h2="जावा एपीआई के माध्यम से Andorid का उपयोग करके XPS को MSG निर्यात करने के लिए Andorid अनुप्रयोगों को तैयार करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid ऐप्स दैनिक आधार पर अंतिम उपयोगकर्ताओं के लिए उपयोग करना आसान है। दिन पर दिन Andorid फोन यूजर्स की संख्या बढ़ती जा रही है। शक्तिशाली [Aspose.Total for Android by Java](https://products.aspose.com/total/android-java/) फ़ाइल फ़ॉर्मेट ऑटोमेशन लाइब्रेरी का उपयोग करके आप ईमेल हेरफेर और रूपांतरण एप्लिकेशन विकसित कर सकते हैं। आप [एंड्रॉइड जावा के लिए Aspose.Msg](https://products.aspose.com/msg/android-java/) और [Aspose.Words for Andorid Java](https:// के संयोजन से MSG को XPS में बदल सकते हैं) products.aspose.com/words/android-java/)। पहले API का उपयोग करके आप MSG फ़ाइल स्वरूप को HTML में बदल सकते हैं और दूसरे API का उपयोग करके, आप HTML को XPS के रूप में प्रस्तुत कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid में MSG को XPS में बदलें" %}}
1. [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage) वर्ग का उपयोग करके MSG फ़ाइल खोलें
2. [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions) का उपयोग करके MSG को HTML में बदलें )) तरीका
3. [दस्तावेज़](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) का उपयोग करके दस्तावेज़ को XPS प्रारूप में सहेजें )) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे जावा के माध्यम से Android के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [जावा के माध्यम से Android के लिए Aspose.Msg](https://docs.aspose.com/msg/androidjava/installation/) और [Aspose.Words for Andorid by Java](https://docs.aspose.com/words) इंस्टॉल करें /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.XPS
document.save("output.xps", SaveFormat.XPS); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-epub/" name="MSG प्रति EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-dot/" name="MSG प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-xps/" name="MSG प्रति XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-doc/" name="MSG प्रति DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-pdf/" name="MSG प्रति PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-dotm/" name="MSG प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-odt/" name="MSG प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-ott/" name="MSG प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-md/" name="MSG प्रति MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-dotx/" name="MSG प्रति DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-rtf/" name="MSG प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-docm/" name="MSG प्रति DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-png/" name="MSG प्रति PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-emf/" name="MSG प्रति EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-wordml/" name="MSG प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-jpeg/" name="MSG प्रति JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-gif/" name="MSG प्रति GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-tiff/" name="MSG प्रति TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-svg/" name="MSG प्रति SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-text/" name="MSG प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-flatopc/" name="MSG प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-docx/" name="MSG प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-ps/" name="MSG प्रति PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/msg-to-pcl/" name="MSG प्रति PCL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}