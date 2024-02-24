---
title: تحويل PCL إلى TXT عبر C# API
description: C# API لتحويل ملف PCL إلى TXT بدون استخدام Microsoft Excel أو Adobe Reader
url_ignore: /ar/net/conversion/pcl-to-txt/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: TXT
otherformats: XLTM SXC DIF XLAM FODS MD XLT TSV ODS TXT XLTX XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API لتقديم PCL إلى TXT" h2="تصدير ملف PCL إلى TXT عبر C# بدون استخدام Microsoft<sup>&reg;</sup> Excel أو Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تحويل ملف PCL إلى TXT ضمن أي تطبيقات .NET و C# و ASP.NET و VB.NET. أولاً ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير PCL إلى XLSX. بعد ذلك ، باستخدام [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API ، يمكنك تحويل XLSX إلى TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="NET API لتحويل PCL إلى TXT" %}}
1. افتح ملف PCL باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تحويل PCL إلى XLSX باستخدام طريقة [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. قم بتحميل مستند XLSX باستخدام فئة [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. احفظ المستند بتنسيق TXT باستخدام طريقة [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) وعيّن `Txt` كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل المحمية PCL إلى TXT عبر C#" %}}
إذا كان مستند PCL الخاص بك محميًا بكلمة مرور ، فلا يمكنك تحويله إلى TXT بدون كلمة المرور. باستخدام واجهة برمجة التطبيقات ، يمكنك أولاً فتح المستند المحمي باستخدام كلمة مرور صالحة وتحويلها بعد ذلك. لفتح الملف المشفر ، يمكنك تهيئة مثيل جديد من فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وتمرير اسم الملف وكلمة المرور كوسائط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PCL إلى TXT بعلامة مائية عبر C#" %}}
أثناء تحويل ملف PCL إلى TXT ، يمكنك أيضًا إضافة علامة مائية إلى تنسيق ملف TXT الناتج. لإضافة علامة مائية ، يمكنك إنشاء كائن مصنف جديد وفتح مستند XLSX المحول ، وتحديد ورقة العمل عبر الفهرس الخاص به ، وإنشاء شكل واستخدام وظيفة AddTextEffect الخاصة به. بعد ذلك يمكنك حفظ مستند XLSX كملف TXT مع علامة مائية. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}