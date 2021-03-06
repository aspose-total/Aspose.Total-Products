---
title: .NET के साथ XLTX को WORD में बदलें 
description: .NET Framework, .NET Core, Mono या Xamarin प्लेटफॉर्म पर XLTX को WORD में बदलें
url: /hi/net/conversion/xltx-to-word/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: DOC
otherformats: PPTX POWERPOINT DOC DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="सी # के माध्यम से सीएसवी को डीओसी में कनवर्ट करें" h2="एक्सेल निर्यात करें&reg; .NET Framework, .NET Core, Mono या Xamarin प्लेटफॉर्म पर WORD को XLTX">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET . पर XLTX से WORD रूपांतरण" %}}
1. [वर्कबुक](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके XLTX फ़ाइल खोलें
2. XLTX को PDF में बदलें और SaveFormat को Auto पर सेट करें
3. रूपांतरित पीडीएफ फाइल को [दस्तावेज़](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument) वर्ग का उपयोग करके लोड करें
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) विधि का उपयोग करके दस्तावेज़ को WORD प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ````Install-Package Aspose.Total`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://downloads.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".नेट सी # सीएसवी के लिए डीओसी रूपांतरण के लिए कोड" gistPath="" %}}
```cs
// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="अन्य समर्थित रूपांतरण" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/csv-to-word/" name="CSV प्रति WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/csv-to-powerpoint/" name="CSV प्रति POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/csv-to-pptx/" name="CSV प्रति PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hi/net/conversion/csv-to-docx/" name="CSV प्रति DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}