---
title: تحويل تنسيق JSON إلى DOCM في Android عبر Java
description: تحليل JSON إلى DOCM في Java بدون استخدام Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: DOCM
otherformats: EPUB PCL DOC CHM WORDML WORD ODT MOBI DOTX RTF FLATOPC OTT PS DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل تنسيق JSON إلى DOCM في تطبيقات Android" h2="تحليل JSON إلى DOCM داخل تطبيقات Android بدون استخدام Microsoft <sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل JSON إلى DOCM في تطبيقات Android في عملية من خطوتين. أولاً ، باستخدام واجهة برمجة تطبيقات قوية لمعالجة جداول البيانات [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) يمكنك تحليل JSON إلى PDF. في الخطوة الثانية ، يمكنك تحويل PDF إلى DOCM باستخدام واجهة برمجة تطبيقات معالجة الكلمات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). تندرج واجهتا APIs ضمن عائلة المنتجات [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى DOCM في Android عبر Java" %}}
1. قم بإنشاء كائن [Workbook] جديد(https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) واقرأ بيانات JSON الصالحة من الملف
2. استيراد ملف JSON إلى ورقة العمل باستخدام فئة [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) و [save](https://reference.aspose.com/cell/java/com.aspose.cells/workbook#save(java.lang.String،٪20com.aspose.cells.SaveOptions)) كملف PDF
3. قم بتحميل مستند PDF باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق DOCM باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String،com.aspose.words.SaveOptions)) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت المكتبات في تطبيقك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى DOCM في Android عبر Java" %}}
علاوة على ذلك ، تسمح لك واجهة برمجة التطبيقات بتعيين خيارات التخطيط لتنسيق JSON الخاص بك أثناء تحليل JSON إلى DOCM باستخدام [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة الصفيف كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان الصفيف ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بتحويل تنسيق JSON إلى DOCM باستخدام علامة مائية في Android عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى DOCM بعلامة مائية. لإضافة علامة مائية إلى مستند DOCM ، يمكنك أولاً تحليل ملف JSON إلى PDF وإضافة علامة مائية إليه. لإضافة علامة مائية ، قم بتحميل ملف PDF الذي تم إنشاؤه حديثًا باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) ، وأنشئ مثيلاً لـ TextWatermarkOptions وقم بتعيين خصائصه ، استدعاء طريقة Watermark.setText وتمرير نص العلامة المائية وكائن TextWatermarkOptions. بعد إضافة العلامة المائية ، يمكنك حفظ المستند في غرفة تبادل المعلومات.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}