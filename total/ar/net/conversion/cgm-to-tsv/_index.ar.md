---
title: تحويل CGM إلى TSV عبر C# API
description: C# API لتحويل ملف CGM إلى TSV بدون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/net/conversion/cgm-to-tsv/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TSV
otherformats: TSV FODS XLSM EXCEL TXT SXC XLAM ODS DIF XLSB XLT MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتقديم CGM إلى TSV" h2="تصدير ملف CGM إلى TSV عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Excel أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تحويل ملف CGM إلى TSV ضمن أي تطبيقات .NET و C# و ASP.NET و VB.NET. أولاً ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى XLSX. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API ، يمكنك تحويل XLSX إلى TSV.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل CGM إلى TSV" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل CGM إلى XLSX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق TSV باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `Tsv` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل المحمية CGM إلى TSV عبر C#" %}}
إذا كان مستند CGM الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى TSV بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى TSV بعلامة مائية عبر C#" %}}
أثناء تحويل ملف CGM إلى TSV ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف TSV الناتج. لإضافة علامة مائية ، يمكنك إنشاء كائن مصنف جديد وفتح مستند XLSX المحول ، وتحديد ورقة العمل عبر الفهرس الخاص به ، وإنشاء شكل واستخدام وظيفة AddTextEffect الخاصة به. بعد ذلك يمكنك حفظ مستند XLSX كملف TSV مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى TSV برمجيًا: حالات الاستخدام" %}}
تحويل ملفات CGM إلى格式 TSV هو من الضرورة لضمان إطالة قدراتك في تحليل البيانات.

**الاستخدامات:**

*   **التكامل البياني**: تحويل ملفات CGM إلى تSV لضمان التكامل السلس مع مصادر البيانات الأخرى والأدوات.
*   **تدريب الموديلاتmachine learning**: استخدام البيانات بتنسيق TSV لتدريب الموديلات machine learning، مما يؤدي إلى пред测 دقيقة وقدرات استخبارية.
*   **القراءة البيانية للعلامات: تحويل ملفات CGM إلى تSV لإنشاء dashboards وار报表 تفاعلية، مما يساعد على اتخاذ قرارات أفضل.
*   **التحليل البياني والبحث: استخدام البيانات بتنسيق TSV في المهام مثل التعرف على الأنماط وال趋势 والкорالات.
*   **التكامل مع الخزانات السحابية**: تحويل ملفات CGM إلى تSV لتحميل بسهولة إلى خدمات تخزين السحاب مثل AWS S3 أو Google Cloud Storage.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}