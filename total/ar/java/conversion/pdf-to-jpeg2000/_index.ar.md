---
title: تحويل PDF إلى JPEG2000 عبر Java
description: قم بتصدير ملف PDF إلى JPEG2000 في تطبيقات Java الخاصة بك دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/java/conversion/pdf-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: JPEG2000
otherformats: EMZ  WMF DXF JPEG2000 TGA SVGZ WMZ PSD IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل PDF إلى JPEG2000 عبر Java" h2="قم بتصدير ملف PDF إلى JPEG2000 داخل أي تطبيقات Java J2SE و J2EE و J2ME بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل ملف pdf إلى صورة JPEG2000 في Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير PDF إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى JPEG2000. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تصدير PDF إلى JPEG2000 عبر Java" %}}
1. افتح ملف PDF باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. قم بتهيئة كائن فئة وتقديم PDF إلى JPEG باستخدام [process](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق JPEG2000 باستخدام [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="تحويل PDF إلى JPEG2000 في ملف واحد عبر Java" %}}
تسمح لك API أيضًا بتصدير ملف PDF إلى JPEG2000 إلى ملف واحد. لتحويل جميع الصفحات ، يمكنك أولاً تحويل مستند PDF إلى ملف TIFF واحد وبعد ذلك ، يمكنك تصدير ملف TIFF إلى JPEG2000. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) لفئة [TiffDevice](https://apireference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) وحفظه بتنسيق JPEG2000 باستخدام [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل PDF إلى JPEG2000 باستخدام علامة مائية عبر Java" %}}
باستخدام API ، يمكنك أيضًا تصدير ملف PDF إلى JPEG2000 بعلامة مائية في مستند JPEG2000 الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل PDF إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Graphics](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Matrix) جديدة  وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق JPEG2000. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل وتدوير PDF إلى ملف JPEG2000 عبر Java" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة JPEG2000 الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.rotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. توفر المكتبة طرقًا بسيطة لإجراء عمليات معقدة مع تغليف جميع التفاصيل القبيحة. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام فئة [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image) واستدعاء الصورة. rotateFlip أثناء تحديد المناسب [RotateFlipType](https://apireference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-emz/" name="PDF ل EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-tga/" name="PDF ل TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-jpeg2000/" name="PDF ل JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-image/" name="PDF ل IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-psd/" name="PDF ل PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-wmz/" name="PDF ل WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-svgz/" name="PDF ل SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to/" name="PDF ل" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-wmf/" name="PDF ل WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-dxf/" name="PDF ل DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/pdf-to-dicom/" name="PDF ل DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}