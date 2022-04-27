---
title: NET API لتحويل DOT إلى SXC
description: C# API لتحويل DOT إلى SXC بدون استخدام Microsoft Excel أو Adobe Reader
url: /ar/net/conversion/dot-to-sxc/
family: total
platformtag: net
feature: conversion
informat: DOT
outformat: SXC
otherformats: DIF XLSM XLTX EXCEL FODS SXC TSV XLSB XLAM ODS XLTM XLSX XLT XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتحويل DOT إلى SXC" h2="تصدير DOT إلى SXC عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تضمين DOT إلى ميزة تحويل SXC ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تصدير DOT إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى SXC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل DOT إلى SXC" %}}
1. افتح ملف DOT باستخدام فئة [Dotument](https://apireference.aspose.com/words/net/aspose.words/dotument)
2. تحويل DOT إلى HTML باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.dotument/save/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق SXC باستخدام طريقة [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `SXC` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند DOT من الدفق عبر C#" %}}
يسمح لك [Aspose.Words for .NET](https://products.aspose.com/words/net/) أيضًا بتحميل مستند DOT عبر الدفق. لفتح مستند من تيار ، ما عليك سوى تمرير كائن تيار يحتوي على المستند إلى مُنشئ [Dotument](https://apireference.aspose.com/words/net/aspose.words/dotument). يوضح المثال التالي من التعليمات البرمجية كيفية فتح مستند من دفق:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إضافة خصائص مخصصة في ملف SXC عبر C#" %}}
أثناء تحويل DOT إلى SXC ، يمكّنك [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) من إضافة خصائص مخصصة في مستندات SXC. لإضافة خاصية مخصصة ، يمكنك استخدام طريقة [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotumentpropertycollection/methods/add/index) للأسلوب [CustomDotumentPropertyCollection](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdotumentpropertycollection) فئة. يضيف الأسلوب Add الخاصية إلى ملف Excel ويعيد مرجعًا لخاصية المستند الجديدة كـ [Aspose.Cells.Properties.DotumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties/dotumentproperty) كائن. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-dif/" name="DOT ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xlsb/" name="DOT ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-tsv/" name="DOT ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-fods/" name="DOT ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xlt/" name="DOT ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-excel/" name="DOT ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xlsx/" name="DOT ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-ods/" name="DOT ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-sxc/" name="DOT ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xlam/" name="DOT ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xltm/" name="DOT ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xlsm/" name="DOT ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xls/" name="DOT ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/dot-to-xltx/" name="DOT ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}