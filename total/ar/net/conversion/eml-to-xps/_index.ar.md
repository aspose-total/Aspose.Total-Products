---
title: C# API لتصدير البريد الإلكتروني إلى XPS
description: قم بتحويل EML إلى XPS دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/eml-to-xps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: XPS
otherformats: DOC PS WORDML DOCX PNG DOTM SVG EMF ODT MD DOTX OTT XPS EPUB GIF DOT JPEG DOCM RTF PCL TIFF PDF FLATOPC TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى XPS عبر .NET" h2=".NET API لتقديم EML إلى XPS على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EML إلى ميزات تحويل XPS داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى XPS" %}}
1. افتح ملف EML باستخدام فئة [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. تحويل EML إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق XPS باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Xps كـ SaveFormat
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
قبل تحويل EML إلى XPS ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EML وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات XPS عبر .NET" %}}
أثناء حفظ المستند من EML إلى XPS ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EML إلى XPS برمجيًا: حالات الاستخدام" %}}
ملفات البريد الإلكتروني (Electronic Mail) هي ملفات تُستخدم لاستور-age النصوص البريدية، مما يجعلها مثالية لإنشاء الوثائق الثابطة والرسائل. ومع ذلك، عندما نعمل مع البيانات المتحركة المتعددة الوسائعة، فإن الملفات التي تحمل规范 XML Paper Specification (XPS) تكون ضرورية لضمان الحفاظ على التنسيق والنصوص بالضبط.

الترخيص من ملفات البريد الإلكتروني إلى صيغ XPS هي عملية هامة لتحرير القدرة الكاملة في حفظ وتمثيل الوثائق. هذه الترخيص تتيح لك:

** استخدامات:**

* **حفاظ على الوثائق**: تحويل الملفات البريدية إلى صيغة XPS لضمان الحفاظ على البريد التاريخي والوثائق والرسائل في صيغة تحتفظ بتصميمها الأصلي.
* **نشر الكتب الإلكترونية**: استخدام XPS لإنشاء كتب إلكترونية تفاعلية، مما يضمن الحفاظ على التنسيق النصفي للنص لتحسين تجربة القراءة.
* **إصدار الشهادات الرقمية**: تحويل الملفات البريدية إلى صيغة XPS لتحقق الشهادات الرقمية وضمان مصداقيتها.
* **التزام بالاست.accessibility**: استخدام XPS لإنشاء الوثائق التي تفي بمتطلبات WCAG، مما يجعلها متاحة للعاملين على الأجهزة المساعدية.
* **تحليلForensic**: تحويل الملفات البريدية إلى صيغة XPS لتحليل المحتوى البريدي للتحقيقات forensics مثل تعريف مصدر الرسالة أو تحديد病毒.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}