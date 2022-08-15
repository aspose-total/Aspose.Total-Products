---
title: C++ के साथ FODS को DOCX में बदलें
description: C++ अनुप्रयोगों के भीतर FODS को DOCX में बदलें
url: /hi/cpp/conversion/fods-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: DOCX
otherformats: DOC WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ के माध्यम से FODS को DOCX में बदलें" h2="एक्सेल निर्यात करें&reg; पूर्ण-कार्यात्मक सी ++ अनुप्रयोगों के भीतर सीएसवी से डीओसी तक" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="सी++ पर सीएसवी से डीओसी रूपांतरण" %}}
1. [Factory](https://reference.aspose.com/cells) के सदस्य फ़ंक्शन [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) का उपयोग करके FODS फ़ाइल खोलें /cpp/class/aspose.cells.factory) वर्ग संदर्भ
2. FODS को PDF में बदलें और SaveFormat को Pdf में सेट करें
3. परिवर्तित पीडीएफ फाइल को [दस्तावेज़](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument) वर्ग संदर्भ का उपयोग करके लोड करें
4. [सहेजें](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) सदस्य फ़ंक्शन का उपयोग करके दस्तावेज़ को DOCX प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total.Cpp``` के रूप में या ````Install-Package Aspose.Total.Cpp`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/cpp) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.fods");
// save FODS as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/fods-to-docx/" name="FODS प्रति DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/fods-to-word/" name="FODS प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/fods-to-pptx/" name="FODS प्रति PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/cpp/conversion/fods-to-powerpoint/" name="FODS प्रति POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}