---
title: C++ API لتحويل POTM إلى WORDML
description: قم بتصدير POTM إلى WORDML داخل تطبيقات C++ الخاصة بك

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: WORDML
otherformats: OTT DOT DOCX RTF DOTX TEXT WORD FLATOPC DOC DOTM DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم POTM إلى WORDML" h2="تصدير POTM إلى WORDML في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint POTM إلى Word WORDML. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل POTM إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى WORDML. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل POTM إلى WORDML" %}}
1. قم بتحميل ملف POTM باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض POTM إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument)
4. احفظ المستند بتنسيق WORDML باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load POTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.potm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Wordmlument
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"htmlOutput.html");
// save wordmlument in WORDML format
wordml->Save(u"output.wordml"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ POTM إلى WORDML</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=wordml&from=potm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-ott/" name="POTM إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-dot/" name="POTM إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-wordmlx/" name="POTM إلى WORDMLX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-rtf/" name="POTM إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-dotx/" name="POTM إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-text/" name="POTM إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-word/" name="POTM إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-flatopc/" name="POTM إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-wordml/" name="POTM إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-dotm/" name="POTM إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-wordmlm/" name="POTM إلى WORDMLM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/potm-to-odt/" name="POTM إلى ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}