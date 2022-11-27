---
title: قم بتحديث ملفات Excel باستخدام Java 

description: قم بتحرير مستندات Microsoft Excel XLSX و XLS و CSV دون تثبيت Microsoft Office داخل التطبيقات المستندة إلى Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="قم بتحديث مستندات Excel عبر Java" h2="قم بتعديل ملفات Microsoft Excel XLSX و XLS داخل التطبيقات المستندة إلى Java دون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
من الشائع أن تقوم المؤسسة بتحديث بياناتها وتخزينها في ملفات Excel مثل بيانات الطلاب وسجلات المرضى وقائمة عناصر المستودعات وما إلى ذلك عبر برامج الشركة. يوفر [Aspose.Total for Java](https://products.aspose.com/total/java/) API وظيفة تعديل جداول البيانات باستخدام البرامج الخاصة بهم. يمكن للمبرمجين تحسين البرنامج بإمكانيات التعديل بمجرد كتابة بضعة أسطر من كود API. [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API الذي يعد جزءًا من حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/) يجعل عملية التعديل هذه سهلة. فيما يلي عملية تحديث وثيقة Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحديث مستندات Excel باستخدام Java" %}}

يوفر [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) التي تتولى تحميل جداول بيانات Excel. العملية بسيطة. قم بإنشاء كائن فئة المصنف من خلال توفير الملف المصدر كمعلمة. قم بالوصول إلى ورقة العمل ذات الصلة والخلية ذات الصلة باستخدام طريقة [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). استخدم طريقة [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) لتعديل المحتوى في الخلية التي تم الوصول إليها واستدعاء طريقة الحفظ () أخيرًا لحفظ المستند.

{{% blocks/products/pf/feature-page-code h3="كود Java - تحديث مستندات Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="تحديث">}}