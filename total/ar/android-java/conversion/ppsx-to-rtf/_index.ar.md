---
title: تصدير PPSX إلى RTF على Andorid عبر Java
description: قم بتحويل PPSX إلى RTF في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: RTF
otherformats: DOT DOTM DOTX DOCX TEXT FLATOPC ODT WORD WORDML DOCM DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم PPSX إلى RTF على Andorid عبر Java" h2="تنسيق ملف APIs لتحويل PPSX إلى RTF داخل تطبيقات Android دون الاعتماد على Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يسمح [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) بمعالجة تنسيقات الملفات داخل تطبيقات Android. باستخدام واجهات برمجة التطبيقات المتوفرة في الحزمة ، يمكنك أتمتة عملية تحويل PowerPoint PPSX إلى Word RTF في تطبيقاتك.
يمكنك تحويل المستند الخاص بك في خطوتين. يمكنك استخدام [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) وهي واجهة برمجة تطبيقات PowerPoint لتطبيقات Android لتقديم PPSX إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) يمكنك تحويل HTML إلى RTF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تقديم PPSX إلى RTF في Android" %}}
1. افتح ملف PPSX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل PPSX إلى HTML باستخدام [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام فئة [Rtfument](https://reference.aspose.com/words/java/com.aspose.words/Rtfument)
4. احفظ المستند بتنسيق RTF باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Rtfument#save (java.lang.String، int)) وقم بتعيين Rtf باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Slides لنظام Android عبر Java](https://rtfs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) و [Aspose.Words for Andorid via Java](https://rtfs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في التطبيقات.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSX file
Presentation presentation = new Presentation("input.ppsx");
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-dot/" name="PPSX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-dotm/" name="PPSX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-dotx/" name="PPSX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-rtfx/" name="PPSX إلى RTFX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-text/" name="PPSX إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-flatopc/" name="PPSX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-odt/" name="PPSX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-word/" name="PPSX إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-wordml/" name="PPSX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-rtfm/" name="PPSX إلى RTFM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-rtf/" name="PPSX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsx-to-ott/" name="PPSX إلى OTT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}