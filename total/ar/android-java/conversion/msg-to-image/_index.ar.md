---
title: تقديم البريد الإلكتروني إلى IMAGE في تطبيق Andorid
description: قم بتصدير MSG إلى IMAGE دون استخدام Microsoft Word أو Outlook في تطبيقات Andorid الخاصة بك

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: IMAGE
otherformats: PDF EPUB OTT RTF DOC EMF SVG DOCM TIFF DOCX DOTM ODT MD GIF PNG DOT XPS DOTX FLATOPC JPEG BMP WORDML PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل البريد الإلكتروني إلى IMAGE في تطبيقات Andorid" h2="تصميم تطبيقات Andorid لتصدير MSG إلى IMAGE باستخدام Andorid عبر Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
تطبيقات Andorid سهلة الاستخدام للمستخدمين النهائيين على أسس يومية. يوما بعد يوم تتزايد أعداد مستخدمي هواتف Andorid. باستخدام [Aspose.Total for Android عبر Java](https://products.aspose.com/total/android-java/) مكتبات أتمتة تنسيق الملفات يمكنك تطوير تطبيقات معالجة البريد الإلكتروني وتحويله. يمكنك تحويل MSG إلى IMAGE عن طريق الجمع بين [Aspose.Msg لنظام Android Java](https://products.aspose.com/msg/android-java/) و [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). باستخدام واجهة برمجة التطبيقات الأولى ، يمكنك تحويل تنسيق ملف MSG إلى HTML وباستخدام واجهة برمجة التطبيقات الثانية ، يمكنك تقديم HTML كـ IMAGE. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل MSG إلى IMAGE في Andorid" %}}
1. افتح ملف MSG باستخدام فئة [MailMessage](https://reference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. تحويل MSG إلى HTML باستخدام [save](https://reference.aspose.com/msg/java/com.aspose.msg/MailMessage#save (java.io.OutputStream،٪ 20com.aspose.msg.SaveOptions )) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق IMAGE باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String،com.aspose.words.SaveOptions)) وضبط IMAGE على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت [Aspose.Msg لنظام Android عبر Java](https://docs.aspose.com/msg/androidjava/installation/) و [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PNG
document.save("output.png", SaveFormat.PNG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}