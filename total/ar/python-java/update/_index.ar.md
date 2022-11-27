---
title: قم بتحديث ملفات Excel باستخدام Python 

description: قم بتحرير مستندات Microsoft Excel XLSX و XLS و CSV دون تثبيت Microsoft Office داخل تطبيقات Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="قم بتحديث مستندات Excel عبر Python" h2="قم بتعديل ملفات Microsoft Excel XLSX و XLS داخل تطبيقات Python دون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
من الشائع أن تقوم المؤسسة بتحديث بياناتها وتخزينها في ملفات Excel مثل بيانات الطلاب وسجلات المرضى وقائمة عناصر المستودعات وما إلى ذلك عبر برامج الشركة. يوفر [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API وظيفة تعديل جداول البيانات عبر البرنامج. يمكن للمبرمجين تحسين البرنامج بإمكانيات التعديل من خلال دمج واجهة برمجة التطبيقات وكتابة أسطر قليلة من التعليمات البرمجية. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API الذي يعد جزءًا من حزمة [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) يجعل عملية التعديل هذه سهلة. فيما يلي عملية تحديث وثيقة Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحديث مستندات Excel باستخدام Python" %}}

يوفر [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API فئة المصنف التي تتعامل مع تحميل جداول بيانات Excel. العملية بسيطة. قم بإنشاء كائن فئة [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) عن طريق توفير الملف المصدر كمعلمة. استخدم طريقة [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) للوصول إلى ورقة العمل ذات الصلة من خلال توفير فهرسها. قم باستدعاء طريقة [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) لتعديل المحتوى في الخلية التي تم الوصول إليها واستدعاء طريقة الحفظ () أخيرًا لحفظ المستند.

{{% blocks/products/pf/feature-page-code h3="Python - تحديث مستندات Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="تحديث">}}