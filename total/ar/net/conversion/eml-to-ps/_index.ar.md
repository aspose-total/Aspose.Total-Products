---
title: C# API لتصدير البريد الإلكتروني إلى PS
description: قم بتحويل EML إلى PS دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/eml-to-ps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PS
otherformats: FLATOPC DOCM DOCX PNG XPS ODT DOC DOT SVG PCL PDF DOTM EPUB RTF GIF EMF WORDML JPEG MD PS DOTX TEXT OTT TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى PS عبر .NET" h2=".NET API لتقديم EML إلى PS على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EML إلى ميزات تحويل PS داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى PS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى PS" %}}
1. افتح ملف EML باستخدام فئة [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. تحويل EML إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق PS باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Ps كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.ps", SaveFormat.Ps); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EML إلى PS ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EML وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات PS عبر .NET" %}}
أثناء حفظ المستند من EML إلى PS ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EML إلى PS برمجيًا: حالات الاستخدام" %}}
الملفات الإلكترونية (EML) هي ملفات تستخدم لstorage من المعلومات النصية plain text عن البريد الإلكتروني، مما يجعلها مثالية للsending والreceiving من الرسائل الإلكترونية بمتطلبات format محدودة. ومع ذلك، عندما تكون قد تحتاج إلى إنشاء و分享 عروض محددة محددة مع محتوى نصي وصور و内容 أ-multimedia، فإن الملفات PS (Presentations) تصبح أساسية لإنشاء وتعديل وتحمل العروض.

التحويل من الملفات الإلكترونية إلى formats PS هو ضروري للاستفادة الكاملة من قدرات إنشاء وتحميل العروض. هذا التحويل يتيح لك:

**الاستخدامات:**

*   **العروض المحترفة**: تحويل الملفات الإلكترونية إلى إنشاء عروض محددة محددة مع النصوص والصور والأ内容 الأ-multimedia.
*   **الاتصال 商业ًا**: استخدام PS لsending العروض والتقارير وال提案ات بالشكلية وال专业ية الكاملة.
*   **المواد التسويقية**: تحويل الملفات الإلكترونية إلى إنشاء مواد تسويقية جذابة، مثل pitches销售、محطات المنتجات، وPRESENTATIONS في المؤتمرات.
*   **التعليم والتدريب**: استخدام PS لإنشاء محتوى تعليمي تفاعلي، مثل slides العروض، وlessons multimedia، وقيد المعلمين.
*   **المواد الداخلية**: تحويل الملفات الإلكترونية إلى sending communications داخلية الشركة، مثل تحديثات السياسات، ملخصات الاجتماعات، والannouncements لل团队.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}