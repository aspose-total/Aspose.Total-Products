---
title: पायथन का उपयोग करके बीएमपी को जीआईएफ में बदलें
description: Microsoft Office का उपयोग किए बिना आपके Python अनुप्रयोगों में PPSM से XLS रूपांतरण 

family: total
platformtag: Python
feature: conversion
informat: PPSM
outformat: XLS
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन के माध्यम से बीएमपी को जीआईएफ में बदलें" h2="Microsoft PowerPoint<sup>&reg;</sup> या Excel इंस्टॉल किए बिना आपके Python एप्लिकेशन में PPSM से XLS रूपांतरण" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक पायथन डेवलपर के लिए, जो एप्लिकेशन के भीतर जीआईएफ रूपांतरण सुविधा में बीएमपी जोड़ने की कोशिश कर रहा है। [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API रूपांतरण प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह बीएमपी और जीआईएफ फाइलों सहित विभिन्न प्रारूपों से निपटने वाले विभिन्न एपीआई का एक पूरा पैकेज है।

यह मुख्यतः दो चरणों में होता है। PPSM फ़ाइल को HTML में बदलने के लिए सबसे पहले [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API का उपयोग करें। उसके बाद Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) का उपयोग करके बनाए गए HTML को वांछित Microsoft Excel स्वरूप में सहेजें। 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पायथन में बीएमपी को जीआईएफ में कैसे बदलें" %}}
- **स्टेप 1** स्रोत PPSM फ़ाइल खोलने के लिए [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) क्लास इंस्टेंस का उपयोग करें 
- फ़ाइल नाम और वांछित निर्देशिका पथ प्रदान करके [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) विधि का उपयोग करके PPSM फ़ाइल को HTML में सहेजें
-  **चरण दो** Workbook वर्ग के उदाहरण के साथ HTML फ़ाइल लोड करें
-  आउटपुट जीआईएफ फ़ाइल पथ निर्दिष्ट करते समय `सेव` विधि को कॉल करें। तो आपकी बीएमपी फाइल निर्दिष्ट पथ पर जीआईएफ में परिवर्तित हो जाती है

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

- बीएमपी से जीआईएफ रूपांतरण के लिए, पायथन 3.5 या बाद के संस्करण की आवश्यकता है
- PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) और [Aspose.Cells](https://pypi.org/project/aspose-cells-python/)) से सीधे परियोजना के भीतर संदर्भ API
-  या निम्न पिप कमांड का उपयोग करें ```पिप aspose.slides स्थापित करें``` और ```पिप aspose-cells-python स्थापित करें```
-  इसके अलावा, Microsoft Windows या Linux आधारित OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) और [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) के लिए और देखें)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PPSM को HTML में Python में सहेजें - चरण 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="पायथन में HTML को XLS में सहेजें - चरण 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}