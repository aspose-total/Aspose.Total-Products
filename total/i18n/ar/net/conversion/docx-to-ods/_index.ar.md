---
title: NET API لتحويل DOCX إلى ODS
description: C# API لتحويل DOCX إلى ODS بدون استخدام Microsoft Excel أو Adobe Reader
url: /ar/net/conversion/docx-to-ods/
family: total
platformtag: net
feature: conversion
informat: DOCXX
outformat: ODS
otherformats: DIF XLTM ODS XLSM XLAM FODS EXCEL XLSX TSV XLT XLTX XLSB XLS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتحويل DOCX إلى ODS" h2="تصدير DOCX إلى ODS عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تضمين DOCX إلى ميزة تحويل ODS ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تصدير DOCX إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل DOCX إلى ODS" %}}
1. افتح ملف DOCX باستخدام فئة [Document](https://apireference.aspose.com/words/net/aspose.words/document)
2. تحويل DOCX إلى HTML باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق ODS باستخدام طريقة [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `ODS` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature](ge-section  h2="قم بتحميل مستند DOCX من الدفق عبر C#" %}}
يسمح لك [Aspose.Words for .NET](https://products.aspose.com/words/net/) أيضًا بتحميل مستند DOCX عبر الدفق. لفتح مستند من تيار ، ما عليك سوى تمرير كائن تيار يحتوي على المستند إلى مُنشئ [Document](https://apireference.aspose.com/words/net/aspose.words/document). يوضح المثال التالي من التعليمات البرمجية كيفية فتح مستند من دفق:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إضافة خصائص مخصصة في ملف ODS عبر C#" %}}
أثناء تحويل DOCX إلى ODS ، يمكّنك [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) من إضافة خصائص مخصصة في مستندات ODS. لإضافة خاصية مخصصة ، يمكنك استخدام طريقة [Add](https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection/methods/add/index) للأسلوب [CustomDocumentPropertyCollection]( https://apireference.aspose.com/cells/net/aspose.cells.properties/customdocumentpropertycollection) فئة. يضيف الأسلوب Add الخاصية إلى ملف Excel ويعيد مرجعًا لخاصية المستند الجديدة كـ [Aspose.Cells.Properties.DocumentProperty](https://apireference.aspose.com/cells/net/aspose.cells.properties / documentproperty) كائن. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-dif/" name="DOCX ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsb/" name="DOCX ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-tsv/" name="DOCX ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-fods/" name="DOCX ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlt/" name="DOCX ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-excel/" name="DOCX ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsx/" name="DOCX ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-ods/" name="DOCX ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-sxc/" name="DOCX ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlam/" name="DOCX ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xltm/" name="DOCX ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xlsm/" name="DOCX ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xls/" name="DOCX ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docx-to-xltx/" name="DOCX ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}