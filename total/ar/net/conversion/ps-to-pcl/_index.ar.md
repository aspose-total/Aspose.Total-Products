---
title: C# API لتصدير PS إلى PCL
description: تحويل PS إلى PCL دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/ps-to-pcl/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PCL
otherformats: MHTML WORDML MARKDOWN DOTM FLATOPC XAMLFLOW ODT DOTX RTF PCL OTT DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PS إلى PCL عبر .NET" h2=".NET API لتصدير PS إلى PCL على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PS إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل PS إلى PCL" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PS إلى Doc باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق PCL باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Pcl كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف PS باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل PS إلى PCL ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح PS باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly PCL- ملف عبر .NET" %}}
من أجل حماية PCL الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى PCL برمجيًا: حالات الاستخدام" %}}
الملخص:

الملفوف PostScript (PS) يستخدم لتحميل معلومات الصور الرسومية، مما يجعلها مثالية لإنشاء صور مركبة معقدة وفنون الرسوم. ومع ذلك، عندما نعمل مع البيانات الصورية المتصورة (EPS - Encapsulated PostScript)، فإن الملفات EPS تصبح أساسية لتحكم دقيق في التنسيق وال设计.

الترخيص من ملف PS إلى صيغ EPS هي必要ية لتمكين القدرات الكاملة على تصميمك. هذه الترخيص تتيح لك استخدام الملفات EPS في:

**الاستخدامات:**

*   **تصميم الشعارات وbranding**: تحويل ملف PS إلى شعار فيكتور، الحفاظ على القدرة على التقليل/الزيادة، وتحقق من دقة الصورة في مختلف الوسائل.
*   **الوثائق الفنية والillustrations**: استخدام EPS لإنشاء صور فنية تفصيلية، تحديد تصميمات معقدة، وتقديم معلومات فنية دقيقة.
*   **التصميم الجرافيكي والنشر**: تحويل ملف PS إلى صور عالية الجودة، إنتاج نشرات محترفة، وتنفيذ معايير التصميم.
*   **الرؤية الفنية في الهندسة المعمارية**: استخدام EPS لvisualizing النماذج المعقدة، المحاكاة من خلال رؤية واقعية، وتقديم مفاهيم تصميم.
*   **الرؤية البيانية والتقارير**: تحويل ملف PS إلى رؤيات بيانية قوية، عرض البيانات معقدة ب方式 جذابة، وتحسين الفهم من خلال المعلومات الفنية.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}