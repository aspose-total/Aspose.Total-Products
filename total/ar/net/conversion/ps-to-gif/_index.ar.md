---
title: C# API لتصدير PS إلى GIF
description: تحويل PS إلى GIF دون استخدام Microsoft Word
url_ignore: /ar/net/conversion/ps-to-gif/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: GIF
otherformats: RTF MHTML XAMLFLOW GIF DOT MARKDOWN OTT ODT FLATOPC DOTX PCL WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تقديم PS إلى GIF عبر .NET" h2=".NET API لتصدير PS إلى GIF على أنظمة التشغيل Windows و macOS و Linux دون استخدام Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهة برمجة تطبيقات قوية لإضافة ميزات معالجة المستندات وتحويلها داخل تطبيق .NET الخاص بك. باستخدام واجهة برمجة تطبيقات معالجة PDF المتقدمة [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تحويل تنسيق ملف PS إلى DOC. بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تقديم DOC إلى GIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل PS إلى GIF" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PS إلى Doc باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل ملف Doc باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document) من Aspose.Words
4. احفظ المستند بتنسيق GIF باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Gif كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="فك تشفير ملف PS باستخدام كلمة مرور المالك عبر .NET" %}}
قبل تحويل PS إلى GIF ، إذا كنت تريد فك تشفير وثيقتك ، يمكنك القيام بذلك باستخدام API. لفك تشفير ملف PDF ، تحتاج أولاً إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وفتح PS باستخدام كلمة مرور المالك. بعد ذلك ، تحتاج إلى استدعاء طريقة [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) لكائن المستند. أخيرًا ، احفظ الملف المحدّث باستخدام طريقة Save في كائن المستند.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="إنشاء ReadOnly GIF- ملف عبر .NET" %}}
من أجل حماية GIF الخاص بك من التحرير ولمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك ، يمكنك أيضًا تعيين حماية المستند باستخدام API. يمكنك تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/). يمكّنك من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى GIF برمجيًا: حالات الاستخدام" %}}
**ملفات Portable Document Format (PS)** تستخدم لتحميل معلومات الصور الرسومية، مما يجعلها مثالية لإنشاء صور ثابتة ودокументات. ومع ذلك، عندما نعمل مع محتوى وثيقة، يصبح GIF (Graphics Interchange Format) ضروريًا للаниنيم이션 وال内容 المتحرك.

الترخيص من ملفات PS إلى صيغ GIF هي必要ية لتمكين القدرة الكاملة على محتويات الصور والأنيميشن. هذه الترخيص تتيح لك استخدامها في:

**الاستخدامات:**

*   **الаниنيمات في وسائل التواصل الاجتماعي**: تحويل ملفات PS إلى أنيميشنات جذابة للشaring على وسائل التواصل الاجتماعي، وإنشاء صور ناشرة ومعلانات إلكترونية.

*   **المحتوى المتحرك في العروض التمثيلية**: استخدام GIF لضف عناصر تفاعلية مثل النصوص المتحركة، والأنيميشنات، والأعمدة المتحركة في العروض التمثيلية.

*   **الграфикات والаниنيمات على المواقع الإلكترونية**: تحويل ملفات PS إلى گرافيكs 动态 للويب، والаниنيمات، والتفاعلات التي تزيد من تجربة المستخدم.

*   **العلانات الرقمية والدعايات التسويقية**: استخدام GIF لإنشاء إعلانات جذابة، ومحطات المنتجات، وفيديوهات توضيح في حملات العلامات التجارية عبر الإنترنت.

*   **المصادر التعليمية والمعرفة التفاعلية**: تحويل ملفات PS إلى مصادر تعليمية تفاعلية مثل التطبيقات التعليمية، والدروس animated، والتحديات، والعروض.

**ملفات Portable Document Format (PS)** تستخدم لتحميل معلومات الصور الرسومية، مما يجعلها مثالية لإنشاء صور ثابتة ودокументات. ومع ذلك، عندما نعمل مع محتوى وثيقة، يصبح GIF (Graphics Interchange Format) ضروريًا للانيينمATION وال内容 المتحرك.

الترخيص من ملفات PS إلى صيغ GIF هي必要ية لتمكين القدرة الكاملة على محتويات الصور والأنيميشن. هذه الترخيص تتيح لك استخدامها في:

**الاستخدامات:**

*   **الаниنيمات في وسائل التواصل الاجتماعي**: تحويل ملفات PS إلى أنيميشنات جذابة للشaring على وسائل التواصل الاجتماعي، وإنشاء صور ناشرة ومعلانات إلكترونية.

*   **المحتوى المتحرك في العروض التمثيلية**: استخدام GIF لضف عناصر تفاعلية مثل النصوص المتحركة، والأنيميشنات، والأعمدة المتحركة في العروض التمثيلية.

*   **الграфикات والانيمنات على المواقع الإلكترونية**: تحويل ملفات PS إلى گرافيكs 动态 للويب، والانيمنات، والتفاعلات التي تزيد من تجربة المستخدم.

*   **العلانات الرقمية والدعايات التسويقية**: استخدام GIF لإنشاء إعلانات جذابة، ومحطات المنتجات، وفيديوهات توضيح في حملات العلامات التجارية عبر الإنترنت.

*   **المصادر التعليمية والمعرفة التفاعلية**: تحويل ملفات PS إلى مصادر تعليمية تفاعلية مثل التطبيقات التعليمية، والدروس animated، والتحديات، والعروض.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}