---
title: تحويل EXCEL إلى POWERPOINT باستخدام .NET 
description: قم بتحويل ملف EXCEL إلى POWERPOINT على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: PPTX
otherformats: WORD PPTX DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="تحويل EXCEL إلى POWERPOINT عبر C#" h2="تصدير Excel & reg ؛ EXCEL إلى POWERPOINT على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل EXCEL إلى POWERPOINT على .NET" %}}
1. افتح ملف EXCEL باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. تحويل EXCEL إلى PDF وضبط SaveFormat على Auto
3. قم بتحميل ملف PDF المحول باستخدام فئة [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. احفظ المستند بتنسيق POWERPOINT باستخدام طريقة [حفظ](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) وقم بتعيين Powerpoint كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NET C# Code لتحويل EXCEL إلى POWERPOINT" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}