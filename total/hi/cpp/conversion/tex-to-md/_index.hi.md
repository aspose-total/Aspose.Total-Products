---
title: सीजीएम को सीएसवी में बदलने के लिए सी++ एपीआई
description: माइक्रोसॉफ्ट एक्सेल या एडोब रीडर का उपयोग किए बिना सीजीएम को सी ++ एपीआई के माध्यम से सीएसवी में कनवर्ट करें

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: MD
otherformats: TXT FODS EXCEL TSV XLT XLSB XLAM XLTX XLSM CSV SXC DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ अनुप्रयोगों में MD को TEX प्रदान करें" h2="Microsoft<sup>&reg;</sup> Excel या Adobe<sup>&reg;</sup> Acrobat Reader की आवश्यकता के बिना TEX को मूल C++ अनुप्रयोगों में MD में बदलें" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) फाइल फॉर्मेट ऑटोमेशन लाइब्रेरी के जरिए सीजीएम को सी++ में सीएसवी में बदलना एक आसान दो चरणों वाली प्रक्रिया है। पहले चरण में, आप [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) का उपयोग करके XLSX को TEX निर्यात कर सकते हैं, उसके बाद, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) स्प्रेडशीट प्रोग्रामिंग एपीआई, आप XLSX को MD में बदल सकते हैं। 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी ++ एपीआई सीजीएम को सीएसवी में कनवर्ट करने के लिए" %}}
1. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके सीजीएम फ़ाइल खोलें
2. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) सदस्य फ़ंक्शन का उपयोग करके TEX को XLSX में बदलें
3. [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) वर्ग संदर्भ का उपयोग करके XLSX दस्तावेज़ लोड करें
4. [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को MD प्रारूप में सहेजें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से TEX फ़ाइल जानकारी प्राप्त करें या सेट करें" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) भी आपको अपने TEX दस्तावेज़ के बारे में जानकारी प्राप्त करने की अनुमति देता है और आपको अपनी रूपांतरण प्रक्रिया से पहले सूचित निर्णय लेने देता है। TEX फ़ाइल की फ़ाइल विशिष्ट जानकारी प्राप्त करने के लिए, आपको सबसे पहले [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) विधि को कॉल करना होगा। [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग। एक बार DocumentInfo ऑब्जेक्ट पुनर्प्राप्त हो जाने के बाद, आप अलग-अलग गुणों के मान प्राप्त कर सकते हैं। इसके अलावा, आप DocumentInfo वर्ग के संबंधित तरीकों का उपयोग करके भी गुण सेट कर सकते हैं।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ के माध्यम से स्ट्रीम करने के लिए MD फ़ाइल स्वरूप सहेजें" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) स्ट्रीम करने के लिए MD फ़ाइल स्वरूप को सहेजने की अनुमति देता है। फ़ाइलों को स्ट्रीम में सहेजने के लिए, एक मेमोरीस्ट्रीम या फ़ाइलस्ट्रीम ऑब्जेक्ट बनाएं और [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) पर कॉल करके फ़ाइल को उस स्ट्रीम ऑब्जेक्ट में सहेजें। ऑब्जेक्ट की [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) विधि। सेव विधि को कॉल करते समय [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) एन्यूमरेशन का उपयोग करके वांछित फ़ाइल स्वरूप निर्दिष्ट करें।
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-md-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}