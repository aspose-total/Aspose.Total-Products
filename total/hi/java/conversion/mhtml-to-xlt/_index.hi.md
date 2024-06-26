---
title: सीएसवी को सीजीएम प्रस्तुत करने के लिए जावा एपीआई
description: माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना जावा एपीआई के माध्यम से सीएसवी को सीजीएम निर्यात करें
url_ignore: /hi/java/conversion/mhtml-to-xlt/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: XLT
otherformats: DIF MD EXCEL ODS XLT FODS XLAM XLSB SXC XLTM TXT TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="जावा के माध्यम से सीजीएम को सीएसवी में निर्यात करें" h2="किसी भी जावा J2SE, J2EE, J2ME अनुप्रयोगों में ऑन-प्रिमाइसेस Java API का उपयोग करके MHTML फ़ाइल को XLT में बदलें" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) का उपयोग करके आप दो चरणों वाली प्रक्रिया में अपने जावा एप्लिकेशन में MHTML को XLT रूपांतरण सुविधा में एकीकृत कर सकते हैं। सबसे पहले, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) का उपयोग करके आप XLSX को MHTML रेंडर कर सकते हैं। दूसरे चरण में, आप स्प्रेडशीट प्रोग्रामिंग API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) का उपयोग करके XLSX को XLT में बदल सकते हैं।
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="जावा के माध्यम से सीजीएम फ़ाइल को सीएसवी में कनवर्ट करें" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) वर्ग का उपयोग करके सीजीएम फ़ाइल खोलें
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- का उपयोग करके MHTML को XLSX में बदलें। ) तरीका
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) क्लास का इस्तेमाल करके XLSX दस्तावेज़ लोड करें
4. [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells)) का उपयोग करके दस्तावेज़ को XLT प्रारूप में सहेजें। SaveOptions)) विधि
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
आप [Maven](https://releases.aspose.com/total/java/) आधारित प्रोजेक्ट से सीधे Java के लिए Aspose.Total का आसानी से उपयोग कर सकते हैं और [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) और [Aspose.Cells for Java](https://docs.aspose.com/cells/java/) शामिल करें स्थापना/) अपने pom.xml में।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="रूपांतरण आवश्यकताएँ" %}}
यदि आपका सीजीएम दस्तावेज़ पासवर्ड से सुरक्षित है, तो आप इसे पासवर्ड के बिना सीएसवी में परिवर्तित नहीं कर सकते। एपीआई का उपयोग करके, आप पहले एक वैध पासवर्ड का उपयोग करके संरक्षित दस्तावेज़ को खोल सकते हैं और उसके बाद उसे परिवर्तित कर सकते हैं। एन्क्रिप्ट की गई फ़ाइल को खोलने के लिए, आप [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String- का एक नया उदाहरण प्रारंभ कर सकते हैं) java.lang.String-) वर्ग और तर्क के रूप में फ़ाइल नाम और पासवर्ड पास करें।  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="जावा के माध्यम से संरक्षित सीजीएम को सीएसवी में कनवर्ट करें" %}}
MHTML फ़ाइल को XLT में कनवर्ट करते समय, आप अपने आउटपुट XLT फ़ाइल स्वरूप में वॉटरमार्क भी जोड़ सकते हैं। वॉटरमार्क जोड़ने के लिए, परिवर्तित XLSX फ़ाइल को खोलने के लिए एक नई कार्यपुस्तिका बनाएँ। इसकी अनुक्रमणिका के माध्यम से वर्कशीट का चयन करें, एक आकृति बनाएं और इसके addTextEffect फ़ंक्शन का उपयोग करें, रंग, पारदर्शिता और बहुत कुछ सेट करें। उसके बाद आप अपने XLSX दस्तावेज़ को वॉटरमार्क के साथ XLT के रूप में सहेज सकते हैं। 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}