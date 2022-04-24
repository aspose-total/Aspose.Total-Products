---
title: C# API لتصدير البريد الإلكتروني إلى EMF
description: قم بتحويل EMLX إلى EMF دون استخدام Microsoft Word أو Outlook على .NET
url: /ar/net/conversion/emlx-to-emf/
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
إذا كنت مطور .NET تتطلع إلى إضافة EMLX إلى ميزات تحويل EMF داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/emlx/net/) ، يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى EMF" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://apireference.aspose.com/emlx/net/aspose.emlx/mailmessage)
2. تحويل EMLX إلى HTML باستخدام طريقة [Save](https://apireference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق EMF باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Emf كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
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
قبل تحويل EMLX إلى EMF ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMLX وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://apireference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/emlx / net /) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://apireference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername).  
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
أثناء حفظ المستند من EMLX إلى EMF ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https: //apireference.aspose. com / Words / net / aspose.words / protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-pcl/" name="MSG TO PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-pdf/" name="MSG إلى PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dot/" name="MSG إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-flatopc/" name="MSG إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-jpeg/" name="MSG إلى JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-png/" name="MSG إلى PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-rtf/" name="MSG إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-tiff/" name="MSG إلى TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-docm/" name="MSG إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-ps/" name="MSG إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-gif/" name="MSG إلى GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-xps/" name="MSG إلى XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-odt/" name="MSG إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-docx/" name="MSG إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-doc/" name="MSG إلى DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-wordml/" name="MSG إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-svg/" name="MSG إلى SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-epub/" name="MSG إلى EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-md/" name="MSG TO MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-emf/" name="MSG إلى EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dotm/" name="MSG إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-ott/" name="MSG إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dotx/" name="MSG إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-text/" name="MSG إلى النص" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}