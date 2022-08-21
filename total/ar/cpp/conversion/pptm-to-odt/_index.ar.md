---
title: C++ API لتحويل PPTM إلى ODT
description: قم بتصدير PPTM إلى ODT داخل تطبيقات C++ الخاصة بك
url: /ar/cpp/conversion/pptm-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: ODT
otherformats: FLATOPC DOCX DOC WORD DOTX DOCM DOTM WORDML RTF DOT OTT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم PPTM إلى ODT" h2="تصدير PPTM إلى ODT في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint PPTM إلى Word ODT. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل PPTM إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل PPTM إلى ODT" %}}
1. قم بتحميل ملف PPTM باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض PPTM إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. احفظ المستند بتنسيق ODT باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-flatopc/" name="PPTM إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-odtx/" name="PPTM إلى ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-odt/" name="PPTM إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-word/" name="PPTM إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-dotx/" name="PPTM إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-odtm/" name="PPTM إلى ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-dotm/" name="PPTM إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-wordml/" name="PPTM إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-rtf/" name="PPTM إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-dot/" name="PPTM إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-ott/" name="PPTM إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pptm-to-text/" name="PPTM إلى TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}