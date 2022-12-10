---
title: सी ++ का उपयोग कर बीएमपी फ़ाइल अपडेट करें
description: Microsoft Excel का उपयोग किए बिना C++ अनुप्रयोगों में XLT दस्तावेज़ को संशोधित करें.
family: total
platformtag: C++
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="सी ++ के माध्यम से बीएमपी फ़ाइल अपडेट करें" h2="Microsoft Office<sup>&reg;</sup> इंस्टॉल किए बिना अपने C++ आधारित एप्लिकेशन के माध्यम से XLT स्प्रेडशीट संशोधित करें।" >}}

{{% blocks/products/pf/feature-page-summary %}}

प्रोग्रामर के लिए, जो सी ++ एप्लिकेशन के भीतर बीएमपी फाइलों को अपडेट करने का प्रयास कर रहा है, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API अपडेट करने की प्रक्रिया को स्वचालित करने में मदद कर सकता है। यह माइक्रोसॉफ्ट एक्सेल दस्तावेज़ों सहित कई प्रारूपों से निपटने वाले विभिन्न सी ++ पुस्तकालयों का एक पूर्ण पैकेज है। [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API जो [Aspose.Total for C++](https://products.aspose.com/total/cpp/) पैकेज का हिस्सा है, इस संशोधन प्रक्रिया को आसान बनाता है। बीएमपी दस्तावेज़ को अपडेट करने की प्रक्रिया पहले शीट तक पहुंचकर सरल है और फिर सी ++ का उपयोग करके एक्सेल में सेल वैल्यू अपडेट करें।

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ में XLT फाइल को कैसे अपडेट करें" %}}

- [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8) का उपयोग करके XLT फ़ाइल लोड करें
- GetIWorksheets()->GetObjectByIndex(0) का उपयोग करके प्रासंगिक [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) और GetICells()->GetObjectByIndex का उपयोग करके प्रासंगिक सेल तक पहुंच
- PutValue पद्धति का उपयोग करके एक्सेस किए गए सेल में नया डेटा डालें
- फाइल को पैरामीटर के रूप में पाथ के साथ पास करके सेव मेथड का उपयोग करके फाइल को .xlt फाइल के रूप में सेव करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="संशोधन आवश्यकताएँ" %}}

- XLT संशोधन के लिए, Windows और Linux सिस्टम के लिए [सिस्टम आवश्यकताएं](https://docs.aspose.com/cells/cpp/system-requirements/) का पालन करें 
- कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में स्थापित करें
- या विज़ुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से ```Install-Package Aspose.Total.Cpp``` के साथ
- वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/cells/cpp) से एक ZIP फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="कोड - सी ++ में बीएमपी फ़ाइल अपडेट करें" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य संशोधन विकल्प" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xls/" name="अद्यतन XLS फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xlsx/" name="अद्यतन XLSX फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/csv/" name="अद्यतन CSV फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xlsb/" name="अद्यतन XLSB फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xlsm/" name="संशोधित XLSM फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xlt/" name="अद्यतन XLT फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xltx/" name="अद्यतन XLTX फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/xltm/" name="अद्यतन XLTM फ़ाइल" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/update/tsv/" name="अद्यतन TSV फ़ाइल" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}