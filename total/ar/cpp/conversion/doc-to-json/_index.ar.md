---
title: تحويل DOC إلى تنسيق JSON في C++
description: قم بتصدير DOC إلى JSON في C++ دون استخدام Microsoft Excel أو Word

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل DOC إلى تنسيق JSON عبر C++" h2="تصدير DOC إلى JSON عبر C++ بدون استخدام Microsoft <sup>&reg;</sup> Word أو Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for C++](https://products.aspose.com/total/cpp/) يمكنك تحويل DOC إلى تنسيق JSON داخل تطبيقات C++. أولاً ، باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير DOC إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) ، يمكنك تحويل HTML إلى تنسيق JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOC إلى تنسيق JSON عبر C++" %}}
1. افتح ملف DOC باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة
2. تحويل DOC إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
3. قم بتحميل مستند HTML باستخدام مرجع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. احفظ المستند بتنسيق JSON باستخدام وظيفة العضو [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت عبر Package Manager Console في Visual Studio باستخدام `` Install-Package Aspose.Total.Cpp '' `.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل DOC المحمي إلى تنسيق JSON عبر C++" %}}
باستخدام API ، يمكنك أيضًا فتح المستند المحمي بكلمة مرور. إذا كان مستند DOC الذي تم إدخاله محميًا بكلمة مرور ، فلا يمكنك تحويله إلى تنسيق JSON دون استخدام كلمة المرور. للقيام بذلك ، استخدم مُنشئ خاص overload ، والذي يقبل كائن LoadOptions. يحتوي هذا الكائن على خاصية كلمة المرور ، والتي تحدد سلسلة كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}