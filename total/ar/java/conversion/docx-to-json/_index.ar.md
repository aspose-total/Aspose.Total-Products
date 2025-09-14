---
title: تحويل DOCX إلى تنسيق JSON عبر Java
description: قم بتحويل تنسيق DOCX إلى تنسيق JSON عبر Java دون استخدام Microsoft Word أو Microsoft Excel
url_ignore: /ar/java/conversion/docx-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCX
outformat: JSON
otherformats: XLAM XLSM DIF XLT CSV XLTX XLSX TSV ODS XLTM EXCEL FODS XLS XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل DOCX إلى تنسيق JSON عبر Java" h2="في Premise Java API لتحويل DOCX إلى JSON بدون استخدام Microsoft<sup>&reg;</sup> Word أو Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
تحويل DOCX إلى تنسيق JSON عبر [Aspose.Total for Java](https://products.aspose.com/total/java/) هي عملية بسيطة من خطوتين. باستخدام واجهة برمجة تطبيقات معالجة المستندات والتحويل الغنية بالميزات [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تصدير DOCX إلى HTML. بعد ذلك ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحويل HTML إلى JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOCX إلى تنسيق JSON عبر Java" %}}
1. افتح ملف DOCX باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. تحويل DOCX إلى HTML باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
3. قم بتحميل مستند HTML باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. احفظ المستند بتنسيق JSON باستخدام [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String%D8%8C%D9%AA20com.aspose.cells.%20SaveOptions)) الطريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
باستخدام API ، يمكنك أيضًا فتح المستند المحمي بكلمة مرور. إذا كان مستند DOCX الذي تم إدخاله محميًا بكلمة مرور ، فلا يمكنك تحويله إلى تنسيق JSON دون استخدام كلمة المرور. تسمح لك واجهة برمجة التطبيقات بفتح المستند المشفر عن طريق تمرير كلمة المرور الصحيحة في كائن LoadOptions. يوضح المثال التالي من التعليمات البرمجية كيفية محاولة فتح مستند مشفر بكلمة مرور:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل DOCX المحمي إلى تنسيق JSON عبر Java" %}}
أثناء قيامك بتحويل DOCX إلى JSON ، يمكنك أيضًا ضبط النطاق على تنسيق JSON الناتج. لتعيين النطاق ، يمكنك فتح HTML المحول باستخدام فئة Workbook ، وإنشاء نطاق من البيانات ليتم تصديرها باستخدام طريقة Cells.createRange ، واستدعاء طريقة JsonUtility.exportRangeToJson مع مراجع Range & ExportRangeToJsonOptions وكتابة سلسلة بيانات JSON إلى ملف عبر طريقة BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
<h2>استخدامات رئيسية ✅</h2>
- استخراج محتوى منظم لـ **واجهات برمجة التطبيقات (APIs)**  
- تمكين تطبيقات الويب التي تعتمد على **المستندات**  
- نقل بيانات DOCX إلى **أنظمة إدارة المحتوى الرأسية (headless CMS)**  
- دعم **أنابيب تعلم الآلة**  
- تبادل البيانات في **تطبيقات المؤسسات**  

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}
- **أنابيب API الضخمة لتحويل DOCX إلى JSON**  
- **تقارير مستندة على JSON تلقائية**  
- **أنظمة تحليل المستندات**  
- **أنظمة التكامل مع الويب**  
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}