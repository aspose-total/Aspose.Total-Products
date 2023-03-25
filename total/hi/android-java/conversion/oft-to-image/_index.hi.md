---
title: Andorid ऐप में IMAGE को OFT रेंडर करें
description: आप Andorid अनुप्रयोगों में Microsoft Word या Outlook का उपयोग किए बिना OFT को IMAGE में निर्यात करें

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PNG
otherformats: BMP RTF OTT GIF DOCX TIFF WORDML PS DOTX DOC EMF TEXT ODT EPUB FLATOPC DOTM JPEG DOT XPS PNG PDF MD DOCM PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Andorid ऐप्स में OFT को IMAGE में बदलें" h2="जावा एपीआई के माध्यम से Andorid का उपयोग करके IMAGE को OFT निर्यात करने के लिए Andorid अनुप्रयोगों को तैयार करना" >}}

{{% blocks/products/pf/feature-page-summary %}}
Andorid ऐप्स दैनिक आधार पर अंतिम उपयोगकर्ताओं के लिए उपयोग करना आसान है। दिन पर दिन Andorid फोन यूजर्स की संख्या बढ़ती जा रही है। शक्तिशाली [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) फ़ाइल फ़ॉर्मेट ऑटोमेशन लाइब्रेरी का उपयोग करके आप ईमेल हेरफेर और रूपांतरण एप्लिकेशन विकसित कर सकते हैं। आप [एंड्रॉइड जावा के लिए Aspose.Oft](https://products.aspose.com/oft/android-java/) और [Aspose.Words for Andorid Java](https:// के संयोजन से OFT को IMAGE में बदल सकते हैं) products.aspose.com/words/android-java/)। पहले API का उपयोग करके आप OFT फ़ाइल स्वरूप को HTML में बदल सकते हैं और दूसरे API का उपयोग करके, आप HTML को IMAGE के रूप में प्रस्तुत कर सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Andorid में OFT को IMAGE में बदलें" %}}
1. [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage) वर्ग का उपयोग करके OFT फ़ाइल खोलें
2. [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions) का उपयोग करके OFT को HTML में बदलें )) तरीका
3. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) वर्ग का उपयोग करके HTML लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) का उपयोग करके दस्तावेज़ को IMAGE प्रारूप में सहेजें )) विधि और बीएमपी को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और [जावा के माध्यम से Android के लिए Aspose.Oft](https://docs.aspose.com/oft/androidjava/installation/) और [Aspose.Words for Andorid by Java](https://docs.aspose.com/words) इंस्टॉल करें /java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके एप्लिकेशन में।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}