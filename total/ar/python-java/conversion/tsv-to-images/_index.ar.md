---
title: تحويل TSV إلى صورة باستخدام Python
description: TSV إلى صورة TIFF BMP PNG JPEG GIF EMF SVG التحويل في تطبيقات Python دون استخدام Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: TSV
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل TSV إلى صورة عبر Python" h2="تحويل صور TSV إلى JPG و TIFF و BMP و PNG و GIF في تطبيقات Python دون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

لمطور Python ، الذي يحاول إضافة TSV إلى PNG و BMP و TIFF و JPEG و GIF Image ضمن التطبيق. كما هو مطلوب في بعض الأحيان لتضمين جداول بيانات Excel في تطبيقات الويب أو سطح المكتب. في مثل هذه الحالات ، يكون تصدير جداول البيانات إلى الصور هو الروح الواحدة. يمكن أن تساعد واجهة برمجة تطبيقات [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) في تصدير ملفات Excel إلى الصور بالإضافة إلى أتمتة عملية التحويل. إنها حزمة كاملة من واجهات برمجة التطبيقات المختلفة التي تتعامل مع تنسيقات مختلفة بما في ذلك تنسيقات Microsoft Excel عبر واجهة برمجة تطبيقات [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) التابعة لها. حاليًا تدعم Python Excel to Image Converter API تحويل ملفات Excel إلى EMF و WMF و JPEG و PNG و BMP و GIF و TIFF و SVG و GLTF و PICT و SVM و Office Compatible EMF أو تحقق من [التنسيقات](https://docs.aspose.com/cells/python-java/supported-file-formats/) المدعوم. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل TSV إلى صور في Python" %}}

- قم بإنشاء كائن فئة [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) لتحميل ملف TSV
- استخدم فئة [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) وحدد الخيارات ذات الصلة لصورة الإخراج
- احصل على الوصول إلى ورقة العمل للتحويل باستخدام طريقة [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- احفظ جميع صفحات ورقة العمل كصورة باستخدام طريقة [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). الآن يتم تحويل ملف TSV إلى صور بالمسار المحدد

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

- لتحويل TSV إلى صور (JPG و PNG و GIF و BMP و TIFF) ، قم بمراجعة واجهات برمجة التطبيقات داخل المشروع مباشرةً من PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- أو استخدم أمر النقطة التالي '' تثبيت نقطة aspose.cells``` 
- علاوة على ذلك ، قم بتنزيل حزمة API من قسم [التحميلات](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="TSV لتحويل الصور عبر Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}