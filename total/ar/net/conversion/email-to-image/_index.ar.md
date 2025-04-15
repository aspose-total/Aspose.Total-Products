---
title: C# API لتصدير البريد الإلكتروني إلى IMAGE
description: قم بتحويل EMAIL إلى IMAGE دون استخدام Microsoft Word أو Outlook على .NET
url_ignore: /ar/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تصدير البريد الإلكتروني إلى IMAGE عبر .NET" h2=".NET API لتقديم EMAIL إلى IMAGE على أنظمة التشغيل Windows و macOS و Linux دون استخدام Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
إذا كنت مطور .NET تتطلع إلى إضافة EMAIL إلى ميزات تحويل IMAGE داخل تطبيقاتك ، فإن [Aspose.Total for .NET](https://products.aspose.com/total/net/) واجهات برمجة تطبيقات معالجة تنسيق الملف هي الطريقة إلى الأمام. باستخدام [Aspose.Email for .NET](https://products.aspose.com/email/net/) ، يمكنك تحويل تنسيق ملف EMAIL إلى HTML. بعد ذلك ، باستخدام [Aspose.Words for .NET](https://products.aspose.com/words/net/) ، يمكنك تحويل HTML إلى IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API لتحويل البريد الإلكتروني إلى IMAGE" %}}
1. افتح ملف EMAIL باستخدام فئة [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. تحويل EMAIL إلى HTML باستخدام طريقة [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. احفظ المستند بتنسيق IMAGE باستخدام طريقة [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) وقم بتعيين Image كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر .NET" %}}
قبل تحويل EMAIL إلى IMAGE ، إذا كنت تريد التأكد من أنك تقوم بتحويل البريد الإلكتروني الصحيح ، فيمكنك تحميل مستند EMAIL وتحليله وإلقاء نظرة على الممتلكات التي تريدها. باستخدام [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) فئة [Aspose.Email for .NET](https://products.aspose.com/email/net/) API ، يمكنك الحصول على معلومات المرسل والمستلمين. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير مستندات IMAGE عبر .NET" %}}
أثناء حفظ المستند من EMAIL إلى IMAGE ، قد تحتاج إلى حماية مستند الإخراج الخاص بك. قد تحتاج أحيانًا إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. يمكن أن يكون هذا مفيدًا لمنع الأشخاص الآخرين من تحرير المعلومات الحساسة والسرية في المستند الخاص بك. تمكّنك واجهة برمجة تطبيقات [Aspose.Words for .NET](https://products.aspose.com/words/net/) من التحكم في طريقة تقييد المحتوى باستخدام [ProtectionType](https://reference.aspose.com/Words/net/aspose.words/protectiontype) معلمة التعداد. يمكنك ضبط المستند للقراءة فقط باستخدام سطور التعليمات البرمجية التالية. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EMAIL إلى IMAGE برمجيًا: حالات الاستخدام" %}}
**تحويل البريد الإلكتروني إلى الصور: إطلاق القصة البصرية**

البريد الإلكتروني هو أداة قوية لتنقل المعلومات، لكنه يفتقر إلى جاذبية الرسوم المتحركة مقارنة بالformats مثل الصور. تحويل البريد الإلكتروني إلى صور من الضرورة للاطلاق القصة البصرية الكاملة وحفظ المحتوى للاستشارة في المستقبل.

التحويل إلى formats الصور للملفات البريدية هو من الضرورة ل:

** الاستخدامات:**

*   **حفظ المحتوى**: تحويل البريد الإلكتروني إلى صور ل捕捉 محتوى مثل ملاحظات اجتماعية، عقود بيع، أو خطط مشاريع، و جعلها متاحة للاستشارة في المستقبل.
*   **حماية العلامة التجارية**: استخدام تحويل الصور لاحترام العلامات التجارية والlogos الشركة، مما يضمن توافق بين جميع قنوات التواصل.
*   **الارشيف الرقمي**: تحويل البريد الإلكتروني إلى صور لإنشاء أرشيف رقمي للشركة، بما في ذلك الأحداث المهمة والمilestones وأساليب اتخاذ القرار.
*   **الموصولية والشمولية**: تحويل البريد الإلكتروني إلى صور لجعل المحتوى أكثر易قابلة للمستخدمين الذين يعانون من إعاقة بصرية أو تعطيلات، باستخدام نصوص وصفية替代ية لتوفير السياق.
*   **الأمان والتشريعات**: استخدام تحويل الصور لحماية المعلومات الحساسة من الوصول غير المترخيص، مما يفيض بالشروط التشريعية ل保护 البيانات وحفظ السرية.

بتحويل ملفات البريد الإلكتروني إلى formats الصور، يمكن للمنظمات إطلاق القصة البصرية الكاملة وحفظ المحتوى وحماية العلامات التجارية.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}