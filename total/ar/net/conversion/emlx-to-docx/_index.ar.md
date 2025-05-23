---
title: C# API لتصدير البريد الإلكتروني إلى DOCX
description: قم بتحويل EMLX إلى DOCX دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/emlx-to-docx/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOCX
otherformats: MD PDF SVG EMF WORDML DOT DOCX FLATOPC DOC ODT JPEG GIF PNG OTT RTF TEXT EPUB DOCM PCL PS DOTM TIFF DOTX XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى DOCX عبر .NET" h2=".NET API لتقديم EMLX إلى DOCX على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل DOCX داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى DOCX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى DOCX" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق DOCX باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Docx كـ SaveFormat
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
قبل تحويل EMLX إلى DOCX ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات DOCX عبر .NET" %}}
أثناء حفظ المستند من EMLX إلى DOCX ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMLX إلى DOCX برمجيًا: حالات الاستخدام" %}}
ملفات إMLX (Electronic Mail Message Exchange) تستخدم لتحميل المعلومات النصية، مما يجعلها مثالية لإنشاء رسائل البريد الإلكتروني البسيطة والنشرة الإخبارية. ومع ذلك، عندما نعمل مع البيانات المتحركة، يصبح ملفات DOCX من Microsoft Word أساسيةً ل编辑 وتحديث محتوى النشر.

تحويل ملفات EMLX إلى صيغ DOCX هو ضروري لتمكين القدرات الكاملة على تحرير و出版 المحتوى. هذا التحول يساعد في:

**الاستخدامات:**

*   **模板 رسائل بريد إلكتروني تجارية**: تحويل ملفات EMLX إلى إنشاء نماذج رسائل بريد إلكتروني مخصصة، مما ي节省 الوقت ويعزز الإنتاجية.
*   **النشرة الإخبارية والاعلان الصحفي**: استخدام DOCX لتحرير والنشر النشرة الإخبارية والاعلان الصحفي وكذلك المحتوى المكتوب، مما يساهم في التنسيق الاحترافي والتصميم.
*   **دقائق اجتماع و سير الذات**: تحويل ملفات EMLX إلى إنشاء دقائق اجتماع و سير الذات، مما يظهر مهاراتكم ومجربتم في إضاءة سلب.

*   **المنشورات الاجتماعية و تعليقاتها**: استخدام DOCX للكتابة والتحرير من المنشورات الاجتماعية وتعليقاتها، مما يساعد على التواصل مع الجمهور و分享 الرسالة بشكل فعال.

*   **الكتابة الفنية ودокументات تقنية**: تحويل ملفات EMLX إلى إنشاء الكتابة الفنية ودокументات تقنية، مما يوفر تعليمات و指南 واضح للمستخدمين والعملاء.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}