---
title: C# API لتصدير البريد الإلكتروني إلى WORDML
description: قم بتحويل EMAIL إلى WORDML دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORDML
otherformats: MD TIFF OTT DOCM EMF DOTM PNG SVG DOT TEXT DOTX DOCX PDF DOC WORDML GIF FLATOPC EPUB ODT JPEG XPS RTF PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى WORDML عبر .NET" h2=".NET API لتقديم EMAIL إلى WORDML على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMAIL إلى ميزات تحويل WORDML داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMAIL إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى WORDML" %}}
1. افتح ملف EMAIL باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMAIL إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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
قبل تحويل EMAIL إلى WORDML ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMAIL وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات WORDML عبر .NET" %}}
أثناء حفظ المستند من EMAIL إلى WORDML ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMAIL إلى WORDML برمجيًا: حالات الاستخدام" %}}
الملفات الإلكترونية用于 تخزين معلومات التواصل النصي، مما يجعلها مثالية لمرسلين المعلومات. ومع ذلك، عندما يتعامل مع البيانات المتعلقة بالPRESENTATIONS، ففайلات WordML (لغة markup للكلمات) تصبح أساسية لإنشاء وثائق محترمة ومحتوى تعليمية.

التحويل من الملفات الإلكترونية إلى صيغ WordML يساعد في تفعيل القدرات الكاملة على إنشاء الوثائق والمحتوى المتعلقة بالPRESENTATIONS. هذا التحويل يتيح لك:

** استخدامات:**

*   **التواصل الأعمال**: تحويل الملفات الإلكترونية لإنشاء التقارير وال提案 والدossiers الرسمية.
*   **设计 الحفلات**: استخدام WordML لإنشاء محتوى حفلات جذابة، إضافة عناصر متعددة الوسائط، وضمان الميزات التفاعلية.
*   **模板 الوثائق**: تحويل الملفات الإلكترونية لإنشاء شаблоны مكررة للوثائق التي تُستخدم بانتظام، مثل العقود والسياسات.
*   **التعاون في البحث**: استخدام WordML ل分享 نتائج البحث، التعاون مع زملاء، وتبادل التقارير.
*   **إنتاج المحتوى التسويقي**: تحويل الملفات الإلكترونية لإنشاء مادة تسويقية، مقالات بلوق، ورسائل 社交媒体.

بتحويل برودكاسترائكم إلى صيغة WordML، يمكنكم تفعيل إمكانيات جديدة في إنشاء الوثائق، تصميم الحفلات، والتعاون.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}