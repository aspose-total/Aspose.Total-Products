---
title: NET API لتحويل WORD إلى CSV
description: C# API لتحويل WORD إلى CSV بدون استخدام Microsoft Excel أو Adobe Reader
url: /ar/net/conversion/word-to-csv/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: CSV
otherformats: XLTX XLAM XLT XLSX XLTM FODS SXC XLSB TSV DIF ODS EXCEL XLSM XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتحويل WORD إلى CSV" h2="تصدير WORD إلى CSV عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تضمين WORD إلى ميزة تحويل CSV ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تصدير WORD إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى CSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل WORD إلى CSV" %}}
1. افتح ملف WORD باستخدام فئة [Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument)
2. تحويل WORD إلى HTML باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.wordument/save/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق CSV باستخدام طريقة [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `CSV` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature](ge-section  h2="قم بتحميل مستند WORD من الدفق عبر C#" %}}
يسمح لك [Aspose.Words for .NET](https://products.aspose.com/words/net/) أيضًا بتحميل مستند WORD عبر الدفق. لفتح مستند من تيار ، ما عليك سوى تمرير كائن تيار يحتوي على المستند إلى مُنشئ [Wordument](https://apireference.aspose.com/words/net/aspose.words/wordument). يوضح المثال التالي من التعليمات البرمجية كيفية فتح مستند من دفق:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إضافة خصائص مخصصة في ملف CSV عبر C#" %}}
أثناء تحويل WORD إلى CSV ، يمكّنك [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) من إضافة خصائص مخصصة في مستندات CSV. لإضافة خاصية مخصصة ، يمكنك استخدام طريقة [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordumentpropertycollection/methods/add/index) للأسلوب [CustomWordumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customwordumentpropertycollection) فئة. يضيف الأسلوب Add الخاصية إلى ملف Excel ويعيد مرجعًا لخاصية المستند الجديدة كـ [Aspose.Cells.Properties.WordumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties / wordumentproperty) كائن. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-dif/" name="WORD ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsb/" name="WORD ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-tsv/" name="WORD ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-fods/" name="WORD ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlt/" name="WORD ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-excel/" name="WORD ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsx/" name="WORD ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-ods/" name="WORD ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-sxc/" name="WORD ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlam/" name="WORD ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xltm/" name="WORD ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xlsm/" name="WORD ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xls/" name="WORD ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/word-to-xltx/" name="WORD ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}