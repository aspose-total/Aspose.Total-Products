---
title: تحويل PS إلى SVGZ عبر Java
description: قم بتصدير ملف PS إلى SVGZ في تطبيقات Java الخاصة بك دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/java/conversion/ps-to-svgz/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SVGZ
otherformats: DXF WMF IMAGE  SVGZ TGA WMZ JPEG2000 PSD EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل PS إلى SVGZ عبر Java" h2="قم بتصدير ملف PS إلى SVGZ داخل أي تطبيقات Java J2SE و J2EE و J2ME بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل ملف ps إلى صورة SVGZ في Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير PS إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى SVGZ. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تصدير PS إلى SVGZ عبر Java" %}}
1. افتح ملف PS باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. قم بتهيئة كائن فئة وتقديم PS إلى JPEG باستخدام [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق SVGZ باستخدام [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="تحويل PS إلى SVGZ في ملف واحد عبر Java" %}}
تسمح لك API أيضًا بتصدير ملف PS إلى SVGZ إلى ملف واحد. لتحويل جميع الصفحات ، يمكنك أولاً تحويل مستند PS إلى ملف TIFF واحد وبعد ذلك ، يمكنك تصدير ملف TIFF إلى SVGZ. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) لفئة [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) وحفظه بتنسيق SVGZ باستخدام [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل PS إلى SVGZ باستخدام علامة مائية عبر Java" %}}
باستخدام API ، يمكنك أيضًا تصدير ملف PS إلى SVGZ بعلامة مائية في مستند SVGZ الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل PS إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) جديدة  وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق SVGZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل وتدوير PS إلى ملف SVGZ عبر Java" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة SVGZ الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.rotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. توفر المكتبة طرقًا بسيطة لإجراء عمليات معقدة مع تغليف جميع التفاصيل القبيحة. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) واستدعاء الصورة. rotateFlip أثناء تحديد المناسب [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

تحويل PS (PostScript) إلى SVGZ (Compressed Scalable Vector Graphics) يضمن رؤية عالية الجودة وغير معتمدة على الدقة مع حجم ملفات مقلص بشكل كبير. ملفات SVGZ مثالية لتصميم الويب والجوال وواجهات المستخدم بسبب قابليتها للتوسيع وكفاءة الضغط.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}

* تحويل الرسوم البيانية PS إلى رسومات نقطية قابلة للتوسيع لواجهات الويب.
* تحسين الرسوم التوضيحية التقنية لمواقع الويب الاستجابية ولوحات القيادة.
* تضمين الرسوم البيانية PS المضغوطة في تطبيقات الجوال الخفيفة.
* إعداد رسومات نقطية تفاعلية لأنظمة التصميم والدلائل الرقمية.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}

* ضغط PS إلى SVGZ بشكل آلي لتحسين محتوى المواقع القائمة على نظام إدارة المحتوى.
* دمجها في خطوط إنتاج إدارة الأصول النقطية.
* تقديم رسوم PS بشكل دفعي إلى تنسيقات مضغوطة للنشر الرقمي.
* تحسين الرسوم النقطية السحابية لمنصات الويب التفاعلية.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}