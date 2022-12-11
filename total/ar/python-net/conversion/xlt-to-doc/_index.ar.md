---
title: تحويل XLT إلى DOC باستخدام Python
description: تحويل XLT إلى DOC في تطبيقات Python الخاصة بك دون استخدام Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: DOC
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل XLT إلى DOC عبر Python" h2="تحويل XLT إلى DOC في تطبيقات Python دون تثبيت Microsoft Excel <sup>&reg;</sup> أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

لمطور Python ، الذي يحاول إضافة ميزة تحويل XLT إلى DOC داخل التطبيق. يمكن أن تساعد [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API في أتمتة عملية التحويل. إنها حزمة كاملة من واجهات برمجة التطبيقات المختلفة التي تتعامل مع تنسيقات مختلفة بما في ذلك ملفات XLT و DOC.

إنها بشكل أساسي في خطوتين. استخدم أولاً [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API لتحويل ملف XLT إلى HTML. بعد ذلك باستخدام Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) ، احفظ HTML الذي تم إنشاؤه في تنسيق Microsoft Word المطلوب. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل XLT إلى DOC في Python" %}}
- **الخطوة 1** افتح ملف XLT المصدر باستخدام فئة Workbook
- احفظ ملف XLT إلى HTML باستخدام طريقة save(file, SaveFormat.HTML) عن طريق توفير اسم الملف ومسار الدليل المطلوب
-  **الخطوة 2** قم بتحميل ملف HTML بنسخة من فئة [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  قم باستدعاء طريقة "الحفظ" أثناء تحديد مسار ملف DOC الناتج. لذلك يتم تحويل ملف XLT الخاص بك إلى DOC في المسار المحدد

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}

- لتحويل XLT إلى DOC ، يلزم Python 3.5 أو أحدث
- واجهات برمجة التطبيقات المرجعية داخل المشروع مباشرة من PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) و [Aspose.Words](https://pypi.org/project/aspose-words/))
-  أو استخدم الأمرين التاليين "pip install aspose-cells-python" "و" pip install aspose.words "
-  علاوة على ذلك ، فإن نظام التشغيل Microsoft Windows أو Linux (انظر المزيد عن [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) و [Words](https://docs.aspose.com/words/python-net/system-requirements/)) ولليوكس تحقق من المتطلبات الإضافية لـ gcc و libpython واتبع [تعليمات خطوه بخطوه](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="حفظ XLT إلى HTML في Python - الخطوة 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="حفظ HTML إلى DOC في Python - الخطوة 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}