---
title: C# API لتصدير البريد الإلكتروني إلى RTF
description: قم بتحويل EMLX إلى RTF دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/emlx-to-rtf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: RTF
otherformats: EMF EPUB TEXT OTT PS PNG GIF DOT DOC DOTM DOTX MD DOCM ODT JPEG XPS DOCX TIFF SVG WORDML PDF FLATOPC RTF PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى RTF عبر .NET" h2=".NET API لتقديم EMLX إلى RTF على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل RTF داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى RTF" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق RTF باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Rtf كـ SaveFormat
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
قبل تحويل EMLX إلى RTF ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات RTF عبر .NET" %}}
أثناء حفظ المستند من EMLX إلى RTF ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMLX إلى RTF برمجيًا: حالات الاستخدام" %}}
ملفات إلكترونية باستخدام X.400 (EMLX) تُستخدم لstorage معلومات إلكترونية نصية، مما يجعلها مثالية لإنشاء بريد إلكتروني بسيط و newsletters. ومع ذلك، عندما يتعامل مع البيانات المتراكمة التي تحتاج إلى ترتيب معين، فيئى ملفات RTF (Rich Text Format)必要 لتطبيق التنسيق والformatting في المستندات.

التحويل من ملفات EMLX إلى formats RTF هو ضروري لتمكين القدرة الكاملة على تنسيق وتطبيق formatings في المستندات. هذا التحويل يتيح لك:

**الاستخدامات:**

*   **ال通信 في الأعمال**: تحويل ملفات EMLX إلى بريد إلكتروني رسمي للعمل، مثل المقترحات و التقارير، مع سيطرة متوسطة على أنواع الخطوط والأنقاض والألوان.
*   **الكتابة الإخبارية**: استخدام RTF لتنسيق المقالات والEDITORIALS و الإعلانات الصحفية، مما يضمن لونًا ونمطًا متشابهين في النشرات.
*   **الكتابة الأكاديمية**: تحويل ملفات EMLX إلى مقالات بحثية وثESIS و博士ية مع تنظيم وformatting دقيق.
*   **المواد التسويقية**: استخدام RTF لتنسيق المواد التسويقية مثل brochures وflyers و catalogs مع تفصيل ودقة في النظر.
*   **ال文档ات الفنية**: تحويل ملفات EMLX إلى دلائل المستخدمين و指南ات الاستخدام و_SPECS技术 مع رؤوس وأعداد متميزة.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}