---
title: C++ के साथ SXC को DOCX में बदलें
description: C++ अनुप्रयोगों के भीतर SXC को DOCX में बदलें

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: DOCX
otherformats: WORD DOC PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ के माध्यम से SXC को DOCX में बदलें" h2="एक्सेल निर्यात करें&reg; पूर्ण-कार्यात्मक सी ++ अनुप्रयोगों के भीतर सीएसवी से डीओसी तक" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी++ पर सीएसवी से डीओसी रूपांतरण" %}}
1. [Factory](https://reference.aspose.com/cells) के सदस्य फ़ंक्शन [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) का उपयोग करके SXC फ़ाइल खोलें /cpp/class/aspose.cells.factory) वर्ग संदर्भ
2. SXC को PDF में बदलें और SaveFormat को Pdf में सेट करें
3. परिवर्तित पीडीएफ फाइल को [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) वर्ग संदर्भ का उपयोग करके लोड करें
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को DOCX प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/sxc-to-word/" name="SXC प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/sxc-to-docx/" name="SXC प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/sxc-to-pptx/" name="SXC प्रति PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/sxc-to-powerpoint/" name="SXC प्रति POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}