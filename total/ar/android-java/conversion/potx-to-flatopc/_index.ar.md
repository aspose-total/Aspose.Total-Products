---
title: تصدير POTX إلى FLATOPC على Andorid عبر Java
description: قم بتحويل POTX إلى FLATOPC في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج
url: /ar/android-java/conversion/potx-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: POTX
outformat: FLATOPC
otherformats: ODT TEXT WORDML DOCX DOTM DOC DOT RTF WORD DOCM OTT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم POTX إلى FLATOPC على Andorid عبر Java" h2="تنسيق ملف APIs لتحويل POTX إلى FLATOPC داخل تطبيقات Android دون الاعتماد على Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يسمح [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) بمعالجة تنسيقات الملفات داخل تطبيقات Android. باستخدام واجهات برمجة التطبيقات المتوفرة في الحزمة ، يمكنك أتمتة عملية تحويل PowerPoint POTX إلى Word FLATOPC في تطبيقاتك.
يمكنك تحويل المستند الخاص بك في خطوتين. يمكنك استخدام [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) وهي واجهة برمجة تطبيقات PowerPoint لتطبيقات Android لتقديم POTX إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) يمكنك تحويل HTML إلى FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تقديم POTX إلى FLATOPC في Android" %}}
1. افتح ملف POTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل POTX إلى HTML باستخدام [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام فئة [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)
4. احفظ المستند بتنسيق FLATOPC باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save (java.lang.String، int)) وقم بتعيين Flatopc باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Slides لنظام Android عبر Java](https://flatopcs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) و [Aspose.Words for Andorid via Java](https://flatopcs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في التطبيقات.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTX file
Presentation presentation = new Presentation("input.potx");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("htmlOutput.html");
// save flatopcument in FLATOPC format
flatopcument.save("output.flatopc",SaveFormat.FlatOpc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-odt/" name="POTX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-text/" name="POTX إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-wordml/" name="POTX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-flatopcx/" name="POTX إلى FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-dotm/" name="POTX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-flatopc/" name="POTX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-dot/" name="POTX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-rtf/" name="POTX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-word/" name="POTX إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-flatopcm/" name="POTX إلى FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-ott/" name="POTX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potx-to-dotx/" name="POTX إلى DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}