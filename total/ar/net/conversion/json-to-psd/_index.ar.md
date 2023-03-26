---
title: تحويل تنسيق JSON إلى PSD عبر .NET
description: تحليل JSON إلى PSD في C# بدون استخدام تبعيات الطرف الثالث
url_ignore: /ar/net/conversion/json-to-psd/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PSD
otherformats: EMZ WMZ PSD WMF JPEG2000 DXF DICOM IMAGE SVGZ TGA
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى PSD عبر C#" h2="C# API لتحليل JSON إلى PSD دون استخدام تبعيات الطرف الثالث" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك تحليل JSON إلى PSD ضمن أي تطبيق .NET و C# و ASP.NET و VB.NET في قسمين بسيطين خطوات. أولاً ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ، يمكنك تصدير JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) ، يمكنك تحويل JPEG إلى PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى PSD عبر C#" %}}
1. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) جديد  واقرأ بيانات JSON من ملف
2. تحويل JSON إلى JPEG باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق PSD باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تعيين التخطيط وتحويل تنسيق JSON إلى PSD عبر C#" %}}
أثناء تحليل JSON إلى PSD ، يمكنك أيضًا تعيين خيارات التخطيط لـ JSON باستخدام [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). يسمح لك بمعالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحليل تنسيق JSON إلى PSD باستخدام العلامة المائية" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى PSD بعلامة مائية في مستند PSD الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل مستند JSON إلى JPEG وإضافة علامة مائية فيه. لتوضيح العملية ، يمكنك تحميل صورة JPEG المحولة وإضافة تحويلات باستخدام كائن من فئة Matrix ورسم سلسلة كعلامة مائية على سطح الصورة باستخدام [Grpahics](https://reference.aspose.com/imaging/net/aspose.imaging/graphics) class '[DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). بعد إضافة العلامة المائية إليها ، يمكنك حفظ JPEG بتنسيق PSD. يوجد أدناه مثال رمز يوضح كيفية إضافة علامة مائية قطرية إلى المستند الخاص بك. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}