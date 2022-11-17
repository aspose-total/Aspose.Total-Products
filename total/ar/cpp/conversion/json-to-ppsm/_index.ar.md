---
title: تحويل تنسيق JSON إلى PPSM عبر C++
description: تحليل JSON إلى PPSM في C++ بدون استخدام Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POT PPS PPTM OTP POTX PPT PPSX POWERPOINT POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل تنسيق JSON إلى PPSM عبر C++" h2="C++ API لتحليل JSON إلى PPSM بدون استخدام Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل JSON إلى PPSM داخل أي تطبيق C++ بخطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحليل JSON إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ، يمكنك تحويل PPTX إلى PPSM. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى PPSM عبر C++" %}}
1. أنشئ كائنًا جديدًا [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) واقرأ بيانات JSON الصالحة من الملف
2. احفظ JSON بتنسيق PPTX باستخدام طريقة [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. احفظ المستند بتنسيق PPSM باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت عبر Package Manager Console في Visual Studio باستخدام `` Install-Package Aspose.Total.Cpp '' `.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى PPSM عبر C++" %}}
أثناء تحليل JSON إلى PPSM ، يمكنك أيضًا تعيين حجم الصفوف والأعمدة عن طريق تحميل JSON مع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). إذا كنت بحاجة إلى تعيين ارتفاع الصف نفسه لجميع الصفوف في ورقة العمل ، فيمكنك القيام بذلك باستخدام [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) طريقة مجموعة [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). وبالمثل ، لتعيين نفس عرض العمود لجميع الأعمدة في ورقة العمل ، استخدم أسلوب مجموعة ICells [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل تنسيق JSON إلى PPSM مع العلامة المائية في C++" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى PPSM بعلامة مائية. لإضافة علامة مائية إلى مستند PPSM الخاص بك ، يمكنك أولاً تحليل JSON إلى PPTX وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PPTX الذي تم إنشاؤه حديثًا باستخدام فئة [العرض التقديمي](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) ، احصل على الشريحة الأولى ، أضف شكل تلقائي لنوع المستطيل ، أضف TextFrame إلى المستطيل ، أنشئ كائن فقرة لإطار نصي ، أنشئ كائن Portion للفقرة ، أضف علامة مائية باستخدام set_Text () ، ويمكن حفظ المستند إلى PPSM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-pot/" name="JSON إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-pps/" name="JSON إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-pptm/" name="JSON إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-otp/" name="JSON إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-potx/" name="JSON إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-ppt/" name="JSON إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-ppsx/" name="JSON إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-powerpoint/" name="JSON إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-potm/" name="JSON إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/json-to-ppsm/" name="JSON إلى PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}