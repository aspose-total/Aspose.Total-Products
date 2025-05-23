---
title: تصدير CGM إلى PPS عبر C# API
description: NET API لتحويل CGM إلى PPS دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/cgm-to-pps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPS
otherformats: PPSM PPS PPTM POWERPOINT PPT PPSX XAML POTM POTX SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم CGM إلى PPS عبر .NET" h2=".NET API لتصدير CGM إلى PPS على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض CGM على PPS في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف CGM إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل CGM إلى PPS" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق PPS باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Pps` على أنه SaveFormat
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
أثناء تحويل CGM إلى PPS ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف CGM. للحصول على البيانات الوصفية لملف CGM ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف CGM للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف PPS للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف PPS الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى PPS برمجيًا: حالات الاستخدام" %}}
الملخص:

الملف CGM (Computer Graphics Metafile) يستخدم لstorage من المعلومات حول الصور النصية، مما يجعلها مثالية لإنشاء الصور والillustrations static. ومع ذلك، عندما نعمل مع البيانات المتحركة، فإن spreadsheets مثل Excel يصبحون أساسيين لvisualizations وanalysis.

التحويل من الملفات CGM إلى صيغ PPS (Portable Presentation) هو 必要 step لunlocking潜力 العروض والvisualizations. هذا التحويل ي允许ك:

** استخدامات:**

*   **设计演示**: تحويل الملفات CGM لإنشاء عروض محترفة مع أنيميشنات وtransitions جذابة للنظرات.
*   **التعليم والتعليم**: استخدام PPS لإنشاء مادة تعليمية تفاعلية، simulations، وتutorials لتحسين النتائج التعليمية.
*   **المواد التسويقية**: تحويل الملفات CGM لإنشاء مواد تسويقية قوية، demos المنتجات، والمواد التسويقية.
*   **ال通信 الداخلي في الشركة**: استخدام PPS لإنشاء communications إ内部ية، التقارير، والinfographics لتحقيق تبادل المعلومات بشكل أفضل.
*   **الvisualizations في الأحداث والأع幕ات**: تحويل الملفات CGM لإنشاء графiken العروض الرائعة، تصميم المعرض، وdisplays التrade shows.

تحويل ملفات CGM إلى صيغ PPS ي允许ك استخدام最新features في برامج العروض، بما في ذلك أنيميشنات متقدمة، transitions، والeffets. هذا التحويل يضمن أن محتوى العرض يظهر ب形式ه الأفضل، مما يجعل هذا الخطوة أساسية ل أي مشروع يتطلب عروضًا محترفة بالجودة.

الترجمة العربية:

الملف CGM (Computer Graphics Metafile) يستخدم لstorage من المعلومات حول الصور النصية، مما يجعلها مثالية لإنشاء الصور والillustrations static. ومع ذلك، عندما نعمل مع البيانات المتحركة، فإن spreadsheets مثل Excel يصبحون أساسيين لvisualizations وanalysis.

التحويل من الملفات CGM إلى صيغ PPS (Portable Presentation) هو 必要 step لunlocking潜力 العروض والvisualizations. هذا التحويل ي允许ك:

** استخدامات:**

*   **设计演示**: تحويل الملفات CGM لإنشاء عروض محترفة مع أنيميشنات وtransitions جذابة للنظرات.
*   **التعليم والتعليم**: استخدام PPS لإنشاء مادة تعليمية تفاعلية، simulations، وتutorials لتحسين النتائج التعليمية.
*   **المواد التسويقية**: تحويل الملفات CGM لإنشاء مواد تسويقية قوية، demos المنتجات، والمواد التسويقية.
*   **ال通信 الداخلي في الشركة**: استخدام PPS لإنشاء communications إ内部ية، التقارير، والinfographics لتحقيق تبادل المعلومات بشكل أفضل.
*   **الvisualizations في الأحداث والأع幕ات**: تحويل الملفات CGM لإنشاء графiken العروض الرائعة، تصميم المعرض، وdisplays التrade shows.

تحويل ملفات CGM إلى صيغ PPS ي允许ك استخدام最新features في برامج العروض، بما في ذلك أنيميشنات متقدمة، transitions، والeffets. هذا التحويل يضمن أن محتوى العرض يظهر ب形式ه الأفضل، مما يجعل هذا الخطوة أساسية ل أي مشروع يتطلب عروضًا محترفة بالجودة.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}