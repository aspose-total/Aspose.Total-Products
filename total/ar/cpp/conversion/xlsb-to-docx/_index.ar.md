---
title: تحويل XLSB إلى DOCX باستخدام C++
description: تحويل XLSB إلى DOCX داخل تطبيقات C++
url: /ar/cpp/conversion/xlsb-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLSB
outformat: DOCX
otherformats: POWERPOINT DOC WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل XLSB إلى DOCX عبر C++" h2="تصدير Excel <sup>&reg;</sup> ؛ XLSB إلى DOCX ضمن تطبيقات C++ كاملة الوظائف" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSB إلى DOCX التحويل على C++" %}}
1. افتح ملف XLSB باستخدام وظيفة عضو [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) في [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) مرجع الفئة
2. تحويل XLSB إلى PDF وتعيين SaveFormat إلى Pdf
3. قم بتحميل ملف PDF المحول باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument) مرجع فئة
4. احفظ المستند بتنسيق DOCX باستخدام وظيفة العضو [حفظ](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.docxument#a6383c010776212483f51cc41235924db) وقم بتعيين Docx على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSB file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsb");
// save XLSB as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Docxument class reference
auto docx = MakeObject<Docxument>(u"pdfOutput.pdf");
// save docxument in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xlsb-to-powerpoint/" name="XLSB إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xlsb-to-docx/" name="XLSB إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xlsb-to-word/" name="XLSB إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/xlsb-to-pptx/" name="XLSB إلى PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}