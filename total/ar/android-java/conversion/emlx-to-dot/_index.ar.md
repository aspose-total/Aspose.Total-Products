---
title: تقديم البريد الإلكتروني إلى DOT في تطبيق Andorid
description: قم بتصدير EMLX إلى DOT دون استخدام Microsoft Word أو Outlook في تطبيقات Andorid الخاصة بك

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOT
otherformats: ODT PNG PS TIFF JPEG DOCX EPUB RTF DOC PCL FLATOPC SVG WORDML BMP DOTX EMF XPS DOCM GIF MD OTT DOTM TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل البريد الإلكتروني إلى DOT في تطبيقات Andorid" h2="تصميم تطبيقات Andorid لتصدير EMLX إلى DOT باستخدام Andorid عبر Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
تطبيقات Andorid سهلة الاستخدام للمستخدمين النهائيين على أسس يومية. يوما بعد يوم تتزايد أعداد مستخدمي هواتف Andorid. باستخدام [Aspose.Total for Android عبر Java](https://products.aspose.com/total/android-java/) مكتبات أتمتة تنسيق الملفات يمكنك تطوير تطبيقات معالجة البريد الإلكتروني وتحويله. يمكنك تحويل EMLX إلى DOT عن طريق الجمع بين [Aspose.Emlx لنظام Android Java](https://products.aspose.com/emlx/android-java/) و [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). باستخدام واجهة برمجة التطبيقات الأولى ، يمكنك تحويل تنسيق ملف EMLX إلى HTML وباستخدام واجهة برمجة التطبيقات الثانية ، يمكنك تقديم HTML كـ DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل EMLX إلى DOT في Andorid" %}}
1. افتح ملف EMLX باستخدام فئة [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage)
2. تحويل EMLX إلى HTML باستخدام [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save (java.io.OutputStream،٪ 20com.aspose.emlx.SaveOptions )) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق DOT باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String،com.aspose.words.SaveOptions)) وضبط DOT على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت [Aspose.Emlx لنظام Android عبر Java](https://docs.aspose.com/emlx/androidjava/installation/) و [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOT
document.save("output.dot", SaveFormat.DOT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}