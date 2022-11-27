---
title: قم بتحديث ملفات Excel باستخدام .NET 

description: قم بتحرير مستندات Microsoft Excel XLSX و XLS و CSV دون تثبيت Microsoft Office مع التطبيقات المستندة إلى C # .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="قم بتحديث مستندات Excel عبر .NET" h2="عدّل ملفات Microsoft Excel XLSX و XLS ضمن التطبيقات المستندة إلى .NET بدون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
من الشائع أن تقوم المؤسسة بتحديث بياناتها وتخزينها في ملفات Excel مثل بيانات الطلاب وسجلات المرضى وقائمة عناصر المستودعات وما إلى ذلك عبر برامج الشركة. يوفر [Aspose.Total for .NET](https://products.aspose.com/total/net/) API وظيفة تعديل جداول البيانات باستخدام البرنامج. يمكن للمبرمجين تحسين البرنامج بإمكانيات التعديل بمجرد كتابة بضعة أسطر من كود API. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API الذي يعد جزءًا من حزمة [Aspose.Total for .NET](https://products.aspose.com/total/net/) يجعل عملية التعديل هذه سهلة. فيما يلي عملية تحديث وثيقة Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحديث مستندات Excel باستخدام .NET" %}}

يوفر [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API فئة المصنف التي تتعامل مع تحميل جداول بيانات Excel. العملية بسيطة. قم بإنشاء كائن [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) عن طريق توفير الملف المصدر كمعامل. قم بالوصول إلى ورقة العمل ذات الصلة من خلال توفير فهرسها باستخدام طريقة [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). استخدم طريقة [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) لتعديل المحتوى في الخلية التي تم الوصول إليها واستدعاء طريقة الحفظ () أخيرًا لحفظ المستند.

{{% blocks/products/pf/feature-page-code h3="NET Code - تحديث مستندات Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="تحديث">}}