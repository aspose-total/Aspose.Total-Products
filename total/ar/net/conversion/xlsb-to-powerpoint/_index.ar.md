---
title: تحويل XLSB إلى POWERPOINT باستخدام .NET 
description: قم بتحويل ملف XLSB إلى POWERPOINT على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin
url: /ar/net/conversion/xlsb-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: DOC DOCX WORD PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل XLSB إلى POWERPOINT عبر C#" h2="تصدير Excel & reg ؛ XLSB إلى POWERPOINT على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل XLSB إلى POWERPOINT على .NET" %}}
1. افتح ملف XLSB باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. تحويل XLSB إلى PDF وضبط SaveFormat على Auto
3. قم بتحميل ملف PDF المحول باستخدام فئة [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. احفظ المستند بتنسيق POWERPOINT باستخدام طريقة [حفظ](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) وقم بتعيين Powerpoint كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NET C# Code لتحويل XLSB إلى POWERPOINT" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-word/" name="CSV إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-powerpoint/" name="CSV إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-pptx/" name="CSV إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-docx/" name="CSV إلى DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}