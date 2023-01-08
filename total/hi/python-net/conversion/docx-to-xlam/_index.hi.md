---
title: पायथन का उपयोग करके बीएमपी को जीआईएफ में बदलें
description: Microsoft Word या Excel का उपयोग किए बिना आपके Python अनुप्रयोगों में DOCX से XLAM रूपांतरण 

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: XLAM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन के माध्यम से बीएमपी को जीआईएफ में बदलें" h2="Microsoft Word<sup>&reg;</sup> या Excel इंस्टॉल किए बिना आपके Python एप्लिकेशन में DOCX से XLAM रूपांतरण" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक पायथन डेवलपर के लिए, जो एप्लिकेशन के भीतर जीआईएफ रूपांतरण सुविधा में बीएमपी जोड़ने की कोशिश कर रहा है। [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API रूपांतरण प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह विभिन्न स्वरूपों से निपटने वाले विभिन्न एपीआई का एक पूरा पैकेज है।

यह मुख्यतः दो चरणों में होता है। DOCX फ़ाइल को HTML में बदलने के लिए सबसे पहले [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API का उपयोग करें। उसके बाद Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) का उपयोग करके बनाए गए HTML को वांछित Microsoft Excel स्वरूप में सहेजें। 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पायथन में बीएमपी को जीआईएफ में कैसे बदलें" %}}
- **चरण 1** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) वर्ग का उपयोग करके स्रोत DOCX फ़ाइल खोलें
- फ़ाइल नाम और वांछित निर्देशिका पथ प्रदान करके [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) विधि का उपयोग करके DOCX फ़ाइल को HTML में सहेजें
-  **चरण 2** पैरामीटर के रूप में फ़ाइल और LoadOptions के साथ कार्यपुस्तिका वर्ग के उदाहरण के साथ HTML फ़ाइल लोड करें
-  आउटपुट जीआईएफ फ़ाइल पथ निर्दिष्ट करते समय `सेव` विधि को कॉल करें। तो आपकी बीएमपी फाइल निर्दिष्ट पथ पर जीआईएफ में परिवर्तित हो जाती है

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

- बीएमपी से जीआईएफ रूपांतरण के लिए, पायथन 3.5 या बाद के संस्करण की आवश्यकता है
- PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) और [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) से सीधे परियोजना के भीतर संदर्भ API
-  या निम्नलिखित पिप कमांड का उपयोग करें ```पिप aspose.words स्थापित करें``` और ```पिप aspose-cells-python स्थापित करें``` 
-  इसके अलावा, Microsoft Windows या Linux आधारित OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) और [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) के लिए और देखें) और Linux के लिए gcc और libpython के लिए अतिरिक्त आवश्यकताओं की जाँच करें और [चरण दर चरण निर्देश](https://docs.aspose.com/words/python-net/installation/) का पालन करें
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DOCX को HTML में Python में सहेजें - चरण 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="पायथन में HTML को XLAM में सहेजें - चरण 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-excel/" name="DOCX सेवा EXCEL" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xls/" name="DOCX सेवा XLS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xlsx/" name="DOCX सेवा XLSX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-csv/" name="DOCX सेवा CSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-dif/" name="DOCX सेवा DIF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-fods/" name="DOCX सेवा FODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-ods/" name="DOCX सेवा ODS" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-sxc/" name="DOCX सेवा SXC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-tsv/" name="DOCX सेवा TSV" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xlam/" name="DOCX सेवा XLAM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xlsb/" name="DOCX सेवा XLSB" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xlt/" name="DOCX सेवा XLT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xltm/" name="DOCX सेवा XLTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xltx/" name="DOCX सेवा XLTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/docx-to-xlsm/" name="DOCX सेवा XLSM" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}