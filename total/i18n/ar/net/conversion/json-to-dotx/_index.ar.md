---
title: تحويل تنسيق JSON إلى DOTX عبر .NET
description: تحليل JSON إلى DOTX في C# بدون استخدام Microsoft Word
url: /ar/net/conversion/json-to-dotx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOC PCL EPUB FLATOPC DOCM ODT WORDML DOTX WORD MOBI PS DOT RTF OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى DOTX عبر C#" h2="C# API لتحليل JSON إلى DOTX بدون استخدام Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) ، يمكنك تحليل JSON إلى DOTX ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في عمليتين بسيطتين خطوات. أولاً ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ، يمكنك تصدير JSON إلى PDF. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل PDF إلى DOTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى DOTX عبر C#" %}}
1. قم بإنشاء كائن [مصنف] جديد (https://apireference.aspose.com/cells/net/aspose.cells/workbook) واقرأ بيانات JSON الصالحة من الملف
2. استيراد ملف JSON إلى ورقة العمل باستخدام فئة [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) و [Save](https://apireference.aspose.com/ خلايا / صافي / aspose.cells.workbook / حفظ / طرق / 4) كملف PDF
3. قم بتحميل مستند PDF باستخدام فئة [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق DOTX باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى DOTX عب]( #" %}}
أثناء تحليل JSON إلى DOTX ، يمكنك أيضًا تعيين خيارات التخطيط لـ JSON باستخدام [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). يسمح لك بمعالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحليل تنسيق JSON إلى DOTX باستخدام العلامة المائية" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى DOTX بعلامة مائية. من أجل إضافة علامة مائية إلى مستند DOTX ، يمكنك أولاً تحليل ملف JSON إلى PDF وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PDF الذي تم إنشاؤه حديثًا باستخدام فئة [Document](https://apireference.aspose.com/words/net/aspose.words/document) ، وأنشئ مثيلاً لـ TextWatermarkOptions وعيّن خصائصه ، استدعاء طريقة Watermark.SetText وتمرير نص العلامة المائية وكائن خيارات TextWatermarkOptions. بعد إضافة العلامة المائية ، يمكنك حفظ المستند في غرفة تبادل المعلومات. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-ott/" name="JSON ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-flatopc/" name="JSON ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-ps/" name="JSON ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dotx/" name="JSON ل DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-rtf/" name="JSON ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-wordml/" name="JSON ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-odt/" name="JSON ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-word/" name="JSON ل WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-epub/" name="JSON ل EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-doc/" name="JSON ل DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dot/" name="JSON ل DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-pcl/" name="JSON ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-mobi/" name="JSON ل MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-docm/" name="JSON ل DOCM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}