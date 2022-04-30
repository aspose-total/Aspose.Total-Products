---
title: सीएसवी को सीजीएम प्रस्तुत करने के लिए जावा एपीआई
description: माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना जावा एपीआई के माध्यम से सीएसवी को सीजीएम निर्यात करें
url: /hi/java/conversion/epub-to-dif/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: DIF
otherformats: XLAM XLSB TSV SXC DIF XLT XLTM ODS XLTX FODS TXT MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से सीजीएम को सीएसवी में निर्यात करें" h2="किसी भी जावा J2SE, J2EE, J2ME अनुप्रयोगों में ऑन-प्रिमाइसेस Java API का उपयोग करके EPUB फ़ाइल को DIF में बदलें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप दो चरणों वाली प्रक्रिया में अपने जावा एप्लिकेशन में EPUB को DIF रूपांतरण सुविधा में एकीकृत कर सकते हैं। सबसे पहले, [जावा के लिए Aspose.PDF](https://products.aspose.com/pdf/java/) का उपयोग करके आप XLSX को EPUB रेंडर कर सकते हैं। दूसरे चरण में, आप स्प्रेडशीट प्रोग्रामिंग API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके XLSX को DIF में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से सीजीएम फ़ाइल को सीएसवी में कनवर्ट करें" %}}
1. [दस्तावेज़](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- का उपयोग करके EPUB को XLSX में बदलें। ) तरीका
3. [वर्कबुक](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके XLSX दस्तावेज़ लोड करें
4. [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells) का उपयोग करके दस्तावेज़ को DIF प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [जावा के लिए Aspose.PDF](https://docs.aspose.com/pdf/java/installation/) और [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) शामिल करें स्थापना/) अपने pom.xml में।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
यदि आपका सीजीएम दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप इसे पासवर्ड के बिना सीएसवी में परिवर्तित नहीं कर सकते। एपीआई का उपयोग करके, आप पहले एक वैध पासवर्ड का उपयोग करके संरक्षित दस्तावेज़ को खोल सकते हैं और उसके बाद उसे परिवर्तित कर सकते हैं। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [दस्तावेज़](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- का एक नया उदाहरण प्रारंभ कर सकते हैं) java.lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से संरक्षित सीजीएम को सीएसवी में कनवर्ट करें" %}}
EPUB फ़ाइल को DIF में कनवर्ट करते समय, आप अपने आउटपुट DIF फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, परिवर्तित XLSX फ़ाइल को खोलने के लिए एक नई कार्यपुस्तिका बनाएँ। इसकी अनुक्रमणिका के माध्यम से वर्कशीट का चयन करें, एक आकृति बनाएं और इसके addTextEffect फ़ंक्शन का उपयोग करें, रंग, पारदर्शिता और बहुत कुछ सेट करें। उसके बाद आप अपने XLSX दस्तावेज़ को वॉटरमार्क के साथ DIF के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-dif/" name="EPUB सेवा DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xltx/" name="EPUB सेवा XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-md/" name="EPUB सेवा MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-fods/" name="EPUB सेवा FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xltm/" name="EPUB सेवा XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-excel/" name="EPUB सेवा EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xlsm/" name="EPUB सेवा XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xlam/" name="EPUB सेवा XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xlt/" name="EPUB सेवा XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-xlsb/" name="EPUB सेवा XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-ods/" name="EPUB सेवा ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/epub-to-sxc/" name="EPUB सेवा SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}