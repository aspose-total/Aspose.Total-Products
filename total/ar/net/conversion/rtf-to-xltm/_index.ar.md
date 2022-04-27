---
title: NET API لتحويل RTF إلى XLTM
description: C# API لتحويل RTF إلى XLTM بدون استخدام Microsoft Excel أو Adobe Reader
url: /ar/net/conversion/rtf-to-xltm/
family: total
platformtag: net
feature: conversion
informat: RTF
outformat: XLTM
otherformats: FODS XLS XLSB XLSX XLTM XLTX XLAM TSV ODS XLT EXCEL SXC DIF XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتحويل RTF إلى XLTM" h2="تصدير RTF إلى XLTM عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تضمين RTF إلى ميزة تحويل XLTM ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تصدير RTF إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى XLTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل RTF إلى XLTM" %}}
1. افتح ملف RTF باستخدام فئة [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument)
2. تحويل RTF إلى HTML باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.rtfument/save/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق XLTM باستخدام طريقة [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `XLTM` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند RTF من الدفق عبر C#" %}}
يسمح لك [Aspose.Words for .NET](https://products.aspose.com/words/net/) أيضًا بتحميل مستند RTF عبر الدفق. لفتح مستند من تيار ، ما عليك سوى تمرير كائن تيار يحتوي على المستند إلى مُنشئ [Rtfument](https://apireference.aspose.com/words/net/aspose.words/rtfument). يوضح المثال التالي من التعليمات البرمجية كيفية فتح مستند من دفق:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إضافة خصائص مخصصة في ملف XLTM عبر C#" %}}
أثناء تحويل RTF إلى XLTM ، يمكّنك [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) من إضافة خصائص مخصصة في مستندات XLTM. لإضافة خاصية مخصصة ، يمكنك استخدام طريقة [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection/methods/add/index) للأسلوب [CustomRtfumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customrtfumentpropertycollection) فئة. يضيف الأسلوب Add الخاصية إلى ملف Excel ويعيد مرجعًا لخاصية المستند الجديدة كـ [Aspose.Cells.Properties.RtfumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/rtfumentproperty) كائن. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-dif/" name="RTF ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsb/" name="RTF ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-tsv/" name="RTF ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-fods/" name="RTF ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlt/" name="RTF ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-excel/" name="RTF ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsx/" name="RTF ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-ods/" name="RTF ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-sxc/" name="RTF ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlam/" name="RTF ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xltm/" name="RTF ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xlsm/" name="RTF ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xls/" name="RTF ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/rtf-to-xltx/" name="RTF ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}