---
title: تحويل DOC إلى FODS في C++ أو مع محول مجاني على الإنترنت
description: C++ API لتحويل DOC إلى FODS أو عبر الإنترنت دون استخدام Microsoft Word أو Microsoft Excel أو عبر الإنترنت. اختبر محول POT إلى CSV على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: FODS
otherformats: DIF SXC ODS XLT XLSM XLSB EXCEL XLTX TSV XLAM XLS XLTM CSV XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOC إلى FODS أو عبر الإنترنت" h2="تصدير DOC إلى FODS عبر C++ بدون استخدام Microsoft <sup>&reg;</sup> Word أو Microsoft <sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تضمين ميزة تحويل DOC إلى FODS داخل تطبيقات C++ بسهولة. باستخدام واجهة برمجة تطبيقات معالجة وتحويل غنية بالميزات وقوية وسهلة الاستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير DOC إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحويل HTML إلى FODS. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل DOC إلى FODS أو عبر الإنترنت" %}}
1. افتح ملف DOC باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة
2. تحويل DOC إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. قم بتحميل مستند HTML باستخدام مرجع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. احفظ المستند بتنسيق FODS باستخدام وظيفة العضو [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="الوصول إلى خصائص مستند DOC عبر C++" %}}
يسمح لك [Aspose.Words for C++](https://products.aspose.com/words/cpp/) أيضًا بالوصول إلى خصائص مستند ملف DOC ويتيح لك اتخاذ قرار مستنير قبل عملية التحويل. للوصول إلى خصائص المستند ، يمكنك استخدام [BuiltInDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_document_properties) للحصول على خصائص مضمنة و [CustomDocumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.custom_document_properties) للحصول على خصائص مخصصة. يوضح مثال التعليمات البرمجية التالي كيفية تعداد كل الخصائص المضمنة والمخصصة في مستند.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-document-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="احفظ ملف FODS للتدفق عبر C++" %}}
بعد تحويل DOC إلى FODS ، يمكّنك [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) من حفظ مستندك للدفق. لحفظ الملفات في تدفق ، أنشئ كائن MemoryStream أو FileStream واحفظ الملف في كائن الدفق هذا عن طريق استدعاء [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) أسلوب الكائن [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). حدد تنسيق الملف المطلوب باستخدام تعداد [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) عند استدعاء [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-dif/" name="DOC إلى DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-sxc/" name="DOC إلى SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-ods/" name="DOC إلى ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xlt/" name="DOC إلى XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xlsm/" name="DOC إلى XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xlsb/" name="DOC إلى XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-excel/" name="DOC إلى EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xltx/" name="DOC إلى XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-tsv/" name="DOC إلى TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xlam/" name="DOC إلى XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xls/" name="DOC إلى XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xltm/" name="DOC إلى XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-fods/" name="DOC إلى FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-xlsx/" name="DOC إلى XLSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}