---
title: تحويل PS إلى EMZ عبر C # API
description: قم بتصدير PS إلى EMZ في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url: /ar/net/conversion/ps-to-emz/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: EMZ
otherformats: WMF TGA WMZ JPEG2000 IMAGE  PSD SVGZ EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف PS إلى EMZ عبر C #" h2="قم بتصدير PS إلى EMZ داخل تطبيقات .NET بدون استخدام Adobe <sup> & reg؛ </sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET] (https://products.aspose.com/total/net/) يمكنك بسهولة تصدير PS إلى صورة EMZ ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) ، يمكنك تصدير PS إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET] (https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف PS إلى EMZ عبر .NET" %}}
1. افتح ملف PS باستخدام فئة [Document] (https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم PS إلى JPEG باستخدام [معالجة] (https: //apireference.aspose. com / pdf / net / aspose.pdf.devices.pagedevice / عملية / طرق / 1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق EMZ باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS إلى EMZ في ملف واحد عبر C #" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف PS إلى EMZ إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند PS إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى EMZ. يمكنك فتح ملف الإدخال باستخدام فئة [المستند] (https://apireference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [معالجة] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice] (https: // apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق EMZ باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PS وتدويره إلى EMZ عبر C #" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة EMZ الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image] (https://apireference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد [RotateFlipType] المناسب (https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-emz/" name="PS ل EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-tga/" name="PS ل TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-jpeg2000/" name="PS ل JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-image/" name="PS ل IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-psd/" name="PS ل PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-wmz/" name="PS ل WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-svgz/" name="PS ل SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to/" name="PS ل" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-wmf/" name="PS ل WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-dxf/" name="PS ل DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/ps-to-dicom/" name="PS ل DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}