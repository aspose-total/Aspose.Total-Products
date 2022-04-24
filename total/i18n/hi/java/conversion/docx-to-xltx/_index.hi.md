---
title: डीओसी को सीएसवी में बदलने के लिए जावा एपीआई
description: माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना जावा के माध्यम से डीओसी को सीएसवी में कनवर्ट करें
url: /hi/java/conversion/docx-to-xltx/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: XLTX
otherformats: XLTX SXC XLT XLSM XLSB XLTX XLS EXCEL TSV ODS XLAM XLTM FODS DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOCX को XLTX में बदलें" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOCX को XLTX में कनवर्ट करने के लिए Premise Java API पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) के माध्यम से DOCX को XLTX में कनवर्ट करना एक आसान दो चरणों वाली प्रक्रिया है। सुविधा संपन्न, दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके, आप HTML को DOCX निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप HTML को XLTX में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" %}}
1. [दस्तावेज़](https://apireference.aspose.com/words/java/com.aspose.words/Docxument) वर्ग का उपयोग करके DOCX फ़ाइल खोलें
2. [Save](https://apireference.aspose.com/words/java/com.aspose.words/Docxument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOCX को HTML में बदलें ) तरीका
3. [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. दस्तावेज़ को [Save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) का उपयोग करके XLTX प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [Aspose.Words for Java](https://docxs.aspose.com/words/java/installation/) और [Aspose.Cells for Java](https://docxs.aspose.com/cells/java/) शामिल करें स्थापना/) अपने pom.xml में।

वैकल्पिक रूप से, आप [डाउनलोड] (https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
DOCX को XLTX में बदलने से पहले, आप [Aspose.Words for Java](https://products.aspose.com/words/java/) के माध्यम से DOCX दस्तावेज़ से अप्रयुक्त जानकारी निकाल सकते हैं। कभी-कभी आपको आउटपुट दस्तावेज़ के आकार और प्रसंस्करण समय को कम करने के लिए अप्रयुक्त या डुप्लिकेट जानकारी को हटाने की आवश्यकता हो सकती है। [CleanupOptions](https://apireference.aspose.com/words/java/com.aspose.words/CleanupOptions) वर्ग आपको दस्तावेज़ की सफाई के लिए विकल्प निर्दिष्ट करने की अनुमति देता है। दस्तावेज़ से डुप्लिकेट शैलियों या केवल अप्रयुक्त शैलियों या सूचियों को निकालने के लिए, आप [क्लीनअप](https://apireference.aspose.com/words/java/com.aspose.words/Docxument#cleanup()) विधि का उपयोग कर सकते हैं। आप [UnusedStyles](https://apireference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) और [UnusedBuiltinStyles](https://apireference.aspose.com/words/java) का इस्तेमाल कर सकते हैं /com.aspose.words/cleanupoptions#UnusedBuiltinStyles) गुणों का पता लगाने और "अप्रयुक्त" के रूप में चिह्नित शैलियों को हटाने के लिए।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एक DOCX दस्तावेज़ से अप्रयुक्त जानकारी निकालें" %}}
DOCX को XLTX में बदलने के बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) आपको अपने दस्तावेज़ को स्ट्रीम में सहेजने में सक्षम बनाता है। यदि आपको फ़ाइलों को स्ट्रीम में सहेजने की आवश्यकता है तो आपको एक FileOutputStream ऑब्जेक्ट बनाना चाहिए और फिर [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io. OutputStream,%20com.aspose.cells.SaveOptions)) [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) की सेव मेथड को कॉल करके उस स्ट्रीम ऑब्जेक्ट में फाइल करें। वस्तु। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xlsm/" name="DOCX सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xlt/" name="DOCX सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-ods/" name="DOCX सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-tsv/" name="DOCX सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xls/" name="DOCX सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xlsb/" name="DOCX सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-fods/" name="DOCX सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-dif/" name="DOCX सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xltx/" name="DOCX सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xlam/" name="DOCX सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xlsx/" name="DOCX सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-xltm/" name="DOCX सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-sxc/" name="DOCX सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/docx-to-excel/" name="DOCX सेवा EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}