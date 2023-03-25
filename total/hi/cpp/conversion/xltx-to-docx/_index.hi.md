---
title: C++ के साथ XLTX को DOCX में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: C++ अनुप्रयोगों के भीतर XLTX को DOCX में बदलें या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।

family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: DOCX
otherformats: DOC POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ के माध्यम से XLTX को DOCX में बदलें या ऑनलाइन" h2="एक्सेल निर्यात करें&reg; पूर्ण-कार्यात्मक सी ++ अनुप्रयोगों के भीतर सीएसवी से डीओसी तक" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी++ पर सीएसवी से डीओसी रूपांतरण" %}}
1. [Factory](https://reference.aspose.com/cells) के सदस्य फ़ंक्शन [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) का उपयोग करके XLTX फ़ाइल खोलें /cpp/class/aspose.cells.factory) वर्ग संदर्भ
2. XLTX को PDF में बदलें और SaveFormat को Pdf में सेट करें
3. परिवर्तित पीडीएफ फाइल को [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को DOCX प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>बीएमपी से जीआईएफ के लिए ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xltx-to-docx/">बीएमपी से जीआईएफ रूपांतरण के लिए हमारा मुफ्त ऐप आज़माएं</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}