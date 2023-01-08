---
title: पायथन का उपयोग करके बीएमपी को जीआईएफ में बदलें
description: Microsoft Office का उपयोग किए बिना आपके Python अनुप्रयोगों में XLSM से ODT रूपांतरण 

family: total
platformtag: Python
feature: conversion
informat: XLSM
outformat: ODT
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन के माध्यम से बीएमपी को जीआईएफ में बदलें" h2="Microsoft Excel<sup>&reg;</sup> या Word इंस्टॉल किए बिना आपके Python एप्लिकेशन में XLSM से ODT रूपांतरण" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक पायथन डेवलपर के लिए, जो एप्लिकेशन के भीतर जीआईएफ रूपांतरण सुविधा में बीएमपी जोड़ने की कोशिश कर रहा है। [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API रूपांतरण प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह बीएमपी और जीआईएफ फाइलों सहित विभिन्न प्रारूपों से निपटने वाले विभिन्न एपीआई का एक पूरा पैकेज है।

यह मुख्यतः दो चरणों में होता है। XLSM फ़ाइल को HTML में बदलने के लिए सबसे पहले [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API का उपयोग करें। उसके बाद Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) का उपयोग करके बनाए गए HTML को वांछित Microsoft Word स्वरूप में सहेजें। 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पायथन में बीएमपी को जीआईएफ में कैसे बदलें" %}}
- **स्टेप 1** Workbook वर्ग का उपयोग करके स्रोत XLSM फ़ाइल खोलें
- फ़ाइल नाम और वांछित निर्देशिका पथ प्रदान करके save(file, SaveFormat.HTML) विधि का उपयोग करके XLSM फ़ाइल को HTML में सहेजें
-  **चरण दो** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) वर्ग के उदाहरण के साथ HTML फ़ाइल लोड करें
-  आउटपुट जीआईएफ फ़ाइल पथ निर्दिष्ट करते समय `सेव` विधि को कॉल करें। तो आपकी बीएमपी फाइल निर्दिष्ट पथ पर जीआईएफ में परिवर्तित हो जाती है

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

- बीएमपी से जीआईएफ रूपांतरण के लिए, पायथन 3.5 या बाद के संस्करण की आवश्यकता है
- PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) और [Aspose.Words](https://pypi.org/project/aspose-words/)) से सीधे परियोजना के भीतर संदर्भ API
-  या निम्न पिप कमांड का उपयोग करें ``` पिप असोस-सेल्स-पायथन स्थापित करें``` और ``` पिप इंस्टाल aspose.words```
-  इसके अलावा, Microsoft Windows या Linux आधारित OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) और [Words](https://docs.aspose.com/words/python-net/system-requirements/) के लिए और देखें) और Linux के लिए gcc और libpython के लिए अतिरिक्त आवश्यकताओं की जाँच करें और [चरण दर चरण निर्देश](https://docs.aspose.com/words/python-net/installation/) का पालन करें
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLSM को HTML में Python में सहेजें - चरण 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="पायथन में HTML को ODT में सहेजें - चरण 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-word/" name="XLSM सेवा WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-doc/" name="XLSM सेवा DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-docx/" name="XLSM सेवा DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-docm/" name="XLSM सेवा DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-dot/" name="XLSM सेवा DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-dotm/" name="XLSM सेवा DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-dotx/" name="XLSM सेवा DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-mobi/" name="XLSM सेवा MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-odt/" name="XLSM सेवा ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-ott/" name="XLSM सेवा OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-rtf/" name="XLSM सेवा RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xlsm-to-wordml/" name="XLSM सेवा WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}