---
title: C# API لتصدير البريد الإلكتروني إلى JPEG
description: قم بتحويل EML إلى JPEG دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/eml-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: JPEG
otherformats: FLATOPC DOTX DOC PDF EPUB DOCM DOTM JPEG TEXT PCL PS OTT DOCX GIF MD XPS RTF SVG PNG WORDML DOT EMF TIFF ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى JPEG عبر .NET" h2=".NET API لتقديم EML إلى JPEG على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EML إلى ميزات تحويل JPEG داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى JPEG" %}}
1. افتح ملف EML باستخدام فئة [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. تحويل EML إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق JPEG باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Jpeg كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EML إلى JPEG ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EML وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات JPEG عبر .NET" %}}
أثناء حفظ المستند من EML إلى JPEG ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EML إلى JPEG برمجيًا: حالات الاستخدام" %}}
الملفات الالكترونية (EML) تستخدم لتحميل الرسائل النصية، مما يجعلها مثالية لإنشاء فيизيالات بسيطة للنصائح أو العلامات القصيرة. ومع ذلك، عندما تكون هناك عناصر VISUALS جاذبة مثل الصور والفيديوهات المتحركة، فإن الملفات JPEG (مجموعة专家 الفوتوغرافية المشتركة) تصبح أساسية ل分享 و عرض البيانات.

التحويل من ملفات EML إلى صيغ JPEG ضروري لتطوير قدراتك في إنشاء وتقديم العروض المرئية وال分享. هذا التحويل يتيح لك:

**الاستخدامات:**

*   ** الحملات الإلكترونية للبريد الإلكتروني**: تحويل الملفات EML إلى برامج بريد إلكتروني مرئية، بما في ذلك عروض الصور، وال帖ات الاجتماعية، والعلامات القصيرة.
*   **النشرات والblogs**: استخدام JPEG لمنشورات البريد الإلكتروني والblogs، مما يجعلها أكثر جاذبية للقراء.
*   **分享 على منصات اجتماعية**: تحويل الملفات EML إلى محتوى مرئي يمكن مشاركته على منصات مثل Twitter وFacebook وLinkedIn.
*   **集成 في بريد الألكتروني**: تحويل الملفات EML لإنشاء клиенты بريد إلكتروني مخصصين مع interfaces مرئية ومجربة.
*   **تقديم البيانات والتقارير**: استخدام JPEG لتقديم البيانات ب方式 أكثر جاذبية، مما يساعد الحكمة على فهم المعلومات المعقدة بشكل أسهل.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}