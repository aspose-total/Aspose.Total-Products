---
title: تصدير EPUB إلى POTX عبر C# API
description: NET API لتحويل EPUB إلى POTX دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/epub-to-potx/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: POTX
otherformats: PPTM POTX PPT XAML POTM OTP PPSM PPS POWERPOINT PPSX SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم EPUB إلى POTX عبر .NET" h2=".NET API لتصدير EPUB إلى POTX على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض EPUB على POTX في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف EPUB إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى POTX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل EPUB إلى POTX" %}}
1. افتح ملف EPUB باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل EPUB إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق POTX باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Potx` على أنه SaveFormat
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
أثناء تحويل EPUB إلى POTX ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف EPUB. للحصول على البيانات الوصفية لملف EPUB ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف EPUB للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف POTX للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف POTX الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potx", SaveFormat.Potx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EPUB إلى POTX برمجيًا: حالات الاستخدام" %}}
الملخص:

الملفات الإلكترونية (EPUB) هي شائعة لتحميل المحتوى الرقمي، بما في ذلك الكتب الإلكترونية، المقالات، والوثائق. ومع ذلك، عندما يتعلق الأمر بتقديم المعلومات في صيغة مруктуفة، ففايزPowerPoint (.potx) يصبح خياراً مثالياً بسبب طبيعتها الإجرائية والمثيرة.

التحويل من ملفات EPUB إلى صيغ .potx ضروريًا للاستخدام الكامل قدراتك في إنشاء العروض المتعلقة. هذا التحويل يتيح لك:

**الاستخدامات:**

*   **المحاضرات الأكاديمية**: تحويل الملفات الإلكترونية إلى عروض متعلقة لمعرض النتائج الرئيسية و分享 البحث مع زملاءك.
*   **الاتصالporate**: استخدام PowerPoint لتقديم تحديثات الشركة، والانطلاقات المنتشرة، وتrends في الصناعة ب方式 مثيرة.
*   **الموارد التدريبية**: تحويل الملفات الإلكترونية إلى عروض متعلقة لجلسات تدريب معقدة، مما يجعل المعلومات أكثر إمكانية الوصول إليها وسهولة الفهم.
*   **ال出版 الرقمي**: استخدام .potx ل出版 المحتوى عبر الإنترنت مثل blogs، المقالات، والمنطرات مع عناصر متعددة مثل الصور، الفيديوهات، والأнимации.
*   **الموارد التعليمية**: تحويل الملفات الإلكترونية إلى مواد تعليمية متعلقة مثل خطط الدراسة، الدراسات النموذجية، والمشاريع الت教学ية.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}