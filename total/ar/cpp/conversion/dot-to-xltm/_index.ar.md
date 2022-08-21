---
title: تحويل DOT إلى XLTM في C++
description: C++ API لتحويل DOT إلى XLTM دون استخدام Microsoft Word أو Microsoft Excel
url: /ar/cpp/conversion/dot-to-xltm/
family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: XLTM
otherformats: XLAM XLS DIF CSV XLTX ODS TSV FODS XLSB XLT XLSX EXCEL XLSM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOT إلى XLTM" h2="تصدير DOT إلى XLTM عبر C++ بدون استخدام Microsoft <sup>&reg;</sup> Word أو Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تضمين ميزة تحويل DOT إلى XLTM داخل تطبيقات C++ بسهولة. باستخدام واجهة برمجة تطبيقات معالجة وتحويل غنية بالميزات وقوية وسهلة الاستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير DOT إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحويل HTML إلى XLTM. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل DOT إلى XLTM" %}}
1. افتح ملف DOT باستخدام [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument) مرجع فئة
2. تحويل DOT إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string_saveformat)
3. قم بتحميل مستند HTML باستخدام مرجع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. احفظ المستند بتنسيق XLTM باستخدام وظيفة العضو [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="الوصول إلى خصائص مستند DOT عبر C++" %}}
يسمح لك [Aspose.Words for C++](https://products.aspose.com/words/cpp/) أيضًا بالوصول إلى خصائص مستند ملف DOT ويتيح لك اتخاذ قرار مستنير قبل عملية التحويل. للوصول إلى خصائص المستند ، يمكنك استخدام [BuiltInDotumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotument_properties) للحصول على خصائص مضمنة و [CustomDotumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotument_properties) للحصول على خصائص مخصصة. يوضح مثال التعليمات البرمجية التالي كيفية تعداد كل الخصائص المضمنة والمخصصة في مستند.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="احفظ ملف XLTM للتدفق عبر C++" %}}
بعد تحويل DOT إلى XLTM ، يمكّنك [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) من حفظ مستندك للدفق. لحفظ الملفات في تدفق ، أنشئ كائن MemoryStream أو FileStream واحفظ الملف في كائن الدفق هذا عن طريق استدعاء [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) أسلوب الكائن [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). حدد تنسيق الملف المطلوب باستخدام تعداد [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) عند استدعاء [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xlam/" name="DOT إلى XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xls/" name="DOT إلى XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-dif/" name="DOT إلى DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xltm/" name="DOT إلى XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xltx/" name="DOT إلى XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-ods/" name="DOT إلى ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-tsv/" name="DOT إلى TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-fods/" name="DOT إلى FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xlsb/" name="DOT إلى XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xlt/" name="DOT إلى XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xlsx/" name="DOT إلى XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-excel/" name="DOT إلى EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-xlsm/" name="DOT إلى XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dot-to-sxc/" name="DOT إلى SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}