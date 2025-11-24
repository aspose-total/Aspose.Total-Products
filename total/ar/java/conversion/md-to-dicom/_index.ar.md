---
title: تحويل MD إلى DICOM عبر Java
description: قم بتصدير ملف MD إلى DICOM في تطبيقات Java الخاصة بك دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/java/conversion/md-to-dicom/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DICOM
otherformats: TGA PSD DXF WMF DICOM SVGZ JPEG2000 EMZ WMZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل MD إلى DICOM عبر Java" h2="قم بتصدير ملف MD إلى DICOM داخل أي تطبيقات Java J2SE و J2EE و J2ME بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل ملف md إلى صورة DICOM في Java في خطوتين بسيطتين. أولاً ، باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) ، يمكنك تصدير MD إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى DICOM. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تصدير MD إلى DICOM عبر Java" %}}
1. افتح ملف MD باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. قم بتهيئة كائن فئة وتقديم MD إلى JPEG باستخدام [process](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. احفظ المستند بتنسيق DICOM باستخدام [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) طريقة
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="تحويل MD إلى DICOM في ملف واحد عبر Java" %}}
تسمح لك API أيضًا بتصدير ملف MD إلى DICOM إلى ملف واحد. لتحويل جميع الصفحات ، يمكنك أولاً تحويل مستند MD إلى ملف TIFF واحد وبعد ذلك ، يمكنك تصدير ملف TIFF إلى DICOM. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) لفئة [TiffDevice](https://reference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) وحفظه بتنسيق DICOM باستخدام [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل MD إلى DICOM باستخدام علامة مائية عبر Java" %}}
باستخدام API ، يمكنك أيضًا تصدير ملف MD إلى DICOM بعلامة مائية في مستند DICOM الخاص بك. لإضافة علامة مائية ، يمكنك أولاً تحويل MD إلى JPEG وإضافة علامة مائية فيه. لإضافة علامة مائية ، قم بتحميل ملف صورة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) ، قم بإنشاء كائن من [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) فئة وتهيئتها باستخدام كائن صورة ، وإنشاء [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) جديدة  وقم بتعيين الترجمة والتحويل إلى الزاوية المطلوبة وإضافة علامة مائية باستخدام [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics). بعد إضافة العلامة المائية في صورتك ، يمكنك حفظ JPEG بتنسيق DICOM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="قم بتحويل وتدوير MD إلى ملف DICOM عبر Java" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة DICOM الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.rotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. توفر المكتبة طرقًا بسيطة لإجراء عمليات معقدة مع تغليف جميع التفاصيل القبيحة. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام فئة [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image) واستدعاء الصورة. rotateFlip أثناء تحديد المناسب [RotateFlipType](https://reference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



تحويل ملفات التنسيق Markdown (MD) إلى تنسيق DICOM (Digital Imaging and Communications in Medicine) يمكن من دمج الوثائق النصية أو التعليقات في سير العمل الخاصة بالصور الطبية. يدعم DICOM البيانات الوصفية، والهياكل القياسية للصور، وهو مثالي لأنظمة المستشفيات والبيئات البحثية.



{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}



* تضمين ملاحظات سريرية قائمة على Markdown في أرشيف الصور الطبية.

* إنشاء رسوم توضيحية هيكلية لتعليم المرضى باستخدام محتوى Markdown.

* دمج وثائق البحث في مجموعات بيانات الصور المتوافقة مع DICOM.

* تخزين التعليقات القائمة على النصوص بجانب صور الأشعة التشخيصية.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات الأتمتة" %}}



* توليد MD-to-DICOM تلقائي لأنظمة توثيق المستشفيات.

* معالجة دفعية لملفات Markdown السريرية لدمجها في سجلات الصحة الإلكترونية.

* خطوط أنابيب التحويل المجدولة تغذي أرشيفات DICOM.

* تقديم تقارير Markdown بجانب بيانات الصور لتشخيص مساعد بواسطة الذكاء الاصطناعي.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}