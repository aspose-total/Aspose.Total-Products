---
title: تحويل POTX إلى XLSX عبر C#
description: قم بتحويل POTX إلى XLSX في C# بدون استخدام Microsoft Excel أو Powerpoint
url_ignore: /ar/net/conversion/potx-to-xlsx/
family: total
platformtag: net
feature: conversion
informat: POTXX
outformat: XLSX
otherformats: MARKDOWN XLS XLSM TSV ODS DIF XLTM XLSB SXC EXCEL XLAM XLSX XLTX FODS XLT MHTML DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل POTX إلى XLSX عبر C#" h2="NET API لتحويل POTX إلى XLSX بدون استخدام Microsoft<sup>&reg;</sup> Excel أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك تحويل ملف POTX إلى XLSX ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في قسمين خطوات بسيطة. أولاً ، باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تصدير POTX إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل HTML إلى XLSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل POTX إلى XLSX عبر C#" %}}
1. افتح ملف POTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. تصدير POTX بتنسيق HTML باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند في ملف XLSX باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل المحمية POTX إلى XLSX عبر C#" %}}
أثناء تحويل ملف POTX إلى XLSX ، إذا كان مستند POTX الذي تم إدخاله محميًا بكلمة مرور ، فلا يمكنك تحويله إلى XLSX بدون فك تشفير المستند. عندما يكون المستند محميًا بكلمة مرور ، فهذا يعني أنه يفرض قيودًا معينة على العرض التقديمي. لإزالة القيود ، يجب إدخال كلمة المرور. يعتبر العرض التقديمي المحمي بكلمة مرور عرضًا تقديميًا مغلقًا. تسمح لك واجهة برمجة التطبيقات بفتح المستند المشفر عن طريق تمرير كلمة المرور الصحيحة في كائن LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-protected-powerpoint-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل POTX إلى XLSX مع علامة مائية عبر C#" %}}
أثناء تحويل ملف POTX إلى XLSX ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف XLSX الناتج. لإضافة علامة مائية ، يمكنك إنشاء كائن مصنف جديد وفتح مستند HTML المحول ، وتحديد ورقة العمل عبر الفهرس الخاص به ، وإنشاء شكل واستخدام وظيفة AddTextEffect الخاصة به. بعد ذلك يمكنك حفظ مستند HTML كملف XLSX مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "c67832c79481518ab87f3f0b311cb1cd" "convert-powerpoint-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-fods/" name="POTX ل FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xltm/" name="POTX ل XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xlt/" name="POTX ل XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xlam/" name="POTX ل XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-markdown/" name="POTX ل MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-excel/" name="POTX ل EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-mhtml/" name="POTX ل MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xlsb/" name="POTX ل XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-ods/" name="POTX ل ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-sxc/" name="POTX ل SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xls/" name="POTX ل XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xltx/" name="POTX ل XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xlsx/" name="POTX ل XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-tsv/" name="POTX ل TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-dif/" name="POTX ل DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-xlsm/" name="POTX ل XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-doc/" name="POTX ل DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-docx/" name="POTX ل DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-docm/" name="POTX ل DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-dot/" name="POTX ل DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-dotm/" name="POTX ل DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-dotx/" name="POTX ل DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-odt/" name="POTX ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-ott/" name="POTX ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-rtf/" name="POTX ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-word/" name="POTX ل WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-wordml/" name="POTX ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-text/" name="POTX ل TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/potx-to-flatopx/" name="POTX ل FLAلPX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}