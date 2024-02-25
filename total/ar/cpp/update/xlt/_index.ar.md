---
title: تحديث ملف XLT باستخدام C++
description: تعديل مستند XLT في تطبيقات C++ بدون استخدام Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحديث ملف XLT عبر C++" h2="قم بتعديل جداول بيانات XLT عبر التطبيقات المستندة إلى C++ بدون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

للمبرمج الذي يحاول تحديث ملفات XLT داخل تطبيق C++, يمكن أن تساعد [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API في أتمتة عملية التحديث. إنها حزمة كاملة من مكتبات C++ مختلفة تتعامل مع تنسيقات متعددة بما في ذلك مستندات Microsoft Excel. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API الذي يعد جزءًا من حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/) يجعل عملية التعديل هذه سهلة. عملية تحديث مستند XLT بسيطة عن طريق الوصول أولاً إلى الورقة ثم تحديث قيمة الخلية في Excel باستخدام C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحديث ملف XLT في C++" %}}

- قم بتحميل ملف XLT باستخدام [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- الوصول إلى [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) ذي الصلة باستخدام GetIWorksheets()->GetObjectByIndex(0) والخلية ذات الصلة باستخدام GetICells()->GetObjectByIndex
- أدخل البيانات الجديدة في الخلية التي تم الوصول إليها باستخدام طريقة PutValue
- احفظ الملف كملف .xlt باستخدام أسلوب الحفظ بتمرير الملف بالمسار كمعامل

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التعديل" %}}

- لتعديل XLT ، باتباع [متطلبات النظام](https://docs.aspose.com/cells/cpp/system-requirements/) لأنظمة Windows و Linux 
- قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp```
- أو عبر وحدة تحكم مدير الحزم في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''
- بدلاً من ذلك ، احصل على مثبت MSI غير المتصل أو DLLs في ملف ZIP من [التحميلات](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="كود - تحديث ملف XLT في C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}