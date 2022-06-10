---
title: डीओसी को सीएसवी में बदलने के लिए जावा एपीआई
description: माइक्रोसॉफ्ट वर्ड या माइक्रोसॉफ्ट एक्सेल का उपयोग किए बिना जावा के माध्यम से डीओसी को सीएसवी में कनवर्ट करें
url_ignore: /hi/java/conversion/dotm-to-xlsm/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: XLSM
otherformats: TSV XLAM SXC XLSM EXCEL ODS FODS XLSM XLTX XLS XLSX DIF XLSB XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से DOTM को XLSM में बदलें" h2="Microsoft<sup>&reg;</sup> Word या Microsoft<sup>&reg;</sup> Excel का उपयोग किए बिना DOTM को XLSM में कनवर्ट करने के लिए Premise Java API पर" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) के माध्यम से DOTM को XLSM में कनवर्ट करना एक आसान दो चरणों वाली प्रक्रिया है। सुविधा संपन्न, दस्तावेज़ हेरफेर और रूपांतरण API [Aspose.Words for Java](https://products.aspose.com/words/java/) का उपयोग करके, आप HTML को DOTM निर्यात कर सकते हैं। उसके बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके, आप HTML को XLSM में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई डीओसी को सीएसवी में कनवर्ट करने के लिए" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Dotmument) वर्ग का उपयोग करके DOTM फ़ाइल खोलें
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions) का उपयोग करके DOTM को HTML में बदलें ) तरीका
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके एचटीएमएल दस्तावेज़ लोड करें
4. दस्तावेज़ को [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [Aspose.Words for Java](https://dotms.aspose.com/words/java/installation/) और [Aspose.Cells for Java](https://dotms.aspose.com/cells/java/) शामिल करें स्थापना/) अपने pom.xml में।

वैकल्पिक रूप से, आप [डाउनलोड](https://downloads.aspose.com/total/java) से एक ज़िप फ़ाइल प्राप्त कर सकते हैं।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
DOTM को XLSM में बदलने से पहले, आप [Aspose.Words for Java](https://products.aspose.com/words/java/) के माध्यम से DOTM दस्तावेज़ से अप्रयुक्त जानकारी निकाल सकते हैं। कभी-कभी आपको आउटपुट दस्तावेज़ के आकार और प्रसंस्करण समय को कम करने के लिए अप्रयुक्त या डुप्लिकेट जानकारी को हटाने की आवश्यकता हो सकती है। [CleanupOptions](https://reference.aspose.com/words/java/com.aspose.words/CleanupOptions) वर्ग आपको दस्तावेज़ की सफाई के लिए विकल्प निर्दिष्ट करने की अनुमति देता है। दस्तावेज़ से डुप्लिकेट शैलियों या केवल अप्रयुक्त शैलियों या सूचियों को निकालने के लिए, आप [cleanup](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#cleanup()) विधि का उपयोग कर सकते हैं। आप [UnusedStyles](https://reference.aspose.com/words/java/com.aspose.words/cleanupoptions#UnusedStyles) और [UnusedBuiltinStyles](https://reference.aspose.com/words/java) का इस्तेमाल कर सकते हैं  गुणों का पता लगाने और "अप्रयुक्त" के रूप में चिह्नित शैलियों को हटाने के लिए।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-protected-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से एक DOTM दस्तावेज़ से अप्रयुक्त जानकारी निकालें" %}}
DOTM को XLSM में बदलने के बाद, [Aspose.Cells for Java](https://products.aspose.com/cells/java/) आपको अपने दस्तावेज़ को स्ट्रीम में सहेजने में सक्षम बनाता है। यदि आपको फ़ाइलों को स्ट्रीम में सहेजने की आवश्यकता है तो आपको एक FileOutputStream ऑब्जेक्ट बनाना चाहिए और फिर [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.io.OutputStream.%20com.aspose.cells.SaveOptions)) [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) की सेव मेथड को कॉल करके उस स्ट्रीम ऑब्जेक्ट में फाइल करें। वस्तु। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-protected-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsm/" name="DOTM सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlt/" name="DOTM सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-ods/" name="DOTM सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-tsv/" name="DOTM सेवा TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xls/" name="DOTM सेवा XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsb/" name="DOTM सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-fods/" name="DOTM सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-dif/" name="DOTM सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xltx/" name="DOTM सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlam/" name="DOTM सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xlsx/" name="DOTM सेवा XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-xltm/" name="DOTM सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-sxc/" name="DOTM सेवा SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/dotm-to-excel/" name="DOTM सेवा EXCEL" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}