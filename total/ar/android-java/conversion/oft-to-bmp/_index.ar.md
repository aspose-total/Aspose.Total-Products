---
title: تقديم البريد الإلكتروني إلى BMP في تطبيق Andorid
description: قم بتصدير OFT إلى BMP دون استخدام Microsoft Word أو Outlook في تطبيقات Andorid الخاصة بك

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: BMP
otherformats: PS DOT OTT SVG GIF JPEG EMF DOC XPS ODT PDF TIFF FLATOPC DOTM PNG PCL MD EPUB TEXT DOCM DOCX DOTX WORDML RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل البريد الإلكتروني إلى BMP في تطبيقات Andorid" h2="تصميم تطبيقات Andorid لتصدير OFT إلى BMP باستخدام Andorid عبر Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
تطبيقات Andorid سهلة الاستخدام للمستخدمين النهائيين على أسس يومية. يوما بعد يوم تتزايد أعداد مستخدمي هواتف Andorid. باستخدام [Aspose.Total for Android عبر Java](https://products.aspose.com/total/android-java/) مكتبات أتمتة تنسيق الملفات يمكنك تطوير تطبيقات معالجة البريد الإلكتروني وتحويله. يمكنك تحويل OFT إلى BMP عن طريق الجمع بين [Aspose.Oft لنظام Android Java](https://products.aspose.com/oft/android-java/) و [Aspose.Words for Andorid Java](https://products.aspose.com/words/android-java/). باستخدام واجهة برمجة التطبيقات الأولى ، يمكنك تحويل تنسيق ملف OFT إلى HTML وباستخدام واجهة برمجة التطبيقات الثانية ، يمكنك تقديم HTML كـ BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل OFT إلى BMP في Andorid" %}}
1. افتح ملف OFT باستخدام فئة [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage)
2. تحويل OFT إلى HTML باستخدام [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save (java.io.OutputStream،٪ 20com.aspose.oft.SaveOptions )) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق BMP باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String،com.aspose.words.SaveOptions)) وضبط BMP على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت [Aspose.Oft لنظام Android عبر Java](https://docs.aspose.com/oft/androidjava/installation/) و [Aspose.Words for Andorid via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}