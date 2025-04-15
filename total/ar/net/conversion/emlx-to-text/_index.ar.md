---
title: C# API لتصدير البريد الإلكتروني إلى TEXT
description: قم بتحويل EMLX إلى TEXT دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/emlx-to-text/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: TEXT
otherformats: DOCX DOC DOTM SVG PDF DOTX PNG RTF ODT FLATOPC DOT XPS GIF EPUB TIFF DOCM JPEG TEXT OTT EMF MD WORDML PCL PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى TEXT عبر .NET" h2=".NET API لتقديم EMLX إلى TEXT على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل TEXT داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى TEXT" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق TEXT باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Text كـ SaveFormat
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
قبل تحويل EMLX إلى TEXT ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات TEXT عبر .NET" %}}
أثناء حفظ المستند من EMLX إلى TEXT ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMLX إلى TEXT برمجيًا: حالات الاستخدام" %}}
ملفات إملكس (Electronic Messaging for Learning) هي ملفات تُستخدم لتخزين المحتوى التعليمي، مما يجعلها مثالية لإنشاء محطات التعلم عبر الإنترنت ومرئيات MULTIMEDIA. ومع ذلك، عندما نعمل مع البيانات النصية البسيطة، فملفات النصوص مثل ملفات النصوص تصبح أساسية للبسوопية والسهولة في الاستخدام.

تحويل ملفات إملكس إلى صيغات النصوص هو شيء 必须 لتمكين من القدرات الكاملة في محتوى التعلم و能力 الإرسال. هذا التحول يتيح لك:

**استخدامات:**

*   **تعديل المحتوى**: تحويل ملفات إملكس إلى نص لتعديله وتعديله، مما يجعل ذلك أسهلًا لتقييمه وتحديثه.
*   **tools للتعاون**: استخدام ملفات النصوص للتعاون مع الآخرين في مشاريع التعديل البسيطة للنصوص.
*   **تطوير قاعدة المعرفة**: تحويل ملفات إملكس إلى بناء قاعدة المعرفة التفاعلية وdocumentation للتعليم، مثل محطات تعلم.
*   **集成 في منصات التعليم الإلكترونية**: استخدام صيغ النصوص لدمج المحتوى التعليمي بسهولة في منصات التعليم الإلكترونية، مما يسهم في تجربة المستخدمين بشكل أفضل.
*   **نشر وانتشار المحتوى**: تحويل ملفات إملكس إلى نص لpublishing وانتشار المحتوى عبر عدة قنوات.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}