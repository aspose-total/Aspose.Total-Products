---
title: تحويل تنسيق JSON إلى DOCM عبر C++
description: C++ API t0 تحليل JSON إلى DOCM دون استخدام Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOCM
otherformats: OTT CHM PCL DOT PS DOTX ODT FLATOPC WORDML EPUB DOC WORD RTF MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل تنسيق JSON إلى DOCM عبر C++" h2="تحليل JSON إلى DOCM داخل تطبيقات C++ بدون استخدام Microsoft <sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for C++](https://products.aspose.com/total/cpp/) ، يمكنك تحليل JSON إلى DOCM داخل تطبيقات C++ في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تصدير JSON إلى PDF. بعد ذلك ، باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cppp/) ، يمكنك تحويل PDF إلى DOCM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى DOCM في C++" %}}
1. أنشئ كائنًا جديدًا [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) واقرأ بيانات JSON الصالحة من الملف
2. احفظ JSON كملف PDF باستخدام طريقة [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. قم بتحميل مستند PDF باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. احفظ المستند بتنسيق DOCM باستخدام طريقة [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت عبر Package Manager Console في Visual Studio باستخدام `` Install-Package Aspose.Total.Cpp '' `.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى DOCM في C++" %}}
أثناء تحليل JSON إلى DOCM ، يمكنك أيضًا تعيين حجم الصفوف والأعمدة عن طريق تحميل JSON مع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). إذا كنت بحاجة إلى تعيين ارتفاع الصف نفسه لجميع الصفوف في ورقة العمل ، فيمكنك القيام بذلك باستخدام [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) طريقة مجموعة [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). وبالمثل ، لتعيين نفس عرض العمود لجميع الأعمدة في ورقة العمل ، استخدم أسلوب مجموعة ICells [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحويل تنسيق JSON إلى DOCM باستخدام علامة مائية في C++" %}}
باستخدام API ، يمكنك أيضًا تحليل JSON إلى DOCM باستخدام العلامة المائية. لإضافة علامة مائية إلى مستند DOCM ، يمكنك أولاً تحويل JSON إلى PDF وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PDF الذي تم إنشاؤه حديثًا باستخدام فئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.document) ، قم بتعيين خصائص مختلفة للعلامة المائية النصية ،
استدعاء طريقة SetText وتمرير نص العلامة المائية وكائن TextWatermarkOptions. بعد إضافة العلامة المائية ، يمكنك حفظ المستند في غرفة تبادل المعلومات.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}