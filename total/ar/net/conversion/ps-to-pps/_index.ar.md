---
title: تصدير PS إلى PPS عبر C# API
description: NET API لتحويل PS إلى PPS دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/ps-to-pps/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPS
otherformats: XAML POTX PPS PPTM PPT PPSX POT OTP POTM PPSM POWERPOINT SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PS إلى PPS عبر .NET" h2=".NET API لتصدير PS إلى PPS على أنظمة التشغيل Windows و macOS و Linux بدون استخدام Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام حزمة من واجهات برمجة تطبيقات أتمتة تنسيق الملفات القوية [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة عرض PS على PPS في خطوتين بسيطتين. باستخدام واجهة برمجة تطبيقات معالجة ملفات PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PS إلى PPTX. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة العروض التقديمية [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) ، يمكنك تحويل PPTX إلى PPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل PS إلى PPS" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PS إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. احفظ المستند بتنسيق PPS باستخدام طريقة [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) وعيّن `Pps` على أنه SaveFormat
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
أثناء تحويل PS إلى PPS ، قد تحتاج إلى معلومات بيانات وصفية إضافية لـ XMP لتحديد أولويات عملية تحويل الدُفعات. على سبيل المثال ، يمكنك الحصول على مستندات التحويل وفرزها بناءً على تاريخ الإنشاء ومعالجة المستندات وفقًا لذلك. يسمح لك [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) بالوصول إلى بيانات XMP الوصفية لملف PS. للحصول على البيانات الوصفية لملف PS ، يمكنك إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح ملف PS للإدخال. بعد ذلك ، يمكنك الحصول على البيانات الوصفية للملف باستخدام خاصية [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى PPS برمجيًا: حالات الاستخدام" %}}
الملخص:

- **المورφοغرافيا المحمية (PS files)**: تستخدم لتخزين المعلومات الصورية static graphics، مما يجعلها مثالية لإنشاء لوحات الحدائق وتصميمات.

- **الحصول على العروض المتحركة (PowerPoint presentations)**: عندما تكون هناك بيانات دقيقة، فإن العروض المتحركة مثل PowerPoint تكون 必须ًا لتمثيل المعلومات وتحليلها.

- **تحويل المورفوغرافيا المحمية إلى PPS**: هذا التحويل يتيح استخدام كامل القدرات في عروضك، بما في ذلك إضفاء الإanimaciones والتحولات ومواد متحركة.

**الاستخدامات:**

1. **تصميم الحدائق الإلكترونية**: تحويل المورفوغرافيا المحمية إلى PPS لإنشاء حديقة إلكترونية جذابة، وإضفاء أنيميشن وتأثيرات متعددة.

2. ** 材料 تعليمية و تدريبية**: استخدام PPS لإنشاء دروس تعليمية تفاعلية، محاكيات، وتعليقات تفاعلية للشريكين، مما يساعد على زيادة فرط التذكر والتفاعل.

3. **提案商业 و عروض**: تحويل المورفوغرافيا المحمية إلى PPS لإنشاء اقتراحات قوية وعروض ت展示 المنتجات أو الخدمات أو الأفكار، مما يساعد على التواصل بشكل أفضل مع العملاء أو المستثمرين.

4. ** 材料 تسويق**: استخدام PPS لإنشاء مواد تسويقية مثل الدعوات والكارتونات والبroschures وleaflets وposters، مما يساعد على إعلان المنتجات أو الخدمات بCONTENT فيزيوًاً جذابًا.

5. **التصوير البياني للبيانات وتلقي القصص**: تحويل المورفوغرافيا المحمية إلى PPS لإنشاء قصص تفاعلية، تصاویر البيانات، و التقارير التي تساعد على عرض المعلومات الصعبة ب方式 مثيرة.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}