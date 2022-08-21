---
title: تقديم البريد الإلكتروني إلى OTT في تطبيق Andorid
description: قم بتصدير EMLX إلى OTT دون استخدام Microsoft Word أو Outlook في تطبيقات Andorid الخاصة بك
url: /ar/android-java/conversion/emlx-to-ott/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: OTT
otherformats: GIF MD EPUB BMP FLATOPC DOC EMF PNG SVG TEXT DOTX DOCX TIFF ODT WORDML JPEG PCL XPS PS DOCM PDF DOT RTF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل البريد الإلكتروني إلى OTT في تطبيقات Andorid" h2="تصميم تطبيقات Andorid لتصدير EMLX إلى OTT باستخدام Andorid عبر Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
تطبيقات Andorid سهلة الاستخدام للمستخدمين النهائيين على أسس يومية. يوما بعد يوم تتزايد أعداد مستخدمي هواتف Andorid. باستخدام [Aspose.Total for Android عبر Java](https://products.aspose.com/total/android-java/) مكتبات أتمتة تنسيق الملفات يمكنك تطوير تطبيقات معالجة البريد الإلكتروني وتحويله. يمكنك تحويل EMLX إلى OTT عن طريق الجمع بين [Aspose.Emlx لنظام Android Java](https://products.aspose.com/emlx/android-java/) و [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). باستخدام واجهة برمجة التطبيقات الأولى ، يمكنك تحويل تنسيق ملف EMLX إلى HTML وباستخدام واجهة برمجة التطبيقات الثانية ، يمكنك تقديم HTML كـ OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل EMLX إلى OTT في Andorid" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. تحويل EMLX إلى HTML باستخدام [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save (java.io.OutputStream،٪ 20com.aspose.emlx.SaveOptions )) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق OTT باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String،com.aspose.words.SaveOptions)) وضبط OTT على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.Emlx لنظام Android عبر Java](https://docs.aspose.com/emlx/androidjava/installation/) و [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.OTT
document.save("output.ott", SaveFormat.OTT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-gif/" name="EMLX إلى GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-md/" name="EMLX إلى MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-epub/" name="EMLX إلى EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-ott/" name="EMLX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-flatopc/" name="EMLX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-doc/" name="EMLX إلى DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-emf/" name="EMLX إلى EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-png/" name="EMLX إلى PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-svg/" name="EMLX إلى SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-text/" name="EMLX إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-dotx/" name="EMLX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-docx/" name="EMLX إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-tiff/" name="EMLX إلى TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-odt/" name="EMLX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-wordml/" name="EMLX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-jpeg/" name="EMLX إلى JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-pcl/" name="EMLX إلى PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-xps/" name="EMLX إلى XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-ps/" name="EMLX إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-docm/" name="EMLX إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-pdf/" name="EMLX إلى PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-dot/" name="EMLX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-rtf/" name="EMLX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/emlx-to-dotm/" name="EMLX إلى DOTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}