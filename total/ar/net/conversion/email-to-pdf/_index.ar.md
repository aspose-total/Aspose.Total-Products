---
title: C# API لتصدير البريد الإلكتروني إلى PDF
description: قم بتحويل EMAIL إلى PDF دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML PDF EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى PDF عبر .NET" h2=".NET API لتقديم EMAIL إلى PDF على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMAIL إلى ميزات تحويل PDF داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMAIL إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى PDF" %}}
1. افتح ملف EMAIL باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMAIL إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق PDF باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Pdf كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EMAIL إلى PDF ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMAIL وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات PDF عبر .NET" %}}
أثناء حفظ المستند من EMAIL إلى PDF ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMAIL إلى PDF برمجيًا: حالات الاستخدام" %}}
التحويل من ملفات البريد الإلكتروني إلى نُسخات PDF هو 必要 evil لتمكين من إمكانيات إدارة الملفات بالكامل. هذا التحويل يتيح لك:

**الاستخدامات:**

*   **السجلات الرسمية والأداء:** تحويل ملفات البريد الإلكتروني إلى نُسخات PDF لتثبيت السجلات الرسمية، وتأكيد الالتزامات الحكومية، وتنفيذ المطابرات.
*   **المواد التسويقية والแคmpaigns العلامية:** استخدام التحويل إلى PDF لإنشاء مادة印刷ية تسويقية، مثل الكاتالوغات والكامبании التسويقية التي تظهر صورة العلامة التجارية بشكل فعال.
*   **المواد التدريبية والمعلمية:** تحويل ملفات البريد الإلكتروني إلى نُسخات PDF لإنشاء دلائل تدريبية تفاعلية، مواد دراسية، وguias للدراسة للم студенты أو الموظفين.
*   **ال提案ات الأعمال وال عقود:** استخدام التحويل إلى PDF لإنشاء عرضات أعمال محترمة، عقود، وأحكام تجارية ت传达 الرسالة بوضوح وحمايةها بشكل آمن.
*   **المشاريع الفنية وال创意:** تحويل ملفات البريد الإلكتروني إلى نُسخات PDF لضمان الحفاظ على الأعمال الفنية الرقمية، مثل الصور والتصميمات، مما يجعلها متاحة للطباعة أو مشاركتها مع العملاء.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}