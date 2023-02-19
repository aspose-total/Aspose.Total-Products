---
title: تحويل XLSB إلى PPTX باستخدام .NET 
description: قم بتحويل ملف XLSB إلى PPTX على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin

family: total
platformtag: net
feature: conversion
informat: XLSB
outformat: PPTX
otherformats: POWERPOINT WORD DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="تحويل XLSB إلى PPTX عبر C#" h2="تصدير Excel & reg ؛ XLSB إلى PPTX على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل XLSB إلى PPTX على .NET" %}}
1. افتح ملف XLSB باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. تحويل XLSB إلى PDF وضبط SaveFormat على Auto
3. قم بتحميل ملف PDF المحول باستخدام فئة [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. احفظ المستند بتنسيق PPTX باستخدام طريقة [حفظ](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) وقم بتعيين Pptx كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NET C# Code لتحويل XLSB إلى PPTX" gistPath="" %}}
```cs
// load the XLSB file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsb");
// save XLSB as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ XLSB إلى PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsb" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-word/" name="CSV إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-powerpoint/" name="CSV إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-pptx/" name="CSV إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/csv-to-docx/" name="CSV إلى DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}