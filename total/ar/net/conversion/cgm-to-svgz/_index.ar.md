---
title: تحويل CGM إلى SVGZ عبر C# API
description: قم بتصدير CGM إلى SVGZ في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف CGM إلى SVGZ عبر C#" h2="قم بتصدير CGM إلى SVGZ داخل تطبيقات .NET بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تصدير CGM إلى صورة SVGZ ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف CGM إلى SVGZ عبر .NET" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم CGM إلى JPEG باستخدام [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق SVGZ باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى SVGZ في ملف واحد عبر C#" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف CGM](ى SVGZ إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند CGM إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى SVGZ. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق SVGZ باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM وتدويره إلى SVGZ عبر C#" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة SVGZ الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد المناسب [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى SVGZ برمجيًا: حالات الاستخدام" %}}
الملفات CGM (Computer Graphics Metafile) تستخدم لتحميل معلومات حول المعلومات المرئية بالرؤية النصية، مما يجعلها مثالية لإنشاء الصور المرئية الثابتة والرسوم البيانية. ومع ذلك، عندما نعمل مع البيانات المتحركة، مثل الملفات الجدولية مثل إكسيل، تصبح هذه الملفات أساسية لجعل الرسوم البيانية و分析 البيانات.

التحويل من الملفات CGM إلى صيغ SVGZ يunlock潜力الرسوم المرئية والillustrations. هذا التحويل ي允许 لك:

** استخدامات:**

*   **إنشاء الصور المرئية الثابتة**: تحويل الملفات CGM لإنشاء صور مرئية عالية الجودة، الرسوم البيانية، و الشعارات التي هي مثالية للاستخدام في الطباعة أو الإنترنت.

*   **التصميم الحقوق التجارية والهوية**: استخدام SVGZ لتصميم الهويات التجارية، الأيقونات، والرسوم المرئية التي يمكن التوسيعها دون فقدان جودة الصورة عند resize.

*   **التصميم 레이سر و labels**: تحويل الملفات CGM لإنشاء تصميمات 레이سر وlabels مرئية جذابة تتميز في شelves المحفور.

*   **إدارة الأصول الرقمية**: تخزين الملفات CGM في صيغة SVGZ لتحقيق إدارة أصول الرسوم البيانية بسهولة، مما يpermite النقل وال分享 بين الفعاليات بسرعة.

*   **optimization للرسوم المرئية على الانترنت والموبाइल**: استخدام SVGZ لoptimize الملفات CGM للاستخدام على الانترنت والموبايل، مما يضمن وقت التحميل السريع وقدرة الصورة العالية.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}