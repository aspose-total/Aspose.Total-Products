---
title: पायथन का उपयोग करके बीएमपी को जीआईएफ में बदलें
description: Microsoft Office का उपयोग किए बिना आपके Python अनुप्रयोगों में EXCEL से POT रूपांतरण 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POT
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="पायथन के माध्यम से बीएमपी को जीआईएफ में बदलें" h2="Microsoft Excel<sup>&reg;</sup> या PowerPoint स्थापित किए बिना आपके Python एप्लिकेशन में EXCEL से POT रूपांतरण" >}}

{{% blocks/products/pf/feature-page-summary %}}

एक पायथन डेवलपर के लिए, जो एप्लिकेशन के भीतर जीआईएफ रूपांतरण सुविधा में बीएमपी जोड़ने की कोशिश कर रहा है, [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API रूपांतरण प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह बीएमपी और जीआईएफ फाइलों सहित विभिन्न प्रारूपों से निपटने वाले विभिन्न एपीआई का एक पूरा पैकेज है.

यह मुख्यतः दो चरणों में होता है. EXCEL फ़ाइल को PDF में बदलने के लिए सबसे पहले [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API का उपयोग करें. उसके बाद PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) का उपयोग करके बनाई गई PDF को वांछित Microsoft PowerPoint स्वरूप में सहेजें. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="पायथन में बीएमपी को जीआईएफ में कैसे बदलें" %}}
- **चरण 1** स्रोत EXCEL फ़ाइल खोलने के लिए Workbook क्लास इंस्टेंस का उपयोग करें 
- फ़ाइल का नाम और वांछित निर्देशिका पथ प्रदान करके save विधि का उपयोग करके EXCEL फ़ाइल को PDF में सहेजें
-  **चरण दो** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) वर्ग का उपयोग करके PDF फ़ाइल लोड करें
-  आउटपुट POT फ़ाइल पथ निर्दिष्ट करते समय [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) विधि को कॉल करें. तो आपकी बीएमपी फाइल निर्दिष्ट पथ पर जीआईएफ में परिवर्तित हो जाती है

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}

- बीएमपी से जीआईएफ रूपांतरण के लिए, पायथन 3.5 या बाद के संस्करण की आवश्यकता है
- PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) और [Aspose.Slides](https://pypi.org/project/Aspose.Slides/)) से सीधे परियोजना के भीतर संदर्भ API
-  या निम्न पिप कमांड का उपयोग करें ``` पिप असोस-सेल्स-पायथन स्थापित करें``` और ``` पिप इंस्टाल aspose.slides```
-  इसके अलावा, Microsoft Windows या Linux आधारित OS ([Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) और [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) के लिए और देखें)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="पायथन में बीएमपी को पीडीएफ में सहेजें - चरण 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="पायथन में पीडीएफ को जीआईएफ में सहेजें - चरण 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}