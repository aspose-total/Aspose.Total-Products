---
title: قم بتصدير MSG إلى PNG عبر Java
description: Java API لتحويل البريد الإلكتروني إلى PNG دون استخدام Microsoft Word أو Outlook
url_ignore: /ar/java/conversion/msg-to-png/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOTX TIFF PNG OTT DOTM PS DOC EPUB WORDML SVG PDF DOCM MD XPS RTF DOT FLATOPC PCL JPEG ODT DOCX EMF GIF TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتقديم البريد الإلكتروني إلى PNG" h2="قم بتصدير MSG إلى PNG باستخدام Java API في مكان العمل دون استخدام أي تبعيات لطرف ثالث" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعد تحويل البريد الإلكتروني ميزة قوية يمكن لمطوري Java دمجها في أي تطبيقات Java J2SE و J2EE و J2ME عبر [Aspose.Total for Java](https://products.aspose.com/total/java/). باستخدام اثنين من واجهات برمجة التطبيقات داخل الحزمة ، يمكنك تحويل البريد الإلكتروني MSG إلى PNG دون أي تبعيات لطرف ثالث. أولاً ، يمكنك استخدام واجهة برمجة تطبيقات معالجة البريد الإلكتروني [Aspose.Email لجافا](https://products.aspose.com/email/java/) لتحويل تنسيق ملف MSG إلى HTML. ثانيًا ، يمكنك عرض HTML إلى PNG باستخدام واجهة برمجة تطبيقات معالجة المستندات [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل البريد الإلكتروني إلى PNG" %}}
1. افتح ملف MSG باستخدام فئة [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. تحويل MSG إلى HTML باستخدام [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save (java.io.OutputStream،٪20com.aspose.msg.SaveOptions)) طريقة
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. احفظ المستند بتنسيق PNG باستخدام [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، com.aspose.words.SaveOptions)) وضبط PNG على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
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

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}