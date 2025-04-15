---
title: C# API لتصدير CGM إلى MARKDOWN
description: تحويل CGM إلى MARKDOWN دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/cgm-to-markdown/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: MARKDOWN
otherformats: MARKDOWN WORDML DOTX DOT DOTM XAMLFLOW FLATOPC ODT OTT RTF PCL MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم CGM إلى MARKDOWN عبر .NET" h2=".NET API لتصدير CGM إلى MARKDOWN على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف CGM إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى MARKDOWN.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل CGM إلى MARKDOWN" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى Doc باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق MARKDOWN باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Markdown كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف CGM باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل CGM إلى MARKDOWN ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح CGM باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly MARKDOWN- ملف عبر .NET" %}}
من أجل حماية MARKDOWN الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.markdown", SaveFormat.Markdown);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى MARKDOWN برمجيًا: حالات الاستخدام" %}}
الملخص:

الملف CGM (Computer Graphics Metafile) يستخدم لتحميل معلومات حول الصور النصية، مما يجعلها مثالية لإنشاء الصور والرسوم البيانيةstatic. ومع ذلك، عندما نعمل مع البيانات المتحركة، مثل في جداول Excel، تصبح هذه الملفات أساسية لتنظيم وتحليل البيانات وتمثيلها.

التحويل من الملفات CGM إلى صيغ Markdown ضروري لتطوير القدرات الكاملة على عرض البيانات وتوثيقها. هذا التحويل يتيح لك استخدام:

**الاستخدامات:**

*   **توثيق الصور النصية**: تحويل الملفات CGM لإنشاء وثائق تفصيلية تفاعلية للprojects الصوريةstatic، مما يساعد الفنانين والمطورين والشريكين على العمل معًا.
*   **كتب البيانات**: استخدام Markdown لتمثيل نظريات البيانات المعقدة، مما ي创造 قصة مثيرة ت传达 النتائج الرئيسية والتrends والpatterns في البيانات.
*   **إدارة الأصول الرقمية**: تحويل الملفات CGM لإنشاء مركز مركزي لإدارة الأصول الرقمية مثل الصور النصية، اللوغوهات، والأيقونات، مما يساعد على متابعة استخدامها وتعديلاتها وعدالتها.
*   **الكتابة العلمية والبحث**: استخدام Markdown لتقديم النتائج البحثية المعقدة، بما في ذلك الأنموذجيات 3D، نتياجات المحاكاة، ونتائج التجارب، في صيغة容易 الفهم للباحثين الكتابين والقراء.
*   **إنشاء محتوى ويب تفاعلي**: تحويل الملفات CGM لإنشاء محتوى ويب تفاعلي مثل الأнимации والمحاكيات والرسوم البيانية، مما يلعب دورًا في تعزيز الاهتمام من خلال conveying المعلومات المعقدة وتسهيل الفهم.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}