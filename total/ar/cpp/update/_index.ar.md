---
title: قم بتحديث ملفات Excel باستخدام C++ 

description: قم بتحرير مستندات Microsoft Excel XLSX و XLS و CSV دون تثبيت Microsoft Office مع التطبيقات المستندة إلى C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="قم بتحديث مستندات Excel عبر C++" h2="قم بتعديل ملفات Microsoft Excel XLSX و XLS داخل التطبيقات المستندة إلى C++ بدون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
من الشائع أن تقوم المؤسسة بتحديث بياناتها وتخزينها في ملفات Excel مثل بيانات الطلاب وسجلات المرضى وقائمة عناصر المستودعات وما إلى ذلك عبر برامج الشركة. يوفر [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API وظيفة تعديل جداول البيانات باستخدام البرنامج. يمكن للمبرمجين تحسين البرنامج بإمكانيات التعديل بمجرد كتابة بضعة أسطر من كود API. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API الذي يعد جزءًا من حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/) يجعل عملية التعديل هذه سهلة. فيما يلي عملية تحديث وثيقة Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحديث مستندات Excel باستخدام C++" %}}

باستخدام [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API ، قم بتحميل المستند المصدر باستخدام [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). قم بالوصول إلى [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) باستخدام GetIWorksheets()->GetObjectByIndex(0) والخلية المطلوبة باستخدام GetICells()->GetObjectByIndex. باستخدام طريقة PutValue ، قم بتعديل المحتوى في الخلية التي تم الوصول إليها. أخيرًا ، قم باستدعاء طريقة الحفظ () لحفظ المستند.

{{% blocks/products/pf/feature-page-code h3="كود C++ - تحديث مستندات Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="تحديث">}}