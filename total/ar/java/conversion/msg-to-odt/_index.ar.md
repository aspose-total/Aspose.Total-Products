---
title: قم بتصدير MSG إلى ODT عبر Java
description: Java API لتحويل البريد الإلكتروني إلى ODT دون استخدام Microsoft Word أو Outlook
url: /ar/java/conversion/msg-to-odt/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: ODT
otherformats: TEXT OTT WORDML RTF ODT FLATOPC DOT PS XPS JPEG DOC PCL DOCX GIF MD SVG EPUB DOCM PDF DOTM DOTX PNG TIFF EMF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتقديم البريد الإلكتروني إلى ODT" h2="قم بتصدير MSG إلى ODT باستخدام Java API في مكان العمل دون استخدام أي تبعيات لطرف ثالث" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعد تحويل البريد الإلكتروني ميزة قوية يمكن لمطوري Java دمجها في أي تطبيقات Java J2SE و J2EE و J2ME عبر [Aspose.Total for Java](https://products.aspose.com/total/java/). باستخدام اثنين من واجهات برمجة التطبيقات داخل الحزمة ، يمكنك تحويل البريد الإلكتروني MSG إلى ODT دون أي تبعيات لطرف ثالث. أولاً ، يمكنك استخدام واجهة برمجة تطبيقات معالجة البريد الإلكتروني [Aspose.Msg لجافا](https://products.aspose.com/msg/java/) لتحويل تنسيق ملف MSG إلى HTML. ثانيًا ، يمكنك عرض HTML إلى ODT باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل البريد الإلكتروني إلى ODT" %}}
1. افتح ملف MSG باستخدام فئة [MailMessage](https://apireference.aspose.com/msg/java/com.aspose.msg/mailmessage)
2. تحويل MSG إلى HTML باستخدام [save](https://apireference.aspose.com/msg/java/com.aspose.msg/MailMessage#save (java.io.OutputStream،٪ 20com.aspose.msg.SaveOptions)) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق ODT باستخدام [save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، com.aspose.words.SaveOptions)) وضبط ODT على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.ODT
document.save("output.odt", SaveFormat.ODT);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-png/" name="MSG ل PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-doc/" name="MSG ل DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-ott/" name="MSG ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-odt/" name="MSG ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-wordml/" name="MSG ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dotx/" name="MSG ل DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-svg/" name="MSG ل SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-docx/" name="MSG ل DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-epub/" name="MSG ل EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-text/" name="MSG ل TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-xps/" name="MSG ل XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-ps/" name="MSG ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-flatopc/" name="MSG ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-docm/" name="MSG ل DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-jpeg/" name="MSG ل JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-tiff/" name="MSG ل TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dot/" name="MSG ل DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-emf/" name="MSG ل EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-rtf/" name="MSG ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-gif/" name="MSG ل GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-pcl/" name="MSG ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-dotm/" name="MSG ل DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-md/" name="MSG ل MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/msg-to-pdf/" name="MSG ل PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}