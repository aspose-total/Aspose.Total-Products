---
title: C++ API لتحويل POT إلى DOTX
description: قم بتصدير POT إلى DOTX داخل تطبيقات C++ الخاصة بك
url: /ar/cpp/conversion/pot-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: POT
outformat: DOTX
otherformats: FLATOPC DOT WORD RTF ODT TEXT DOTM DOC WORDML DOCM DOCX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم POT إلى DOTX" h2="تصدير POT إلى DOTX في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint POT إلى Word DOTX. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل POT إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى DOTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل POT إلى DOTX" %}}
1. قم بتحميل ملف POT باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض POT إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
4. احفظ المستند بتنسيق DOTX باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pot");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotxument
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"htmlOutput.html");
// save dotxument in DOTX format
dotx->Save(u"output.dotx"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-flatopc/" name="POT إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-dot/" name="POT إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-word/" name="POT إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-rtf/" name="POT إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-odt/" name="POT إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-text/" name="POT إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-dotm/" name="POT إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-dotx/" name="POT إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-wordml/" name="POT إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-dotxm/" name="POT إلى DOTXM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-dotxx/" name="POT إلى DOTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/pot-to-ott/" name="POT إلى OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}