---
title: تصدير POTM إلى RTF على Andorid عبر Java
description: قم بتحويل POTM إلى RTF في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج

family: total
platformtag: cpp
feature: conversion
informat: POTM
outformat: RTF
otherformats: ODT DOT TEXT DOTM DOCM DOCX WORDML DOTX FLATOPC WORD OTT DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم POTM إلى RTF على Andorid عبر Java" h2="تنسيق ملف APIs لتحويل POTM إلى RTF داخل تطبيقات Android دون الاعتماد على Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يسمح [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) بمعالجة تنسيقات الملفات داخل تطبيقات Android. باستخدام واجهات برمجة التطبيقات المتوفرة في الحزمة ، يمكنك أتمتة عملية تحويل PowerPoint POTM إلى Word RTF في تطبيقاتك.
يمكنك تحويل المستند الخاص بك في خطوتين. يمكنك استخدام [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) وهي واجهة برمجة تطبيقات PowerPoint لتطبيقات Android لتقديم POTM إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) يمكنك تحويل HTML إلى RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تقديم POTM إلى RTF في Android" %}}
1. افتح ملف POTM باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل POTM إلى HTML باستخدام [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام فئة [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. احفظ المستند بتنسيق RTF باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save (java.lang.String، int)) وقم بتعيين Rtf باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Slides لنظام Android عبر Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) و [Aspose.Words for Andorid via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في التطبيقات.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a POTM file
Presentation presentation = new Presentation("input.potm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Rtfument
Rtfument rtfument = new Rtfument("htmlOutput.html");
// save rtfument in RTF format
rtfument.save("output.rtf",SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-odt/" name="POTM إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-dot/" name="POTM إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-text/" name="POTM إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-dotm/" name="POTM إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-rtfm/" name="POTM إلى RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-rtfx/" name="POTM إلى RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-wordml/" name="POTM إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-dotx/" name="POTM إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-flatopc/" name="POTM إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-word/" name="POTM إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-ott/" name="POTM إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/potm-to-rtf/" name="POTM إلى RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}