---
title: تحويل DOCX إلى تنسيق JSON عبر .NET
description: تحويل DOCX إلى JSON في C # بدون استخدام Microsoft Excel أو Adobe Reader
url: /ar/net/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: JSON
otherformats: FODS XLTX XLSM XLS XLT XLSB ODS CSV TSV XLTM EXCEL SXC XLAM DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل DOCX إلى تنسيق JSON عبر C #" h2="تحليل DOCX إلى JSON عبر C # بدون استخدام Microsoft <sup> & reg؛ </sup> Word أو Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET] (https://products.aspose.com/total/net/) يمكنك تحويل DOCX إلى تنسيق JSON ضمن أي تطبيق .NET و C # و ASP.NET و VB.NET في اثنين خطوات بسيطة. أولاً ، باستخدام [Aspose.Words for .NET] (https://products.aspose.com/words/net/) ، يمكنك تصدير DOCX إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET] (https://products.aspose.com/cells/net/) Spreadsheet Programming API ، يمكنك تحويل HTML إلى JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOCX إلى تنسيق JSON عبر C #" %}}
1. افتح ملف DOCX باستخدام فئة [Docxument] (https://apireference.aspose.com/words/net/aspose.words/docxument)
2. تحويل DOCX إلى HTML باستخدام طريقة [حفظ] (https://apireference.aspose.com/words/net/aspose.words.docxument/save/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook] (https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق JSON باستخدام طريقة [حفظ] (https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل DOCX المحمي إلى تنسيق JSON عبر C #" %}}
باستخدام API ، يمكنك أيضًا فتح المستند المحمي بكلمة مرور. إذا كان مستند DOCX الذي تم إدخاله محميًا بكلمة مرور ، فلا يمكنك تحويله إلى تنسيق JSON دون استخدام كلمة المرور. تسمح لك واجهة برمجة التطبيقات بفتح المستند المشفر عن طريق تمرير كلمة المرور الصحيحة في كائن LoadOptions. يوضح المثال التالي من التعليمات البرمجية كيفية محاولة فتح مستند مشفر بكلمة مرور:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل DOCX إلى JSON في النطاق عبر C #" %}}
أثناء قيامك بتحويل DOCX إلى JSON ، يمكنك أيضًا ضبط النطاق على تنسيق JSON الناتج. لتعيين النطاق ، يمكنك فتح HTML المحول باستخدام فئة Workbook ، والحصول على مجموعة Cells من ورقة العمل التي تحتوي على البيانات ، وإنشاء نطاق من CellsCollection عن طريق تحديد فهارس الصفوف والأعمدة ، واستدعاء طريقة ExportRangeToJson مع إشارات إلى كائنات Range & ExportRangeToJsonOptions. أخيرًا ، يمكنك حفظ بيانات JSON في ملف عبر طريقة File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-csv/" name="DOCX ل CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlam/" name="DOCX ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-sxc/" name="DOCX ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-tsv/" name="DOCX ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlt/" name="DOCX ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-excel/" name="DOCX ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-dif/" name="DOCX ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsm/" name="DOCX ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xltm/" name="DOCX ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsx/" name="DOCX ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsb/" name="DOCX ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-fods/" name="DOCX ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-ods/" name="DOCX ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xltx/" name="DOCX ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}