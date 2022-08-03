---
title: تحويل XLTX إلى PPTX باستخدام C++
description: تحويل XLTX إلى PPTX داخل تطبيقات C++
url: /ar/cpp/conversion/xltx-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: POWERPOINT DOC DOCX WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل XLTX إلى PPTX عبر C++" h2="تصدير Excel <sup>&reg;</sup> ؛ XLTX إلى PPTX ضمن تطبيقات C++ كاملة الوظائف" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLTX إلى PPTX التحويل على C++" %}}
1. افتح ملف XLTX باستخدام وظيفة عضو [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) في [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) مرجع الفئة
2. تحويل XLTX إلى PDF وتعيين SaveFormat إلى Pdf
3. قم بتحميل ملف PDF المحول باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) مرجع فئة
4. احفظ المستند بتنسيق PPTX باستخدام وظيفة العضو [حفظ](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) وقم بتعيين Pptx على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltx");
// save XLTX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xltx-to-powerpoint/" name="XLTX إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xltx-to-pptx/" name="XLTX إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xltx-to-pptxx/" name="XLTX إلى PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xltx-to-word/" name="XLTX إلى WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}