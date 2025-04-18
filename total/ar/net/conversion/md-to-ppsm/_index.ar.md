---
title: تصدير MD إلى PPSM عبر C# API
description: NET API لتحويل MD إلى PPSM دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/md-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PPSM
otherformats: PPSM POWERPOINT XAML POTM PPSX SWF PPT POTX PPTM PPS POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم MD إلى PPSM عبر .NET" h2=".NET API لتصدير MD إلى PPSM على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض MD على PPSM في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف MD إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل MD إلى PPSM" %}}
1. افتح ملف MD باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل MD إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق PPSM باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Ppsm` على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على XMP Metadata من ملف MD عبر .NET" %}}
أثناء تحويل MD إلى PPSM ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف MD. للحصول على البيانات الوصفية لملف MD ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف MD للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء ملف PPSM للقراءة فقط عبر .NET" %}}
باستخدام واجهة برمجة تطبيقات [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك زيادة تحسين ميزات تطبيق التحويل الخاص بك. يمكن أن تكون إحدى الميزات إنشاء ملف الإخراج الخاص بك للقراءة فقط لزيادة الأمان. تسمح لك واجهة برمجة التطبيقات بتعيين ملف PPSM الخاص بك على "للقراءة فقط" ، مما يعني أن المستخدمين (بعد فتح العرض التقديمي) يرون توصية للقراءة فقط. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف MD إلى PPSM برمجيًا: حالات الاستخدام" %}}
تحويل ملفات markdown إلى عرض幻灯片 بالبرنامج презентي  

ملفات markdown هي مثالية لإنشاء محتوى وثيقة صلبة مثل الدокументات والnotes. ومع ذلك، عندما يتعلق الأمر بتقديم المعلومات المعقدة أو المحتوى المتحرك، يصبح العروض الحلقية بالبرنامج презенти (PPSM) ضروريًا.幸运的是، تحويل ملفات markdown إلى格式 PPSM يساعدك في إطلاق القدرة الكاملة في عرضك.

التحويل من markdown إلى PPSM هو شيء 必须 لتحويل محتوىك النصي الأساسي إلى عرض تفاعلي ومفكر. هذا التحويل ي允许 لك:

**الأستخدامات:**

*   **العروض الارتباعية في الشركات**: تحويل ملفات markdown إلى عروض رائعة للنشر في الأحداث التجارية، والاستطلاع على المنتجات، والمؤتمرات الصناعية.
*   **المحتوى التعليمي**: استخدام PPSM لإنشاء عرض幻灯片 تفاعلية للتعليم، مثل المحاضرات،التعليمات، وкурسات الإنترنت.
*   ** 材料 التسويق**: تحويل markdown إلى مواد تسويقية مثيرة، مثل pitches销售，دمو المنتجات، والمواد العلامية.
*   **ال培训 والتسليم**: استخدام PPSM لإنشاء دروس متخددة للتدريب، programs تسليم الموظفين، و手册 الموظفين.
*   **العروض الشخصية**: تحويل markdown إلى عروض نظرية م专业ة لمن مشاريع شخصية مثل blogs، podcasts، أو فيديوهات يوتيوب.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}