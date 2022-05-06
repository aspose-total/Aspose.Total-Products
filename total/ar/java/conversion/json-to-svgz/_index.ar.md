---
title: تحويل تنسيق JSON إلى SVGZ عبر Java
description: تحليل JSON إلى SVGZ في Java بدون استخدام Microsoft PowerPoint
url_ignore: /ar/java/conversion/json-to-svgz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: SVGZ
otherformats: IMAGE DICOM TGA WMF WMZ EMZ PSD SVGZ JPEG2000 DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل تنسيق JSON إلى SVGZ عبر Java" h2="Java API لتحليل تنسيق JSON إلى SVGZ في أي تطبيقات Java J2SE و J2EE و J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for Java](https://products.aspose.com/total/java/) ، يمكنك تحويل تنسيق JSON إلى SVGZ داخل أي تطبيق Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.Cells for Java](https://products.aspose.com/cells/java/) ، يمكنك تحليل JSON إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) ، يمكنك تحويل JPEG إلى SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل تنسيق JSON إلى SVGZ عبر Java" %}}
1. قم بإنشاء كائن [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) جديد  وافتح ملف JSON
2. احفظ JSON بتنسيق JPEG باستخدام [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String،٪20com.aspose.cells.SaveOptions)) طريقة
3. قم بتحميل مستند JPEG باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق SVGZ باستخدام [Save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
علاوة على ذلك ، تسمح لك API بتحليل JSON إلى SVGZ بخيارات تخطيط محددة. لتحديد خيارات التخطيط ، يمكنك استخدام فئة [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). يسمح لك بمعالجة مصفوفة كجدول ، وتجاهل القيم الخالية ، وتجاهل عنوان المصفوفة ، وتجاهل عنوان الكائن ، وتحويل السلسلة إلى رقم أو تاريخ ، وتعيين تنسيق التاريخ والأرقام ، وتعيين نمط العنوان. تتيح لك كل هذه الخيارات تقديم بياناتك وفقًا لاحتياجاتك. يوضح لك مقتطف الشفرة التالي كيفية تعيين خيارات التخطيط.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتعيين التخطيط وتحويل تنسيق JSON إلى SVGZ عبر Java" %}}
باستخدام API ، يمكنك أيضًا تحويل JSON إلى SVGZ بعلامة مائية في مستند SVGZ الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل JSON إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Grpahics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-jpeg2000/" name="JSON ل JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-emz/" name="JSON ل EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-psd/" name="JSON ل PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-wmf/" name="JSON ل WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-wmz/" name="JSON ل WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dxf/" name="JSON ل DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-image/" name="JSON ل IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-svgz/" name="JSON ل SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-dicom/" name="JSON ل DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/json-to-tga/" name="JSON ل TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}