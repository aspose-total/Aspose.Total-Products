---
title: تحويل PDF إلى IMAGE عبر C # API
description: قم بتصدير PDF إلى IMAGE في تطبيقات .NET دون استخدام أي تطبيق تابع لجهة خارجية
url: /ar/net/conversion/pdf-to-image/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: JPEG2000
otherformats: JPEG2000 EMZ  WMZ TGA PSD DXF WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل ملف PDF إلى IMAGE عبر C #" h2="قم بتصدير PDF إلى IMAGE داخل تطبيقات .NET بدون استخدام Adobe <sup> & reg؛ </sup> Acrobat Reader أو أي تطبيقات أخرى تابعة لجهات خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
باستخدام [Aspose.Total for .NET] (https://products.aspose.com/total/net/) يمكنك بسهولة تصدير PDF إلى صورة IMAGE ضمن أي تطبيقات .NET في خطوتين بسيطتين. بادئ ذي بدء ، باستخدام [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) ، يمكنك تصدير PDF إلى JPEG. بعد ذلك ، باستخدام [Aspose.Imaging for .NET] (https://products.aspose.com/imaging/net/) واجهة برمجة تطبيقات معالجة الصور ، يمكنك تحويل JPEG إلى IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملف PDF إلى IMAGE عبر .NET" %}}
1. افتح ملف PDF باستخدام فئة [Document] (https://apireference.aspose.com/pdf/net/aspose.pdf/document)
2. تهيئة [JpegDevice] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) كائن فئة وتقديم PDF إلى JPEG باستخدام [معالجة] (https: //apireference.aspose. com / pdf / net / aspose.pdf.devices.pagedevice / عملية / طرق / 1) طريقة
3. قم بتحميل ملف JPEG باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
4. احفظ المستند بتنسيق IMAGE باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total ''` أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total' '.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات] (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PDF إلى IMAGE في ملف واحد عبر C #" %}}
باستخدام API ، يمكنك أيضًا تحويل ملف PDF إلى IMAGE إلى ملف صورة واحد. لتحويل كل الصفحات ، يمكنك أولاً تحويل مستند PDF إلى ملف TIFF واحد وبعد ذلك يمكنك تصدير ملف TIFF إلى IMAGE. يمكنك فتح ملف الإدخال باستخدام فئة [المستند] (https://apireference.aspose.com/pdf/net/aspose.pdf/document) وإنشاء كائنات جهاز Resolution و TiffSettings و TIFF. يمكنك الحصول على صورة TIFF واحدة باستخدام طريقة [معالجة] (https://apireference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) من [TiffDevice] (https: // apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice) فئة. أخيرًا ، يمكنك تحميل ملف TIFF باستخدام فئة [صورة] (https://apireference.aspose.com/imaging/net/aspose.imaging/image)
واحفظه في تنسيق IMAGE باستخدام طريقة [حفظ] (https://apireference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل ملف PDF وتدويره إلى IMAGE عبر C #" %}}
باستخدام API ، يمكنك أيضًا تدوير صورة IMAGE الناتجة وفقًا لاحتياجاتك. يمكن استخدام طريقة Image.RotateFlip لتدوير الصورة بمقدار 90/180/270 درجة وقلب الصورة أفقيًا أو رأسيًا. يمكنك تحديد نوع التدوير والوجه لتطبيقه على الصورة. لتدوير الصورة وعكسها ، يمكنك تحميل صورة JPEG المحولة باستخدام طريقة المصنع المكشوفة بواسطة فئة [Image] (https://apireference.aspose.com/imaging/net/aspose.imaging/image) واستدعاء الصورة .RotateFlip أثناء تحديد [RotateFlipType] المناسب (https://apireference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}
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