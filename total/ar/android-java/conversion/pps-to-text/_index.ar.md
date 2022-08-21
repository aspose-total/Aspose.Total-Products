---
title: تصدير PPS إلى TEXT على Andorid عبر Java
description: قم بتحويل PPS إلى TEXT في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج
url: /ar/android-java/conversion/pps-to-text/
family: total
platformtag: cpp
feature: conversion
informat: PPS
outformat: TEXT
otherformats: WORD DOTM DOC RTF FLATOPC DOCM WORDML DOCX DOTX OTT DOT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم PPS إلى TEXT على Andorid عبر Java" h2="تنسيق ملف APIs لتحويل PPS إلى TEXT داخل تطبيقات Android دون الاعتماد على Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يسمح [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) بمعالجة تنسيقات الملفات داخل تطبيقات Android. باستخدام واجهات برمجة التطبيقات المتوفرة في الحزمة ، يمكنك أتمتة عملية تحويل PowerPoint PPS إلى Word TEXT في تطبيقاتك.
يمكنك تحويل المستند الخاص بك في خطوتين. يمكنك استخدام [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) وهي واجهة برمجة تطبيقات PowerPoint لتطبيقات Android لتقديم PPS إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) يمكنك تحويل HTML إلى TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تقديم PPS إلى TEXT في Android" %}}
1. افتح ملف PPS باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل PPS إلى HTML باستخدام [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام فئة [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)
4. احفظ المستند بتنسيق TEXT باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save (java.lang.String، int)) وقم بتعيين Text باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Slides لنظام Android عبر Java](https://texts.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) و [Aspose.Words for Andorid via Java](https://texts.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في التطبيقات.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPS file
Presentation presentation = new Presentation("input.pps");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Textument
Textument textument = new Textument("htmlOutput.html");
// save textument in TEXT format
textument.save("output.text",SaveFormat.Text);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-word/" name="PPS إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-dotm/" name="PPS إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-text/" name="PPS إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-rtf/" name="PPS إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-flatopc/" name="PPS إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-textm/" name="PPS إلى TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-wordml/" name="PPS إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-textx/" name="PPS إلى TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-dotx/" name="PPS إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-ott/" name="PPS إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-dot/" name="PPS إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/pps-to-odt/" name="PPS إلى ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}