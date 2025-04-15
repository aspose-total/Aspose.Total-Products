---
title: تصدير PS إلى SWF عبر C# API
description: NET API لتحويل PS إلى SWF دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: PPSM POTM OTP POWERPOINT PPS PPTM POT POTX XAML SWF PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PS إلى SWF عبر .NET" h2=".NET API لتصدير PS إلى SWF على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض PS على SWF في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PS إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل PS إلى SWF" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PS إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق SWF باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Swf` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على XMP Metadata من ملف PS عبر .NET" %}}
أثناء تحويل PS إلى SWF ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف PS. للحصول على البيانات الوصفية لملف PS ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف PS للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف SWF للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف SWF الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى SWF برمجيًا: حالات الاستخدام" %}}
**ملفات PS (Portable Scribbler)** تُستخدم لstorage من المعلومات في الوثائق، مما يجعلها مثالية لإنشاء وثائق ثابتة ودعائم. ومع ذلك، عندما نعمل مع محتوى الإعلام المتحرك المتعدد الوسائح، ففيئات SWF (Small Web Format) تكون 必须 لتشغيلها وdisplay.

التحويل من ملفات PS إلى صيغ SWF هو ضروري للاستخدام الكامل لمحتوى الإعلام المتحرك المتعدد الوسائح. هذا التحويل يتيح لك:

**الاستخدامات:**

*   ** محتوى التعلم الإلكتروني الممتع**: تحويل ملفات PS إلى مساعدات تعليمية在线 ممتعة، مثل الدروس والتعليمات والموارد التعليمية التي يمكن تشغيلها على أجهزة مختلفة.
*   **قطاع الأفلام والبرامج التلفزيونية animated**: استخدام ملفات SWF لتعزيز تفاعل الأفلام والبرامج التلفزيونية، مما يجعل المحتوى أكثر جاذبية للنظرة.
*   **أصول الفيديو الجيء وأفاصيل الإجراء**: تحويل ملفات PS إلى أصول الفيديو الجيء وأفاصيل الإجراء المتفاعلة التي تزيد من تجربة لعب اللعبة.
*   **تطبيقات الويب والتمارين**: استخدام ملفات SWF لبناء تطبيقات ويب متفاعلة وتمارين توفر تجارب مimmerسية.
*   ** محتوى التطبيقات المحمولة والعلانات**: تحويل ملفات PS إلى محتوى تطبيقات محمولة وممتع، والعلانات التي ت привлек النزاهة من خلال الجلد.

الترجمة الم 完成.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}