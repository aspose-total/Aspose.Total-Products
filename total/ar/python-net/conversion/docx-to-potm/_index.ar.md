---
title: تحويل DOCX إلى POTM في Python
description: تحويل DOCX إلى POTM في تطبيقات Python الخاصة بك دون استخدام Microsoft Word أو PowerPoint 
url: /ar/python-net/conversion/docx-to-potm/
family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: POTM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل DOCX إلى POTM باستخدام Python" h2="تحويل DOCX إلى POTM في تطبيقات Python دون تثبيت Microsoft Word <sup>&reg;</sup> أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

بالنسبة لمطور Python ، من يحاول إضافة ميزة تحويل DOCX إلى POTM داخل التطبيق؟ يمكن أن تساعد [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API في أتمتة عملية التحويل. إنها حزمة كاملة من واجهات برمجة التطبيقات المختلفة التي تتعامل مع تنسيقات مختلفة. لذا **كيفية تحويل DOCX إلى POTM في بايثون؟**

إنها بشكل أساسي في خطوتين. استخدم أولاً [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API لتحويل ملف DOCX إلى PDF. بعد ذلك باستخدام PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) ، احفظ ملف PDF الذي تم إنشاؤه في العرض التقديمي بتنسيق POTM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOCX إلى POTM في Python" %}}
- **الخطوة 1** افتح ملف DOCX المصدر باستخدام فئة [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- احفظ ملف DOCX في PDF باستخدام طريقة [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) من خلال توفير اسم الملف ومسار الدليل المطلوب.
-  **الخطوة 2** تحميل ملف PDF بمثيل من فئة [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  قم باستدعاء طريقة "save" أثناء تحديد مسار ملف الإخراج & SaveFormat.POTM كمعلمات. لذلك يتم تحويل ملف DOCX الخاص بك إلى POTM في المسار المحدد.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

- لتحويل DOCX إلى POTM ، يلزم Python 3.5 أو أحدث
- واجهات برمجة التطبيقات المرجعية داخل المشروع مباشرة من PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) و [Aspose.Words](https://pypi.org/project/aspose-words/)) أو
- استخدم أوامر النقطة التالية `` تثبيت pip aspose.slides "" و "تثبيت النقطة aspose.words". علاوة على ذلك،
- نظام التشغيل Microsoft Windows أو Linux (انظر المزيد عن [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) و [Words](https://docs.aspose.com/words/python-net/system-requirements/)) ولليوكس تحقق من المتطلبات الإضافية لـ gcc و libpython واتبع التعليمات خطوة بخطوة [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="حفظ DOCX في PDF في Python - الخطوة 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حفظ PDF في POTM في Python - الخطوة 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}