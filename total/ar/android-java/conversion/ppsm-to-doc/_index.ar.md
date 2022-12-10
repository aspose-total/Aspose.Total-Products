---
title: تصدير PPSM إلى DOC على Andorid عبر Java
description: قم بتحويل PPSM إلى DOC في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOC
otherformats: DOTX WORD ODT DOTM WORDML TEXT DOCX DOCM RTF DOT OTT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم PPSM إلى DOC على Andorid عبر Java" h2="تنسيق ملف APIs لتحويل PPSM إلى DOC داخل تطبيقات Android دون الاعتماد على Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
يسمح [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) بمعالجة تنسيقات الملفات داخل تطبيقات Android. باستخدام واجهات برمجة التطبيقات المتوفرة في الحزمة ، يمكنك أتمتة عملية تحويل PowerPoint PPSM إلى Word DOC في تطبيقاتك.
يمكنك تحويل المستند الخاص بك في خطوتين. يمكنك استخدام [Aspose.Slides for Andorid via Java](https://products.aspose.com/slides/android-java/) وهي واجهة برمجة تطبيقات PowerPoint لتطبيقات Android لتقديم PPSM إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/) يمكنك تحويل HTML إلى DOC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تقديم PPSM إلى DOC في Android" %}}
1. افتح ملف PPSM باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. تحويل PPSM إلى HTML باستخدام [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق DOC باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، int)) وقم بتعيين Doc باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Slides لنظام Android عبر Java](https://docs.aspose.com/slides/androidjava/install-aspose-slides-for-android-via-java/) و [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في التطبيقات.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// instantiate a Presentation object that represents a PPSM file
Presentation presentation = new Presentation("input.ppsm");
// save the presentation as HTML
presentation.save("htmlOutput.html", SaveFormat.Html);
// load HTML with an instance of Document
Document document = new Document("htmlOutput.html");
// save document in DOC format
document.save("output.doc",SaveFormat.Doc);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-dotx/" name="PPSM إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-word/" name="PPSM إلى WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-odt/" name="PPSM إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-dotm/" name="PPSM إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-wordml/" name="PPSM إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-text/" name="PPSM إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-docx/" name="PPSM إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-docm/" name="PPSM إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-rtf/" name="PPSM إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-dot/" name="PPSM إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-ott/" name="PPSM إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/ppsm-to-flatopc/" name="PPSM إلى FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}