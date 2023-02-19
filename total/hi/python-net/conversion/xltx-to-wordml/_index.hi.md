---
title: पायथन का उपयोग करके बीएमपी को जीआईएफ में बदलें
description: Microsoft Office का उपयोग किए बिना आपके Python अनुप्रयोगों में XLTX से WORDML रूपांतरण 

family: total
platformtag: Python
feature: conversion
informat: XLTX
outformat: WORDML
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन के माध्यम से बीएमपी को जीआईएफ में बदलें" h2="Microsoft Excel<sup>&reg;</sup> या Word इंस्टॉल किए बिना आपके Python एप्लिकेशन में XLTX से WORDML रूपांतरण" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक पायथन डेवलपर के लिए, जो एप्लिकेशन के भीतर जीआईएफ रूपांतरण सुविधा में बीएमपी जोड़ने की कोशिश कर रहा है। [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API रूपांतरण प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह बीएमपी और जीआईएफ फाइलों सहित विभिन्न प्रारूपों से निपटने वाले विभिन्न एपीआई का एक पूरा पैकेज है।

यह मुख्यतः दो चरणों में होता है। XLTX फ़ाइल को HTML में बदलने के लिए सबसे पहले [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API का उपयोग करें। उसके बाद Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) का उपयोग करके बनाए गए HTML को वांछित Microsoft Word स्वरूप में सहेजें। 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पायथन में बीएमपी को जीआईएफ में कैसे बदलें" %}}
- **स्टेप 1** Workbook वर्ग का उपयोग करके स्रोत XLTX फ़ाइल खोलें
- फ़ाइल नाम और वांछित निर्देशिका पथ प्रदान करके save(file, SaveFormat.HTML) विधि का उपयोग करके XLTX फ़ाइल को HTML में सहेजें
-  **चरण दो** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) वर्ग के उदाहरण के साथ HTML फ़ाइल लोड करें
-  आउटपुट जीआईएफ फ़ाइल पथ निर्दिष्ट करते समय `सेव` विधि को कॉल करें। तो आपकी बीएमपी फाइल निर्दिष्ट पथ पर जीआईएफ में परिवर्तित हो जाती है

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

- बीएमपी से जीआईएफ रूपांतरण के लिए, पायथन 3.5 या बाद के संस्करण की आवश्यकता है
- PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) और [Aspose.Words](https://pypi.org/project/aspose-words/)) से सीधे परियोजना के भीतर संदर्भ API
-  या निम्न पिप कमांड का उपयोग करें ``` पिप असोस-सेल्स-पायथन स्थापित करें``` और ``` पिप इंस्टाल aspose.words```
-  इसके अलावा, Microsoft Windows या Linux आधारित OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) और [Words](https://docs.aspose.com/words/python-net/system-requirements/) के लिए और देखें) और Linux के लिए gcc और libpython के लिए अतिरिक्त आवश्यकताओं की जाँच करें और [चरण दर चरण निर्देश](https://docs.aspose.com/words/python-net/installation/) का पालन करें
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XLTX को HTML में Python में सहेजें - चरण 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="पायथन में HTML को WORDML में सहेजें - चरण 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>बीएमपी से जीआईएफ के लिए मुफ्त ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=wordml&from=xltx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य रूपांतरण विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-word/" name="XLTX सेवा WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-doc/" name="XLTX सेवा DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-docx/" name="XLTX सेवा DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-docm/" name="XLTX सेवा DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-dot/" name="XLTX सेवा DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-dotm/" name="XLTX सेवा DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-dotx/" name="XLTX सेवा DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-mobi/" name="XLTX सेवा MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-odt/" name="XLTX सेवा ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-ott/" name="XLTX सेवा OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-rtf/" name="XLTX सेवा RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/python-net/conversion/xltx-to-wordml/" name="XLTX सेवा WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}