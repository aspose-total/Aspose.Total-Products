---
title: تحويل CGM إلى XLSB عبر C# API
description: C# API لتحويل ملف CGM إلى XLSB بدون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/net/conversion/cgm-to-xlsb/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XLSB
otherformats: XLSB TSV XLTX ODS XLSM XLT XLTM EXCEL SXC TXT FODS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتقديم CGM إلى XLSB" h2="تصدير ملف CGM إلى XLSB عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Excel أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تحويل ملف CGM إلى XLSB ضمن أي تطبيقات .NET و C# و ASP.NET و VB.NET. أولاً ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى XLSX. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API ، يمكنك تحويل XLSX إلى XLSB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل CGM إلى XLSB" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى XLSX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق XLSB باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `Xlsb` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل المحمية CGM إلى XLSB عبر C#" %}}
إذا كان مستند CGM الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى XLSB بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى XLSB بعلامة مائية عبر C#" %}}
أثناء تحويل ملف CGM إلى XLSB ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف XLSB الناتج. لإضافة علامة مائية ، يمكنك إنشاء كائن مصنف جديد وفتح مستند XLSX المحول ، وتحديد ورقة العمل عبر الفهرس الخاص به ، وإنشاء شكل واستخدام وظيفة AddTextEffect الخاصة به. بعد ذلك يمكنك حفظ مستند XLSX كملف XLSB مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى XLSB برمجيًا: حالات الاستخدام" %}}
الملفات CGM (Computer Graphics Metafile) تستخدم لتحميل معلومات حول الصور النصية، مما يجعلها مثالية لإنشاء الصور الثابتة والillustrations. ومع ذلك، عندما نعمل مع البيانات المتحركة، مثل الملفات excel، يصبحوا أساسًا لجستطيع استخدامهم في تحليل البيانات وترسيخ البيانات.

التحويل من الملفات CGM إلى صيغ Excel ضروريًا للاستفادة الكاملة من قدراتك في ترسيح البيانات وتحليلها. هذا التحويل يتيح لك:

**الاستخدامات:**

*   **التصميم الثابت للgraphics**: تحويل الملفات CGM لإنشاء الصور النصية الم优化، مثل اللوغوهات والايكونز مع سيطرة متكاملة على الألوان، الشكل، وأحجامها.
*   **التحرير والillustrations**: استخدام Excel لتعديل الصور النصية، دمج الصور، واضافة النص أو الإφέكت لتحسين illustrations و内容 الرسومي.
*   **التصميم الدعائي والهيكل**: تحويل الملفات CGM لإنشاء تصميمات الدعاء المتحركة، تنظيم المحتوى، وتعديل الهيكل بسهولة.
*   **إنشاء المعلومات البيانية**: استخدام Excel ل设计信息图表 جذابة، تنظيم البيانات، وترسيح المعلومات المعقدة في شكل واضح وقصير.
*   **إنتاج التقارير الثابتة**: تحويل الملفات CGM لإنتاج التقارير المتحركة، متابعة الأعمدة الرئيسية (KPIs)، وإنتاج visuals عالية الجودة للتفكير العقلاني في الأعمال.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}