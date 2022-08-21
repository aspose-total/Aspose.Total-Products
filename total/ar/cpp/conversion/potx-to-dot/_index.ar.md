---
title: C++ API لتحويل POTX إلى DOT
description: قم بتصدير POTX إلى DOT داخل تطبيقات C++ الخاصة بك
url: /ar/cpp/conversion/potx-to-dot/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: DOT
otherformats: WORDML OTT DOC DOCM TEXT ODT DOTX WORD FLATOPC RTF DOTM DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم POTX إلى DOT" h2="تصدير POTX إلى DOT في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint POTX إلى Word DOT. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل POTX إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل POTX إلى DOT" %}}
1. قم بتحميل ملف POTX باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض POTX إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
4. احفظ المستند بتنسيق DOT باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotument
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"htmlOutput.html");
// save dotument in DOT format
dot->Save(u"output.dot"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-wordml/" name="POTX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-ott/" name="POTX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-dot/" name="POTX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-dotm/" name="POTX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-text/" name="POTX إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-odt/" name="POTX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-dotx/" name="POTX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-word/" name="POTX إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-flatopc/" name="POTX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-rtf/" name="POTX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-dotm/" name="POTX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potx-to-dotx/" name="POTX إلى DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}