---
title: تحويل CGM إلى EXCEL عبر C# API
description: C# API لتحويل ملف CGM إلى EXCEL بدون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/net/conversion/cgm-to-excel/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: EXCEL
otherformats: XLTX XLSB TXT ODS XLTM EXCEL DIF XLAM XLT MD SXC TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتقديم CGM إلى EXCEL" h2="تصدير ملف CGM إلى EXCEL عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Excel أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تحويل ملف CGM إلى EXCEL ضمن أي تطبيقات .NET و C# و ASP.NET و VB.NET. أولاً ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى XLSX. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API ، يمكنك تحويل XLSX إلى EXCEL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل CGM إلى EXCEL" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى XLSX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق EXCEL باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `Excel` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل المحمية CGM إلى EXCEL عبر C#" %}}
إذا كان مستند CGM الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى EXCEL بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى EXCEL بعلامة مائية عبر C#" %}}
أثناء تحويل ملف CGM إلى EXCEL ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف EXCEL الناتج. لإضافة علامة مائية ، يمكنك إنشاء كائن مصنف جديد وفتح مستند XLSX المحول ، وتحديد ورقة العمل عبر الفهرس الخاص به ، وإنشاء شكل واستخدام وظيفة AddTextEffect الخاصة به. بعد ذلك يمكنك حفظ مستند XLSX كملف EXCEL مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى EXCEL برمجيًا: حالات الاستخدام" %}}
**ملفات CGM (Computer Graphics Metafile) لا هي المثالية لvisualizing البيانات动态**

الملفات CGM، التي تستخدم لstorage المعلومات عن الصور الرقمية، تفيد في الغالب استخدامها في الصور static والرسوم البيانية. ومع ذلك، عندما تكون بحاجة إلى visualizing البيانات dynamic، فإن spreadsheets مثل Excel يصبحون غير المiable لتحليل البيانات وتقديم النتائج.

الترجمة من ملفات CGM إلى صيغ Excel هي عملية 必须 for unlocking القدرات الكاملة في visualizing البيانات وتحليلها. هذه الترجمة تتيح لك استخدام:

**用途:**

*   **تحليل البيانات动态**: تحويل ملفات CGM لتحليل البيانات dynamic، وتعرف على النمطيات، وتنفيذ تحسينات الأداء.
*   **visualizing البيانات في الوقت الحقيقي**: استخدام Excel لvisualizing البيانات real-time، مما يتيح اتخاذ قرارات أسرع وفهم أفضل للمعلومات.
*   **tools التعاونية**: تحويل ملفات CGM لإنشاء dashboards تفاعلية وreports وvisualizations للتعاون مع الفريقين وتنفيذ المشاركات.
*   **النموذجинг العلمي المتقدم**: استخدام Excel ل建模 وتحليل الظواهر العلمية المعقدة، وتحسين النماذج وت验证 الاعتقادات.
*   **processing البيانات الكبيرة**: تحويل ملفات CGM لprocessing datasets كبيرة، وتعرف على النمطيات، واستخراج المعلومات المهمة من البيانات.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}