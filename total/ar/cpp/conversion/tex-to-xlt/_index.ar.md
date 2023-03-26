---
title: C++ API لتحويل TEX إلى XLT
description: قم بتحويل TEX إلى XLT عبر C++ API دون استخدام Microsoft Excel أو Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: XLT
otherformats: CSV ODS EXCEL SXC XLSB DIF FODS XLTM XLTX TSV XLSM MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم TEX إلى XLT في تطبيقات C++" h2="تحويل TEX إلى XLT في تطبيقات C++ الأصلية دون الحاجة إلى Microsoft <sup>&reg;</sup> Excel أو Adobe <sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
تحويل TEX إلى XLT في C++ عبر [Aspose.Total for C++](https://products.aspose.com/total/cpp/) مكتبات أتمتة تنسيق الملفات هي عملية بسيطة من خطوتين. في الخطوة الأولى ، يمكنك تصدير TEX إلى XLSX باستخدام [Aspose.PDF لـ C++](https://products.aspose.com/pdf/cpp/) ، بعد ذلك ، باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) واجهة برمجة تطبيقات برمجة جداول البيانات ، يمكنك تحويل XLSX إلى XLT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل TEX إلى XLT" %}}
1. افتح ملف TEX باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) مرجع فئة
2. تحويل TEX إلى XLSX باستخدام وظيفة العضو [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. قم بتحميل مستند XLSX باستخدام مرجع فئة [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. احفظ المستند بتنسيق XLT باستخدام وظيفة العضو [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="الحصول على معلومات ملف TEX أو تعيينها عبر C++" %}}
يسمح لك [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) أيضًا بالحصول على معلومات حول مستند TEX الخاص بك ويتيح لك اتخاذ قرارات مستنيرة قبل عملية التحويل. للحصول على معلومات خاصة بالملف لملف TEX ، تحتاج أولاً إلى استدعاء [get_Info ()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) طريقة [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) فئة. بمجرد استرداد كائن DocumentInfo ، يمكنك الحصول على قيم الخصائص الفردية. علاوة على ذلك ، يمكنك أيضًا تعيين الخصائص باستخدام الطرق الخاصة بفئة DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="احفظ تنسيق ملف XLT للدفق عبر C++" %}}
يسمح [Aspose.Cells for C++](https://products.aspose.com/cells/net/) بحفظ تنسيق ملف XLT للتدفق. لحفظ الملفات في تدفق ، أنشئ كائن MemoryStream أو FileStream واحفظ الملف في كائن الدفق هذا عن طريق استدعاء [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) أسلوب الكائن [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). حدد تنسيق الملف المطلوب باستخدام تعداد [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) عند استدعاء طريقة Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlt-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}