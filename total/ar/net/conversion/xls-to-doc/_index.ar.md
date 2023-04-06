---
title: تحويل XLS إلى DOC باستخدام .NET أو مع محول مجاني على الإنترنت
description: قم بتحويل ملف XLS إلى DOC على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin أو عبر الإنترنت. اختبر محول CSV إلى DOC على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: DOC
otherformats: PPTX POWERPOINT DOCX WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="تحويل XLS إلى DOC عبر C# أو التطبيق عبر الإنترنت" h2="تصدير Excel & reg ؛ XLS إلى DOC على الأنظمة الأساسية .NET Framework أو .NET Core أو Mono أو Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل XLS إلى DOC على .NET" %}}
1. افتح ملف XLS باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. تحويل XLS إلى PDF وضبط SaveFormat على Auto
3. قم بتحميل ملف PDF المحول باستخدام فئة [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. احفظ المستند بتنسيق DOC باستخدام طريقة [حفظ](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) وقم بتعيين Doc كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="NET C# Code لتحويل XLS إلى DOC" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ XLS إلى DOC</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=doc&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}