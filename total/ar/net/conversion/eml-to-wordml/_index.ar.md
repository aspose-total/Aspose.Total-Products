---
title: C# API لتصدير البريد الإلكتروني إلى WORDML
description: قم بتحويل EML إلى WORDML دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORDML
otherformats: FLATOPC ODT RTF DOT WORDML DOTX PCL TIFF XPS SVG JPEG MD DOCM OTT DOC DOTM PNG DOCX EPUB EMF TEXT PS PDF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى WORDML عبر .NET" h2=".NET API لتقديم EML إلى WORDML على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EML إلى ميزات تحويل WORDML داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى WORDML" %}}
1. افتح ملف EML باستخدام فئة [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. تحويل EML إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق WORDML باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Wordml كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EML إلى WORDML ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EML وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات WORDML عبر .NET" %}}
أثناء حفظ المستند من EML إلى WORDML ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EML إلى WORDML برمجيًا: حالات الاستخدام" %}}
ملفات EML (لغة markup النص الأساسي) تستخدم لتحميل الرسائل النصية البسيطة، مما يجعلها مثالية لل通信 عبر البريد الإلكتروني البسيط. ومع ذلك، عندما نعمل مع البيانات التي تكون في شكل وثائق، فان لغة WordML (لغة markup DOC) تصبح 必不可少ًا لتنسيق النصوص وتحديد الطراز.

تحويل ملفات EML إلى formats WordML هو من الضرورة لتمكينك من إمكانات تحرير النصوص وال出版 الكاملة. هذا التحول يتيح لك:

**الاستخدامات:**

*   **تحرير النصوص وال出版**: تحويل ملفات EML إلى format WordML لتحرير النصوص والpublication، مما يساعدك على الحفاظ على التنسيق والطريقة المستمرة.
*   **ال模板 البريدية وجوزئات السيرة الذاتية**: استخدام لغة WordML لإنشاء شабون بريدية و جوزئات سير الذاتية، مما يضمن لك مظهرًا محترمًا وممتازًا.
*   **إنتاج التقارير وال出版ات**: تحويل ملفات EML إلى formats WordML لإنتاج التقارير والكتب白皮书 المقروء والمقالات وغيرها من النصوص الأكاديمية.
*   ** 材料 الحملة التسويقية: استخدام لغة WordML لإنشاء مادة الحملة التسويقية مثل الدعانات والر676فلي وال内容 الاجتماعي.
*   **الكتابة الأكاديمية والمساعدة البحثية: تحويل ملفات EML إلى formats WordML لتنسيق النصوص الأكاديمية والtheses والرسائل البحثية، مما يساعدك على إجراء المراجع الصحيحة وال引用 المناسب.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}