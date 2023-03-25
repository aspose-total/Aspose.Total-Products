---
title: تحويل تنسيق JSON إلى OTT عبر Java
description: تحليل JSON إلى OTT في Java بدون استخدام Microsoft Word
url_ignore: /ar/java/conversion/json-to-ott/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: OTT
otherformats: DOC WORD MOBI RTF DOCM EPUB ODT OTT PS WORDML DOT PCL FLATOPC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى OTT عبر Java" h2="واجهة برمجة تطبيقات Java في الشركة لتحليل JSON إلى OTT بدون استخدام Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) يمكنك تحويل JSON إلى OTT في تطبيقات Java في عملية من خطوتين. أولاً ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) يمكنك تحليل JSON إلى PDF. في الخطوة الثانية ، يمكنك تحويل PDF إلى OTT باستخدام واجهة برمجة تطبيقات معالجة الكلمات [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى OTT عبر Java" %}}
1. أنشئ كائنًا [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) جديدًا واقرأ بيانات JSON الصالحة من الملف
2. استيراد ملف JSON إلى ورقة العمل باستخدام فئة [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) و [Save](https://reference.aspose.com/ cell/java/com.aspose.cells/workbook # save (java.lang.String،٪20com.aspose.cells.SaveOptions)) كملف PDF
3. قم بتحميل مستند PDF باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق OTT باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.com.aspose.words.SaveOptions)) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
علاوة على ذلك ، تسمح لك واجهة برمجة التطبيقات بتعيين خيارات التخطيط لـ JSON أثناء تحليل JSON إلى OTT باستخدام [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى OTT عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحليل JSON إلى OTT باستخدام العلامة المائية. لإضافة علامة مائية إلى مستند OTT ، يمكنك أولاً تحويل ملف JSON إلى PDF وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PDF الذي تم إنشاؤه حديثًا باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) ، وأنشئ مثيلاً لـ TextWatermarkOptions وعيّن خصائصه ، استدعاء طريقة Watermark.setText وتمرير نص العلامة المائية وكائن TextWatermarkOptions. بعد إضافة العلامة المائية ، يمكنك حفظ المستند في غرفة تبادل المعلومات. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}