---
title: C# API لتصدير البريد الإلكتروني إلى EPUB
description: قم بتحويل EMLX إلى EPUB دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى EPUB عبر .NET" h2=".NET API لتقديم EMLX إلى EPUB على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل EPUB داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى EPUB" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق EPUB باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Epub كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EMLX إلى EPUB ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات EPUB عبر .NET" %}}
أثناء حفظ المستند من EMLX إلى EPUB ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMLX إلى EPUB برمجيًا: حالات الاستخدام" %}}
ملفات EMLX (Electronic Mail with X-Based Headers) تستخدم لstorage من المعلومات الإلكترونية، مما يجعلها مثالية لإنشاء 邮件ات ساكنة و архивات الرسائل. ومع ذلك، عندما نعمل مع محتوى تفاعلي، formats ePUB يصبحون أساسيين لل出版 الإلكتروني والتوزيع عبر الإنترنت.

تحويل ملفات EMLX إلى formats ePUB هو من الضرورة للاستخدام الكامل ل潜力ك في出版 الإلكتروني وتوزيع المحتوى عبر الإنترنت. هذا التحول ي允许 لك:

** استخدامات:**

*   **ال出版 الإلكتروني**: تحويل ملفات EMLX إلى كتب رقمية تفاعلية مثل المجلات والجazias والكتب، مما يجعلها متاحة على أجهزة مختلفة.
*   **توزيع المحتوى التعليمي عبر الإنترنت**: استخدام formats ePUB ل出版 المقررات التعليمية والتutorials والمواد التعليمية، مما يسهم في تحسين تجربة التعلم للمعلمين والمحصلين.
*   **نشر المقالات الإخبارية عبر الإنترنت**: تحويل ملفات EMLX إلى مقالات رائعة المرئية، مما يزيد من تفاعل الجمهور ورضف القراء.
*   **ال漫画 الرقمية والروايات**: استخدام formats ePUB لضمان الحفاظ على الروايات والكتب الرائعة وتوزيعها رقميًا، مما يوفر تجربة قراءة فريدة للمقرأين.
*   **توزيع المحتوى على المواقع الإخبارية**: تحويل ملفات EMLX إلى محتوى إلكتروني تفاعلي مثل المقالات والوصفيات والتعليقات من الجمهور، مما يسهم في زيادة تفاعل الموقع ومعدل التحويل.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}