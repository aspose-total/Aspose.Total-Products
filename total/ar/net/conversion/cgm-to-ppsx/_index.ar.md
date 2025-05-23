---
title: تصدير CGM إلى PPSX عبر C# API
description: NET API لتحويل CGM إلى PPSX دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/cgm-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSX
otherformats: PPT POWERPOINT POTX POTM PPS SWF PPSM PPTM XAML OTP POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم CGM إلى PPSX عبر .NET" h2=".NET API لتصدير CGM إلى PPSX على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض CGM على PPSX في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف CGM إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل CGM إلى PPSX" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق PPSX باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Ppsx` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على XMP Metadata من ملف CGM عبر .NET" %}}
أثناء تحويل CGM إلى PPSX ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف CGM. للحصول على البيانات الوصفية لملف CGM ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف CGM للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى PPSX برمجيًا: حالات الاستخدام" %}}
تحويل ملفات CGM (ملف واجهة النماذج الحاسوبية) إلى PPSX (ملف عرض PowerPoint XML من شركة مايكروسوفت) يمنحك القدرة على إطلاق التمثيل الكامل لبيانات العرض البيانية والتحليل. هذا التحويل ضروريًا لاستخدام قوة الميزات الإجرائية في PowerPoint مثل الإanimaciones، والعوامل التفاعلية، ومحتويات الأصوات والنصوص المتحركة.

تحويل ملفات CGM إلى صيغ PPSX يفتح استخدامات عديدة:

** الاستخدامات:**

*   **تصميم وتنفيذ العروض البيانية**: تحويل ملفات CGM إلى عروض قوية ومثيرة، والتمثيلات التفاعلية التي ت吸引 الانتباه من الجمهور.
*   **القصة البيانية بناءً على البيانات**: استخدام PPSX لدمج معاني البيانات المعقدة في العروض، مما يتيح إخبار القصة بشكل فعال عبرالتمثيل والتفاعل.
*   **التواصل الحكومي والتقارير**: تحويل CGM إلى تقارير محترمة و لوحات بيانية للشاهدين، مما يساعد على اتخاذ القرارات المدروسة.
*   **الحملات التسويقية والأعلانات**: استخدم PPSX لدمج المحتوى المتحرك مثل الأصوات والفيديوهات في العروض، مما يزيد من قوة الرسائل التسويقية والأعلانية.
*   **العروض الأكاديمية والمابحث العلمي**: استخدام PPSX لإنشاء عروض بحثية محترمة ت包含 التمثيلات البيانية المعقدة والتمثيلات التفاعلية والمحتويات المتحركة.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}