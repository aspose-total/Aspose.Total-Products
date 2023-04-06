---
title: .NET के साथ ODS को WORD में बदलें या मुफ्त ऑनलाइन कन्वर्टर के साथ
description: .NET Framework, .NET Core, Mono या Xamarin प्लेटफॉर्म पर ODS को WORD में बदलें या ऑनलाइन। कोड को एकीकृत करने से पहले मुफ्त बीएमपी से जीआईएफ ऑनलाइन परिवर्तक का त्वरित परीक्षण करें।

family: total
platformtag: net
feature: conversion
informat: ODS
outformat: DOC
otherformats: DOCX POWERPOINT DOC PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="सी # के माध्यम से सीएसवी को डीओसी में कनवर्ट करें या ऑनलाइन ऐप" h2="एक्सेल निर्यात करें&reg; .NET Framework, .NET Core, Mono या Xamarin प्लेटफॉर्म पर WORD को ODS">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET . पर ODS से WORD रूपांतरण" %}}
1. [वर्कबुक](https://apireference.aspose.com/cells/net/aspose.cells/workbook) क्लास का इस्तेमाल करके ODS फ़ाइल खोलें
2. ODS को PDF में बदलें और SaveFormat को Auto पर सेट करें
3. रूपांतरित पीडीएफ फाइल को [दस्तावेज़](https://apireference.aspose.com/pdf/net/aspose.pdf/wordument) वर्ग का उपयोग करके लोड करें
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.wordument/save/methods/5) विधि का उपयोग करके दस्तावेज़ को WORD प्रारूप में सहेजें और दस्तावेज़ को SaveFormat के रूप में सेट करें
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="रूपांतरण आवश्यकताएँ" %}}
कमांड लाइन से ```nuget install Aspose.Total``` के रूप में या ````Install-Package Aspose.Total`` के साथ विजुअल स्टूडियो के पैकेज मैनेजर कंसोल के माध्यम से इंस्टॉल करें।

वैकल्पिक रूप से, [डाउनलोड](https://releases.aspose.com/total/net) से ज़िप फ़ाइल में ऑफ़लाइन MSI इंस्टॉलर या DLL प्राप्त करें।
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".नेट सी # सीएसवी के लिए डीओसी रूपांतरण के लिए कोड" gistPath="" %}}
```cs
// load the ODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.ods");
// save ODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Wordument class
var wordument = new Aspose.Pdf.Wordument("pdfOutput.pdf");
// save wordument in WORD format
wordument.Save("output.word", SaveFormat.Word); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>बीएमपी से जीआईएफ के लिए मुफ्त ऑनलाइन कन्वर्टर</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=ods" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}