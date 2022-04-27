---
title: تحويل تنسيق JSON إلى TGA عبر .NET
description: تحليل JSON إلى TGA في C# بدون استخدام تبعيات الطرف الثالث
url: /ar/net/conversion/json-to-tga/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: TGA
otherformats: EMZ PSD IMAGE TGA DXF WMZ WMF JPEG2000 SVGZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى TGA عبر C#" h2="C# API لتحليل JSON إلى TGA دون استخدام تبعيات الطرف الثالث" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك تحليل JSON إلى TGA ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في قسمين بسيطين خطوات. أولاً ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ، يمكنك تصدير JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) ، يمكنك تحويل JPEG إلى TGA.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى TGA عبر C#" %}}
1. قم بإنشاء كائن [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) جديد  واقرأ بيانات JSON من ملف
2. تحويل JSON إلى JPEG باستخدام طريقة [Save](https://apireference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق TGA باستخدام طريقة [Save](https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تعيين التخطيط وتحويل تنسيق JSON إلى TGA عبر C#" %}}
أثناء تحليل JSON إلى TGA ، يمكنك أيضًا تعيين خيارات التخطيط لـ JSON باستخدام [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). يسمح لك بمعالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحليل تنسيق JSON إلى TGA باستخدام العلامة المائية" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى TGA بعلامة مائية في مستند TGA الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل مستند JSON إلى JPEG وإضافة علامة مائية فيه. لتوضيح العملية ، يمكنك تحميل صورة JPEG المحولة وإضافة تحويلات باستخدام كائن من فئة Matrix ورسم سلسلة كعلامة مائية على سطح الصورة باستخدام [Grpahics](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics) class '[DrawString](https://apireference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). بعد إضافة العلامة المائية إليها ، يمكنك حفظ JPEG بتنسيق TGA. يوجد أدناه مثال رمز يوضح كيفية إضافة علامة مائية قطرية إلى المستند الخاص بك. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-wmz/" name="JSON ل WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dicom/" name="JSON ل DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-psd/" name="JSON ل PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-jpeg2000/" name="JSON ل JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-tga/" name="JSON ل TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-emz/" name="JSON ل EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-svgz/" name="JSON ل SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-wmf/" name="JSON ل WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-image/" name="JSON ل IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dxf/" name="JSON ل DXF" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}