---
title: تحويل CGM إلى EMZ عبر C# API
description: قم بتصدير CGM إلى EMZ في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url_ignore: /ar/net/conversion/cgm-to-emz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: EMZ
otherformats: SVGZ WMF PSD EMZ WMZ TGA JPEG2000 IMAGE DXF  DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف CGM إلى EMZ عبر C#" h2="قم بتصدير CGM إلى EMZ داخل تطبيقات .NET بدون استخدام Adobe<sup>&reg;</sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET](https://products.aspose.com/total/net/) يمكنك بسهولة تصدير CGM إلى صورة EMZ ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) ، يمكنك تصدير CGM إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف CGM إلى EMZ عبر .NET" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم CGM إلى JPEG باستخدام [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق EMZ باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ ``nuget install Aspose.Total`` أو عبر Package Manager Console في Visual Studio مع ``Install-Package Aspose.Total``.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [Downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى EMZ في ملف واحد عبر C#" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف CG](لى EMZ إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند CGM إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى EMZ. يمكنك فتح ملف الإدخال باستخدام فئة [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق EMZ باستخدام طريقة [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM وتدويره إلى EMZ عبر C#" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة EMZ الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد المناسب [RotateFlipType](https://reference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف CGM إلى EMZ برمجيًا: حالات الاستخدام" %}}
التحويل من ملفات CGM إلى صيغات EMZ هو 必要步骤 لتمكين القدرة الكاملة على تحليل البيانات وتعزيز قدراتك في مجال الإشعاع الرقمي. يتيح هذا التحويل لك استخدام:

**الاستخدامات:**

*   ** إدارة محتوى الإشعاع الرقمي**: تحويل ملفات CGM لتحكم بمحتوى الإشعاع الرقمي، تحديث العروض الإلكترونية، وتزامن العناصر المتعددة الوسيط.

*   ** تطوير الألعاب الإلكترونية**: استخدام صيغة EMZ لإنشاء بيئات لعبية تفاعلية، تجسيد لعب游戏، وتحسين أداء الصور.

*   **编辑矢量图形**: تحويل ملفات CGM لتعديل الصور النصفي في صيغة EMZ، مما يمنحك سيطرة متكاملة على الشكل والخطوط والنصوص.

*   ** إرسال محتوى ويب**: استخدام صيغة EMZ لإرسال المحتوى الويب، بما في ذلك الصور النصفي والillustrations، لتحسين تجربة المستخدمين وسرعة التحميل.

*   ** تصميم CAD وتصنيع المنتجات**: تحويل ملفات CGM لإنشاء تصميمات CAD متقدمة، وتحليل العمليات الصناعية، وتحسين أداء المنتج.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}