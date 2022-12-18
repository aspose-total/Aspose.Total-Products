---
title: تحويل PPTX إلى XLTM باستخدام Python
description: تحويل PPTX إلى XLTM في تطبيقات Python الخاصة بك دون استخدام Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTX
outformat: XLTM
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل PPTX إلى XLTM عبر Python" h2="تحويل PPTX إلى XLTM في تطبيقات Python دون تثبيت Microsoft PowerPoint <sup>&reg;</sup> أو Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

لمطور Python ، الذي يحاول إضافة ميزة تحويل PPTX إلى XLTM داخل التطبيق. يمكن أن تساعد [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API في أتمتة عملية التحويل. إنها حزمة كاملة من واجهات برمجة التطبيقات المختلفة التي تتعامل مع تنسيقات مختلفة بما في ذلك ملفات PPTX و XLTM.

إنها بشكل أساسي في خطوتين. أولاً ، استخدم [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API لتحويل ملف PPTX إلى HTML. بعد ذلك باستخدام Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) ، احفظ HTML الذي تم إنشاؤه في تنسيق Microsoft Excel المطلوب. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل PPTX إلى XLTM في Python" %}}
- **الخطوة 1** استخدم مثيل فئة [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) لفتح ملف PPTX المصدر 
- احفظ ملف PPTX إلى HTML باستخدام طريقة [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) عن طريق توفير اسم الملف ومسار الدليل المطلوب
-  **الخطوة 2** قم بتحميل ملف HTML بنسخة من فئة Workbook
-  قم باستدعاء طريقة "الحفظ" أثناء تحديد مسار ملف XLTM الناتج. لذلك يتم تحويل ملف PPTX الخاص بك إلى XLTM في المسار المحدد

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

- لتحويل PPTX إلى XLTM ، يلزم Python 3.5 أو أحدث
- واجهات برمجة التطبيقات المرجعية داخل المشروع مباشرة من PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) و [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  أو استخدم أوامر النقطة التالية `` تثبيت pip aspose.slides "" و "تثبيت pip aspose-cell-python" "
-  علاوة على ذلك ، نظام التشغيل Microsoft Windows أو Linux (انظر المزيد عن [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) و [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="حفظ PPTX إلى HTML في Python - الخطوة 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حفظ HTML في XLTM في Python - الخطوة 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}