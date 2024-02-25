---
title: تحويل تنسيق JSON إلى POTM عبر C++
description: تحليل JSON إلى POTM في C++ بدون استخدام Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POTM
otherformats: POTX OTP ODP PPT PPTM PPSM PPSX POWERPOINT POT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل تنسيق JSON إلى POTM عبر C++" h2="C++ API لتحليل JSON إلى POTM بدون استخدام Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل JSON إلى POTM داخل أي تطبيق C++ بخطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحليل JSON إلى PPTX. بعد ذلك ، باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ، يمكنك تحويل PPTX إلى POTM. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى POTM عبر C++" %}}
1. أنشئ كائنًا جديدًا [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) واقرأ بيانات JSON الصالحة من الملف
2. احفظ JSON بتنسيق PPTX باستخدام طريقة [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. احفظ المستند بتنسيق POTM باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت عبر Package Manager Console في Visual Studio باستخدام `` Install-Package Aspose.Total.Cpp '' `.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى POTM عبر C++" %}}
أثناء تحليل JSON إلى POTM ، يمكنك أيضًا تعيين حجم الصفوف والأعمدة عن طريق تحميل JSON مع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). إذا كنت بحاجة إلى تعيين ارتفاع الصف نفسه لجميع الصفوف في ورقة العمل ، فيمكنك القيام بذلك باستخدام [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) طريقة مجموعة [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). وبالمثل ، لتعيين نفس عرض العمود لجميع الأعمدة في ورقة العمل ، استخدم أسلوب مجموعة ICells [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل تنسيق JSON إلى POTM مع العلامة المائية في C++" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى POTM بعلامة مائية. لإضافة علامة مائية إلى مستند POTM الخاص بك ، يمكنك أولاً تحليل JSON إلى PPTX وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PPTX الذي تم إنشاؤه حديثًا باستخدام فئة [العرض التقديمي](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) ، احصل على الشريحة الأولى ، أضف شكل تلقائي لنوع المستطيل ، أضف TextFrame إلى المستطيل ، أنشئ كائن فقرة لإطار نصي ، أنشئ كائن Portion للفقرة ، أضف علامة مائية باستخدام set_Text () ، ويمكن حفظ المستند إلى POTM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}