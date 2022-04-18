---
title: C # API لتصدير PDF إلى GIF
description: تحويل PDF إلى GIF دون استخدام Microsoft Word
url: /ar/net/conversion/pdf-to-gif/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: GIF
otherformats: DOTM ODT XAMLFLOW GIF DOT RTF MHTML WORDML PS OTT MARKDOWN PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PDF إلى GIF عبر .NET" h2=".NET API لتصدير PDF إلى GIF على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET] (https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PDF إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET] (https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى GIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C # API لتحويل PDF إلى GIF" %}}
1. افتح ملف PDF باستخدام فئة [Document] (https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PDF إلى Doc باستخدام طريقة [حفظ] (https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document] (https://apireference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق GIF باستخدام طريقة [حفظ] (https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Gif كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pdf");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.gif", SaveFormat.Gif);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف PDF باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل PDF إلى GIF ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [مستند] (https://apireference.aspose.com/pdf/net/aspose.pdf/document) وفتح PDF باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [فك تشفير] (https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.pdf", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly GIF- ملف عبر .NET" %}}
من أجل حماية GIF الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET] (https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType] (https://apireference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-ott/" name="PDF ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-mhtml/" name="PDF ل MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-wordml/" name="PDF ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-dot/" name="PDF ل DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-odt/" name="PDF ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-rtf/" name="PDF ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-ps/" name="PDF ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-flatopc/" name="PDF ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-pcl/" name="PDF ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-markdown/" name="PDF ل MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-xamlflow/" name="PDF ل XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-dotx/" name="PDF ل DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}