---
title: C++ API لتحويل PPSX إلى DOTM
description: قم بتصدير PPSX إلى DOTM داخل تطبيقات C++ الخاصة بك
url: /ar/cpp/conversion/ppsx-to-dotm/
family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: DOTM
otherformats: WORDML DOT DOCM TEXT DOC ODT OTT DOTX WORD RTF DOCX FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم PPSX إلى DOTM" h2="تصدير PPSX إلى DOTM في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint PPSX إلى Word DOTM. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل PPSX إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل PPSX إلى DOTM" %}}
1. قم بتحميل ملف PPSX باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض PPSX إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument)
4. احفظ المستند بتنسيق DOTM باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotmument
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"htmlOutput.html");
// save dotmument in DOTM format
dotm->Save(u"output.dotm"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-wordml/" name="PPSX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-dot/" name="PPSX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-dotmm/" name="PPSX إلى DOTMM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-text/" name="PPSX إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-dotm/" name="PPSX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-odt/" name="PPSX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-ott/" name="PPSX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-dotx/" name="PPSX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-word/" name="PPSX إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-rtf/" name="PPSX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-dotmx/" name="PPSX إلى DOTMX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ppsx-to-flatopc/" name="PPSX إلى FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}