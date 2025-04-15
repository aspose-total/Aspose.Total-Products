---
title: تحويل CGM إلى JPEG2000 عبر C# API
description: قم بتصدير CGM إلى JPEG2000 في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/net/conversion/cgm-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: JPEG2000
otherformats: WMF  TGA DXF IMAGE WMZ JPEG2000 PSD SVGZ EMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف CGM إلى JPEG2000 عبر C#" h2="قم بتصدير CGM إلى JPEG2000 داخل تطبيقات .NET بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تصدير CGM إلى صورة JPEG2000 ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف CGM إلى JPEG2000 عبر .NET" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم CGM إلى JPEG باستخدام [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق JPEG2000 باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى JPEG2000 في ملف واحد عبر C#" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف CGM إلى](EG2000 إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند CGM إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى JPEG2000. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق JPEG2000 باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM وتدويره إلى JPEG2000 عبر C#" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة JPEG2000 الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد المناسب [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى JPEG2000 برمجيًا: حالات الاستخدام" %}}
ملفات CGM (Computer Graphics Metafile) تستخدم لتخزين معلومات عن الصور النصية، مما يجعلها مثالية لإنشاء الصور الثابتة والillustrations. ومع ذلك، عند العمل مع البيانات动态ية، تصبح صور مثل JPEG 2000 أساسية لتحقيق الأفضلية في压缩 وتجديد الجودة.

تحويل ملفات CGM إلى صيغ JPEG 2000 ضروري للاستخدام الكامل لاستطاعاتك في压缩 الصور وتحسين الجودة. هذا التحول يسمح لك استخدام:

**تطبيقات الاستخدام:**

*   **编辑高质量图像**: تحويل ملفات CGM إلى صور عالية الجودة، تحسين الصور لل استخدام على الإنترنت، وضمان برند متstable في جميع المواد التسويقية.
  
*   **تطبيقات الأرشيف والحفظ**: استخدام JPEG 2000 لضغط وتخزين datasets كبيرة من الصور، مما يضمن الحفاظ طويل الأمد وسهولة الوصول إلى محتوى رخيص.

*   **التصوير الطبي والتشخيص**: تحويل ملفات CGM إلى صور طبيعية تفصيلية عالية الجودة للمستخدمين التشخيصية، مما يقلل من الأخطاء وتحسين نتيجة المريض.

*   **ال研究科学ي وال出版**: استخدام JPEG 2000 لضغط ونشر datasets كبيرة من الصور العلمية، مما يساعد على التكامل العالمي وال分享 المعرفة.

*   **المعارض الرقمية والأرشيفات**: تحويل ملفات CGM إلى مكتبة رقمية مرنة عالية الجودة، مما يحافظ على التراث الثقافي والآثار التاريخية لآجياء الأجيال.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}