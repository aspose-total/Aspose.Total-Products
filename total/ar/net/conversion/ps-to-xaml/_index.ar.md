---
title: تصدير PS إلى XAML عبر C# API
description: NET API لتحويل PS إلى XAML دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PS إلى XAML عبر .NET" h2=".NET API لتصدير PS إلى XAML على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض PS على XAML في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PS إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل PS إلى XAML" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PS إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق XAML باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Xaml` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على XMP Metadata من ملف PS عبر .NET" %}}
أثناء تحويل PS إلى XAML ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف PS. للحصول على البيانات الوصفية لملف PS ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف PS للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف XAML للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف XAML الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى XAML برمجيًا: حالات الاستخدام" %}}
ملفات PS (Portable Document Format) تستخدم لتخزين معلومات الصور الرسومية بال形式矢量ية، مما يجعلها مثالية لإنشاء الصور الثابتة، الشعارات، والillustrations. ومع ذلك، عندما نعمل مع البيانات动态، يصبح XAML (Extensible Application Markup Language) ضروريًا لبناء interfaces المستخدمين و تطبيقات الأجهزة.

الترخيص من ملفات PS إلى صيغ XAML هي必要ية لتمكين قدراتك في تطوير تطبيقاتك. هذه الترخيص تسمح لك:

** استخدامات:**

* **تطوير تطبيقات الهاتف المحمول**: تحويل ملفات PS إلى تطبيقات محمولة مع interfaces المستخدمين友好، باستخدام قوة XAML ل تجربة المستخدمين متماسكة.
* **تطوير تطبيقات سطح المكتب**: استخدام XAML لبناء تطبيقات سطح المكتب القوية والمقاومة للزيادة،Exploiting قوة اللغة في تحديد البيانات، والAnimations، والTemplate.
* **bibliothèques من組件 UI**: تحويل ملفات PS إلى組件 UI م可复用的 مثل الأزرار، المجالات النصية، والنوافذ، باستخدام XAML لتصميم الكفاءة والمحافظة.
* **الرسوميات 3D والAnimations**: استخدام XAML لجعل الرسوميات 3D والAnimations حياة في تطبيقاتك، مزيج قوة الصور الرسومية مع灵活ية لغة الماركة.
* **المستخدمين وخصائص التطبيق**: تحويل ملفات PS إلى عناصر UI متاحة ومخصصة، مما يجعل تطبيقاتك تلبيط需求ات المستخدمين المختلفة وال تفضيلات.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}