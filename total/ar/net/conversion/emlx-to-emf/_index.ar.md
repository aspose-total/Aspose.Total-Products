---
title: C# API لتصدير البريد الإلكتروني إلى EMF
description: قم بتحويل EMLX إلى EMF دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/emlx-to-emf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EMF
otherformats: PS PNG XPS OTT DOC DOCM MD TIFF DOT DOCX TEXT JPEG DOTX PDF RTF GIF FLATOPC EMF WORDML ODT DOTM SVG PCL EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى EMF عبر .NET" h2=".NET API لتقديم EMLX إلى EMF على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل EMF داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى EMF" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق EMF باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Emf كـ SaveFormat
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

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EMLX إلى EMF ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات EMF عبر .NET" %}}
أثناء حفظ المستند من EMLX إلى EMF ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMLX إلى EMF برمجيًا: حالات الاستخدام" %}}
ملفات EMF (Enhanced Metafile) تستخدم لتخزين معلومات الصور الرشسترية، مما يجعلها مثالية لإنشاء الصور الثابتة والillustrations. ومع ذلك، عندما تعمل مع البيانات المتحركة، فالمنصات مثل Excel تصبح أساسية في مجالات مثل تحليل البيانات وترسيخ البيانات.

التحويل من ملفات EMF إلى صيغ Excel يتيح لك استخدامها في العديد من الاستخدامات التالية:

* **تعديل الصور**: تحرير الصور، إضافة النصوص والشكلات، وتحرير قيم البكسلات.
* **تصميم GUI التفاعلي**: استخدام Excel لإنشاء عناصر GUI مثل الأزرار والنوافذ والرسوم البيانية.
* **الرسم الفني والdocumentation الفنية**: تحويل ملفات EMF إلى إنشاء رسمات فنية مفصلة لل مشاريع.
* **الillustrations العلمية**: استخدام Excel لترسيخ الرسوم البيانية من البيانات العلمية.
* **الفن الرقمي**: تحويل ملفات EMF إلى إنشاء أعمال الفن الرقمي باستخدام تقنيات التحرير بالبكسلات.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}