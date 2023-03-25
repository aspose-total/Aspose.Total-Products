---
title: تحويل تنسيق JSON إلى POWERPOINT عبر .NET
description: تحليل JSON إلى POWERPOINT في C# بدون استخدام Microsoft PowerPoint
url_ignore: /ar/net/conversion/json-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPT
otherformats: OTP PPS PPSM PPTM POTX PPT POTM POWERPOINT POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى POWERPOINT عبر C#" h2="C# API لتحليل JSON إلى POWERPOINT بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل JSON إلى POWERPOINT في أي تطبيق .NET و C# و ASP.NET و VB.NET بخطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) ، يمكنك تحليل JSON إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى POWERPOINT. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى POWERPOINT عبر C#" %}}
1. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) جديد  واقرأ بيانات JSON الصالحة من الملف
2. استيراد ملف JSON إلى ورقة العمل باستخدام فئة [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) و [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)  أنها PPTX
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق POWERPOINT باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تعيين التخطيط وتحويل تنسيق JSON إلى POWERPOINT عبر C#" %}}
أثناء تحليل JSON إلى POWERPOINT ، يمكنك أيضًا تعيين خيارات التخطيط لتنسيق JSON باستخدام [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). يتيح لك معالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل تنسيق JSON إلى POWERPOINT مع العلامة المائية" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى POWERPOINT بعلامة مائية. لإضافة علامة مائية إلى مستند POWERPOINT الخاص بك ، يمكنك أولاً تحليل JSON إلى PPTX وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PPTX الذي تم إنشاؤه حديثًا باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) ، حدد العرض التقديمي الرئيسي ، أضف نوع الشكل باستخدام AddAutoShape وإضافة نص العلامة المائية باستخدام AddTextFrame. بعد إضافة العلامة المائية ، يمكنك حفظ المستند في POWERPOINT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}