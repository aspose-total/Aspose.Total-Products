---
title: تصدير EPUB إلى PPSX عبر C# API
description: NET API لتحويل EPUB إلى PPSX دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/epub-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: PPSM POTX PPT PPS XAML OTP PPTM PPSX POTM POT SWF POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم EPUB إلى PPSX عبر .NET" h2=".NET API لتصدير EPUB إلى PPSX على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض EPUB على PPSX في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف EPUB إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل EPUB إلى PPSX" %}}
1. افتح ملف EPUB باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل EPUB إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق PPSX باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Ppsx` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على XMP Metadata من ملف EPUB عبر .NET" %}}
أثناء تحويل EPUB إلى PPSX ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف EPUB. للحصول على البيانات الوصفية لملف EPUB ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف EPUB للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف PPSX للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف PPSX الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EPUB إلى PPSX برمجيًا: حالات الاستخدام" %}}
تحويل ملفات EPUB إلى صيغ PPSX هو أساسي للاستخدام الكامل لمحتوى العروض الالكترونية  

ملفات EPUB (Electronic Publication) تستخدم على نطاق واسع لتخزين و分享 المحتوى الإلكتروني، مثل الكتب الإلكترونية والمقالات والعلامات التفاعلية. ومع ذلك، عندما يتعلق الأمر بالعروض، مثل العروض التي تُ创建 باستخدام Microsoft PowerPoint، فمن المهم أن تكونملفات EPUB أقل من المثالية بسبب محدوديتها في تقديم الصور والillustrations الدقيقة.

لذلك، تحول ملفات EPUB إلى صيغ PPSX (PowerPoint XML) هو 必要ية للاستخدام الكامل لمحتوى العروض وتتمكنك من:

**الاستخدامات:**

*   **العروض الالكترونية في الشركات**: تحويل ملفات EPUB إلى عروض PowerPoint محددة وم专业ة، بما في ذلك الصور والillustrations التفاعلية والأفلام.
*   **العروض الأكاديمية**: استخدام صيغ PPSX لتمثيل البيانات المتقدمة مثل نتائج البحث العلمي و التحليل الإحصائي ب方式 تفاعلية وممتعة.
*   **المواد التسويقية والventas**: تحويل ملفات EPUB إلى مواد تسويقية جذابة، مثل demos المنتجات وتعليقات العملاء، التي يمكن مشاركتها بسهولة مع الزملاء والمستخدمين.
*   **العروض التعليمية**: استخدام صيغ PPSX لإنشاء عروض تفاعلية للطلاب، بما في ذلك المحتوى المتحرك والتفاعل والعقوبات.
*   **العروض في المؤتمرات**: تحويل ملفات EPUB إلى عروض محددة ومحترمة للمؤتمرات، بما في ذلك التأثيرات الفنية مثل التحول بين الصور وتأثيرات العرض.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}