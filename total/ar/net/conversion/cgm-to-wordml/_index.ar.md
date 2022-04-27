---
title: C# API لتصدير CGM إلى WORDML
description: تحويل CGM إلى WORDML دون استخدام Microsoft Word
url: /ar/net/conversion/cgm-to-wordml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: WORDML
otherformats: RTF MHTML XAMLFLOW DOTM DOT DOTX FLATOPC PCL PS WORDML OTT MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم CGM إلى WORDML عبر .NET" h2=".NET API لتصدير CGM إلى WORDML على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف CGM إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل CGM إلى WORDML" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى Doc باستخدام طريقة [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document](https://apireference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق WORDML باستخدام طريقة [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Wordml كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.cgm");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");
// call save method while passing SaveFormat.WordML
outputDocument.Save("output.wordml", SaveFormat.WordML);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف CGM باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل CGM إلى WORDML ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) وفتح CGM باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.cgm", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly WORDML- ملف عبر .NET" %}}
من أجل حماية WORDML الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-ott/" name="CGM ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-mhtml/" name="CGM ل MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-wordml/" name="CGM ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-dot/" name="CGM ل DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-odt/" name="CGM ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-rtf/" name="CGM ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-ps/" name="CGM ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-flatopc/" name="CGM ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-pcl/" name="CGM ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-markdown/" name="CGM ل MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-xamlflow/" name="CGM ل XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/cgm-to-dotx/" name="CGM ل DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}