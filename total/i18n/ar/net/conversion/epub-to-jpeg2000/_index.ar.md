---
title: تحويل EPUB إلى JPEG2000 عبر C # API
description: قم بتصدير EPUB إلى JPEG2000 في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url: /ar/net/conversion/epub-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: JPEG2000
otherformats: JPEG2000 WMZ WMF TGA PSD EMZ SVGZ IMAGE  DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف EPUB إلى JPEG2000 عبر C #" h2="قم بتصدير EPUB إلى JPEG2000 داخل تطبيقات .NET بدون استخدام Adobe <sup> & reg؛ </sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET] (https://products.aspose.com/total/net/) يمكنك بسهولة تصدير EPUB إلى صورة JPEG2000 ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) ، يمكنك تصدير EPUB إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET] (https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف EPUB إلى JPEG2000 عبر .NET" %}}
1. افتح ملف EPUB باستخدام فئة [Document] (https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم EPUB إلى JPEG باستخدام [معالجة] (https: //apireference.aspose. com / pdf / net / aspose.pdf.devices.pagedevice / عملية / طرق / 1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق JPEG2000 باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EPUB إلى JPEG2000 في ملف واحد عبر C #" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف EPUB إلى JPEG2000 إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند EPUB إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى JPEG2000. يمكنك فتح ملف الإدخال باستخدام فئة [المستند] (https://apireference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [معالجة] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice] (https: // apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق JPEG2000 باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف EPUB وتدويره إلى JPEG2000 عبر C #" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة JPEG2000 الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image] (https://apireference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد [RotateFlipType] المناسب (https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-emz/" name="EPUB ل EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-tga/" name="EPUB ل TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-jpeg2000/" name="EPUB ل JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-image/" name="EPUB ل IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-psd/" name="EPUB ل PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-wmz/" name="EPUB ل WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-svgz/" name="EPUB ل SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to/" name="EPUB ل" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-wmf/" name="EPUB ل WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-dxf/" name="EPUB ل DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/epub-to-dicom/" name="EPUB ل DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}