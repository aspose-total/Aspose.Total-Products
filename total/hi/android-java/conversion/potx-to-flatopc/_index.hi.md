---
title: जावा के माध्यम से Andorid पर FLATOPC को POTX निर्यात करें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: बिना किसी सॉफ्टवेयर को इंस्टॉल किए मोबाइल ऐप्स में POTX को FLATOPC में बदलें या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।

family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: FLATOPC
otherformats: ODT TEXT WORDML DOCX DOTM DOC DOT RTF WORD DOCM OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="जावा के माध्यम से एंडोरिड पर पीओटी को डीओसी को प्रस्तुत करना या ऑनलाइन" h2="Microsoft PowerPoint या Word पर निर्भर किए बिना Android ऐप्स के भीतर POTX को FLATOPC में बदलने के लिए फ़ाइल स्वरूप API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) Android ऐप्लिकेशन के भीतर फ़ाइल स्वरूपों में हेरफेर करने की अनुमति देता है। पैकेज में दिए गए API का उपयोग करके आप अपने ऐप्स में PowerPoint POTX से Word FLATOPC रूपांतरण प्रक्रिया को स्वचालित कर सकते हैं।
आप अपने दिए गए दस्तावेज़ को दो चरणों में बदल सकते हैं। आप [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) का उपयोग कर सकते हैं जो कि HTML को POTX रेंडर करने के लिए Android एप्लिकेशन के लिए एक PowerPoint API है। उसके बाद दस्तावेज़ संसाधन API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके आप HTML को FLATOPC में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android में POTX से FLATOPC रेंडरिंग" %}}
1. [प्रस्तुति](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) वर्ग का उपयोग करके POTX फ़ाइल खोलें
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)  का उपयोग करके POTX को HTML में बदलें।ISaveOptions-) विधि और HTML को SaveFormat के रूप में सेट करें
3. परिवर्तित HTML फ़ाइल को [Document](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument) वर्ग का उपयोग करके लोड करें
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int)) विधि का उपयोग करके दस्तावेज़ को FLATOPC प्रारूप में सहेजें और Flatopc सेट करें SaveFormat के रूप में
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और स्थापित करें [Aspose.Slides for Android via Java](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) और [Aspose.Words for Andorid by Java](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) आपके अनुप्रयोग।

वैकल्पिक रूप से, आप [डाउनलोड](https://releases.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>बीएमपी से जीआईएफ के लिए मुफ्त ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=flatopc&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-odt/" name="POTX प्रति ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-text/" name="POTX प्रति TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-wordml/" name="POTX प्रति WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-flatopcx/" name="POTX प्रति FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotm/" name="POTX प्रति DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-flatopc/" name="POTX प्रति FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dot/" name="POTX प्रति DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-rtf/" name="POTX प्रति RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-word/" name="POTX प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-flatopcm/" name="POTX प्रति FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-ott/" name="POTX प्रति OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/potx-to-dotx/" name="POTX प्रति DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}