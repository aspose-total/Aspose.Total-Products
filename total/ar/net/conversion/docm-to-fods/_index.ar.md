---
title: NET API لتحويل DOCM إلى FODS
description: C# API لتحويل DOCM إلى FODS بدون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/net/conversion/docm-to-fods/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: FODS
otherformats: XLSM XLTX XLAM XLT ODS FODS EXCEL XLS SXC XLSX XLSB XLTM TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتحويل DOCM إلى FODS" h2="تصدير DOCM إلى FODS عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تضمين DOCM إلى ميزة تحويل FODS ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تصدير DOCM إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى FODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل DOCM إلى FODS" %}}
1. افتح ملف DOCM باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. تحويل DOCM إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.documentsave/methods/4)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق FODS باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `FODS` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "convert-word-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند DOCM من الدفق عبر C#" %}}
يسمح لك [Aspose.Words for .NET](https://products.aspose.com/words/net/) أيضًا بتحميل مستند DOCM عبر الدفق. لفتح مستند من تيار ، ما عليك سوى تمرير كائن تيار يحتوي على المستند إلى مُنشئ [Document](https://reference.aspose.com/words/net/aspose.words/document). يوضح المثال التالي من التعليمات البرمجية كيفية فتح مستند من دفق:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "load-word-via-stream.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إضافة خصائص مخصصة في ملف FODS عبر C#" %}}
أثناء تحويل DOCM إلى FODS ، يمكّنك [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) من إضافة خصائص مخصصة في مستندات FODS. لإضافة خاصية مخصصة ، يمكنك استخدام طريقة [Add](https://reference.aspose.com/cells/net/aspose.cells.properties/customdocumentropertycollection/methods/add/index) للأسلوب [CustomDocumentPropertyCollection](https://reference.aspose.com/cells/net/aspose.cells.properties/CustomDocumentPropertyCollection) فئة. يضيف الأسلوب Add الخاصية إلى ملف Excel ويعيد مرجعًا لخاصية المستند الجديدة كـ [Aspose.Cells.Properties.DocumentProperty](https://reference.aspose.com/cells/net/aspose.cells.properties/DocumentProperty) كائن. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "7a952faebcdf859aef38480f2fabc0dc" "manage-custom-properties-in-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-dif/" name="DOCM ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsb/" name="DOCM ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-tsv/" name="DOCM ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-fods/" name="DOCM ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlt/" name="DOCM ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-excel/" name="DOCM ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsx/" name="DOCM ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-ods/" name="DOCM ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-sxc/" name="DOCM ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlam/" name="DOCM ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xltm/" name="DOCM ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xlsm/" name="DOCM ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xls/" name="DOCM ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/docm-to-xltx/" name="DOCM ل XLTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}