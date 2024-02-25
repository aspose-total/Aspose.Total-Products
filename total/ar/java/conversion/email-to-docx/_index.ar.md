---
title: قم بتصدير EMAIL إلى DOCX عبر Java
description: Java API لتحويل البريد الإلكتروني إلى DOCX دون استخدام Microsoft Word أو Outlook
url_ignore: /ar/java/conversion/email-to-docx/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: PCL OTT RTF PDF WORDML TIFF DOCX MD EMF JPEG DOTX DOT FLATOPC XPS GIF DOC EPUB TEXT DOTM SVG PNG PS DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتقديم البريد الإلكتروني إلى DOCX" h2="قم بتصدير EMAIL إلى DOCX باستخدام Java API في مكان العمل دون استخدام أي تبعيات لطرف ثالث" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعد تحويل البريد الإلكتروني ميزة قوية يمكن لمطوري Java دمجها في أي تطبيقات Java J2SE و J2EE و J2ME عبر [Aspose.Total for Java](https://products.aspose.com/total/java/). باستخدام اثنين من واجهات برمجة التطبيقات داخل الحزمة ، يمكنك تحويل البريد الإلكتروني EMAIL إلى DOCX دون أي تبعيات لطرف ثالث. أولاً ، يمكنك استخدام واجهة برمجة تطبيقات معالجة البريد الإلكتروني [Aspose.Email لجافا](https://products.aspose.com/email/java/) لتحويل تنسيق ملف EMAIL إلى HTML. ثانيًا ، يمكنك عرض HTML إلى DOCX باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل البريد الإلكتروني إلى DOCX" %}}
1. افتح ملف EMAIL باستخدام فئة [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. تحويل EMAIL إلى HTML باستخدام [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save (java.io.OutputStream،٪20com.aspose.email.SaveOptions)) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق DOCX باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، com.aspose.words.SaveOptions)) وضبط DOCX على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMAIL file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save EMAIL as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.DOCX
document.save("output.docx", SaveFormat.DOCX);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}