---
title: DOT को XLTM में बदलने के लिए Android API
description: माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना जावा के माध्यम से एंड्रॉइड में डीओसी को सीएसवी में कनवर्ट करें
url: /hi/android-java/conversion/dot-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: XLTM
otherformats: FODS TSV XLAM CSV XLSB XLS XLSX SXC EXCEL DIF XLT ODS XLTX XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Android एप्लिकेशन में DOT को XLTM में बदलें" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना जावा के द्वारा Android में DOT को XLTM में निर्यात करें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) का उपयोग करके आप अपने Android एप्लिकेशन के अंदर DOT को XLTM रूपांतरण सुविधा में एकीकृत कर सकते हैं। सबसे पहले, आप सुविधा संपन्न, दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) का उपयोग करके DOT को HTML में बदल सकते हैं। उसके बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/android-java/) का उपयोग करके, आप HTML को XLTM में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT को XLTM में बदलने के लिए Android API" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Dotument) वर्ग का उपयोग करके DOT फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOT को HTML में बदलें ) तरीका
3. [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) का उपयोग करके दस्तावेज़ को XLTM प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) से सीधे Aspose.Total for Android via Java का आसानी से उपयोग कर सकते हैं और इंस्टॉल करें [Aspose.Cells for Android via Java](https://dots.aspose.com/cells/java/aspose-cells-for-android-via-java-installation/#install-asposecells-for-android-via- java-from-maven-repository) और [Aspose.Words for Android via Java](https://dots.aspose.com/words/java/install-aspose-words-for-android-via-java/#install- asposewords-for-android-via-java-from-maven-repository) आपके अनुप्रयोगों में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/androidjava) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में एक DOT दस्तावेज़ से अप्रयुक्त जानकारी निकालें" %}}
DOT को XLTM में बदलने से पहले, आप [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) के माध्यम से DOT दस्तावेज़ से अप्रयुक्त जानकारी निकाल सकते हैं। कभी-कभी आपको आउटपुट दस्तावेज़ के आकार और प्रसंस्करण समय को कम करने के लिए अप्रयुक्त या डुप्लिकेट जानकारी को हटाने की आवश्यकता हो सकती है। [क्लीनअपऑप्शन](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) वर्ग आपको दस्तावेज़ की सफाई के लिए विकल्प निर्दिष्ट करने की अनुमति देता है। दस्तावेज़ से डुप्लिकेट शैलियों या केवल अप्रयुक्त शैलियों या सूचियों को निकालने के लिए, आप [क्लीनअप](https://reference.aspose.com/words/java/com.aspose.words/Dotument#cleanup()) पद्धति का उपयोग कर सकते हैं। आप [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) और [UnusedBuiltinStyles](https://reference.aspose.com/words/java) का उपयोग कर सकते हैं /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) गुणों का पता लगाने और "अप्रयुक्त" के रूप में चिह्नित शैलियों को हटाने के लिए।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "remove-unused-information-from-word-dotument.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से Android में स्ट्रीम करने के लिए XLTM फ़ाइल सहेजें" %}}
DOT को XLTM में बदलने के बाद, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) आपको अपने दस्तावेज़ को स्ट्रीम करने के लिए सहेजने में सक्षम बनाता है। यदि आपको फ़ाइलों को स्ट्रीम में सहेजने की आवश्यकता है, तो आपको एक FileOutputStream ऑब्जेक्ट बनाना चाहिए और फिर [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream,%20com.aspose.cells.SaveOptions)) [वर्कबुक](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) की सेव मेथड को कॉल करके उस स्ट्रीम ऑब्जेक्ट में फाइल करें। वस्तु।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "save-excel-to-stream.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-fods/" name="DOT प्रति FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-tsv/" name="DOT प्रति TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xlam/" name="DOT प्रति XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xltm/" name="DOT प्रति XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xlsb/" name="DOT प्रति XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xls/" name="DOT प्रति XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xlsx/" name="DOT प्रति XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-sxc/" name="DOT प्रति SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-excel/" name="DOT प्रति EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-dif/" name="DOT प्रति DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xlt/" name="DOT प्रति XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-ods/" name="DOT प्रति ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xltx/" name="DOT प्रति XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/android-java/conversion/dot-to-xlsm/" name="DOT प्रति XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}