---
title: C# API لتصدير CGM إلى PS
description: تحويل CGM إلى PS دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML DOT DOTX MARKDOWN OTT PCL WORDML FLATOPC DOTM XAMLFLOW ODT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم CGM إلى PS عبر .NET" h2=".NET API لتصدير CGM إلى PS على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف CGM إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى PS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل CGM إلى PS" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى Doc باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق PS باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Ps كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف CGM باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل CGM إلى PS ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح CGM باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly PS- ملف عبر .NET" %}}
من أجل حماية PS الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى PS برمجيًا: حالات الاستخدام" %}}
**تحويل ملفات CGM إلى格式 PS لضمان استخدامه الكامل في 设计 النشرات الإ印刷ية**

استخدم الملفات CGM (Computer Graphics Metafile) في العديد من الصناعات، بما في ذلك تصميم graphic وعلانات. ومع ذلك، عندما يتعلق الأمر بالتصميم الإ印刷ي، يمكن أن تكون هذه الملفات معقدة للعمل بسبب طبيعتها矢كية.

为了 تجاوز这一 تحدي، هو 必须 تحويل ملفات CGM إلى格式 PS (PostScript) لضمان استخدامه الكامل في قدرات تصميم النشرات الإ印刷ية. يتم من خلال ذلك:

**الاستخدامات:**

*   **اللогوهات والbranding**: تحويل الملفات CGM إلى إنشاء لوگوها والرموز والعناصر التي يمكن طباعتها بضمان دقة.
*   **المواد الإعلانية**: استخدام formats PS لتصميم المواد العلامية مثل الدعوات والكارتات والكتبlets التي تتميز في النشر.
*   **ال візيت والهانف: تحويل الملفات CGM إلى إنشاء كартات 비زيت و رأسنامه و حاوليات تعكس هوية العلامة التجارية.
*   **العلانات الإ印刷ية**: استخدام formats PS لإنشاء إعلانات ناجحة في الطباعة التي يمكن إنتاجها بضمان دقة عالية.
*   **تصميم الحقائب: تحويل الملفات CGM إلى تصميم حلول مبتكرة للحقائب التي تعكس风格 العلامة التجارية والشخصية.

بتحويل ملفات CGM إلى formats PS، يمكنك التأكد من أن تصميماتك تتم طباعة بثبات ودقة، دون فقدان جودة أو تفصيل.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}