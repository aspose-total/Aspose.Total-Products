---
title: C# API لتصدير البريد الإلكتروني إلى DOC
description: قم بتحويل EMAIL إلى DOC دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى DOC عبر .NET" h2=".NET API لتقديم EMAIL إلى DOC على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMAIL إلى ميزات تحويل DOC داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMAIL إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى DOC" %}}
1. افتح ملف EMAIL باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMAIL إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق DOC باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Doc كـ SaveFormat
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
قبل تحويل EMAIL إلى DOC ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMAIL وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات DOC عبر .NET" %}}
أثناء حفظ المستند من EMAIL إلى DOC ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMAIL إلى DOC برمجيًا: حالات الاستخدام" %}}
تحويل ملفات البريد الإلكتروني إلى وثائق Microsoft Office (DOC)

الملفات البريد الإلكتروني تستخدم广泛ًا في التواصل، لكن عندما يتعلق الأمر بال分享 والتحليل البياني للبيانات، فان الوثائق Microsoft Office تكون ملاذاً أساسيًا. تحويل ملفات البريد الإلكتروني إلى格式 DOC يفتح الباب لاستخدام القدرات الكاملة في إعداد وتحليل الوثائق.

التحويل من البريد الإلكتروني إلى_formats_DOC_يُعد 必须 للاستفادة الكاملة من قدرات إعدادك و تحليلك للوثائق. هذا التحويل يتيح لك:

** استخدامات:**

*   **تقديم提案 مشروع**: تحويل ملفات البريد الإلكتروني إلى وثائق قصيرة وقوية لتقديم مشاريع القدرات، مما يسعى إلى تفاصيل关键ة ومواعيد إجراءات.

*   **دокументات دقوق会议**: استخدام DOC لتنظيم دقوق اجتماع، وتفاصيل أعمال الاجتماع، وأخبار اتخاذ قرارات.

*   **مراجعة العقد و تحليله**: تحويل البريد الإلكتروني إلى وثائق لمراجعة و تحليل العقود، مما يضمن فهم جميع الأعضاء للمصطلحات والشروط بالطريقة التي تتماشى معها.

*   **تقديم السير الذاتية والأحوال**: استخدام DOC لإنشاء سير الذاتية والأحوال باستخدام ش板قms تميزت بالاستخدام من خلاله، مما يسعى إلى تطبيق الأوراق على فرص العمل المفتوحة.

*   **生成会议报告**: استخدام DOC لإنشاء تقارير المؤتمرات، مما يلخص محتويات العروض الرئيسية، والمناقشات، وأخبار النتائج.

بتحويل ملفات البريد الإلكتروني إلى格式 DOC يمكنك إدارة وتحليل احتياجات إعداد الوثائق بكفاءة.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}