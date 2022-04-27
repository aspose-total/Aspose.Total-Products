---
title: Java API لتصدير MHTML إلى DOTM
description: قم بتحويل MHTML إلى DOTM باستخدام Java API في مكان العمل
url: /ar/java/conversion/mhtml-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: DOTM
otherformats: DOTM OTT PCL ODT RTF FLATOPC XAMLFLOW MARKDOWN DOTX DOT WORDML PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل MHTML إلى DOTM عبر Java" h2="في Premise Java API لتقديم MHTML إلى DOTM دون استخدام أي تطبيق تابع لجهة خارجية" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل MHTML إلى DOTM باستخدام خطوتين بسيطتين. تحتاج أولاً إلى تقديم ملف MHTML إلى DOC باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تحويل DOC إلى DOTM. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل MHTML إلى DOTM" %}}
1. افتح ملف MHTML باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل MHTML إلى DOC باستخدام [Save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق DOTM باستخدام طريقة [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.int)) وقم بتعيين DOTM باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load MHTML file with an instance of Document class
Document document = new Document("template.mhtml");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.DOTM
outputDocument.save("output.dotm", SaveFormat.DOTM);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحويل MHTML إلى DOTM ، حتى إذا كان المستند محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام واجهة برمجة تطبيقات معالجة PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). لفتح الملف المشفر ، تحتاج إلى إنشاء كائن [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) وفتح MHTML باستخدام كلمة مرور المالك.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.mhtml", "password");
// save MHTML as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح مستند MHTML المحمي بكلمة مرور عبر Java" %}}
أثناء حفظ مستند الإدخال بتنسيق ملف DOTM ، يمكنك أيضًا حفظ المستند في قاعدة البيانات بدلاً من نظام الملفات. قد تحتاج إلى تنفيذ تخزين واسترجاع كائنات المستند من قاعدة البيانات وإليها. سيكون هذا ضروريًا إذا كنت تقوم بتنفيذ أي نوع من أنظمة إدارة المحتوى. من أجل حفظ DOTM في قاعدة البيانات ، غالبًا ما يكون من الضروري إجراء تسلسل للوثيقة للحصول على مصفوفة بايت. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for Java](https://products.aspose.com/words/Java/). بعد الحصول على مصفوفة البايت الخاصة بك ، يمكنك تخزينها في قاعدة البيانات باستخدام جملة SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.DOTM);
    // get the byte array from output steam
    // the byte array now contains the document
    byte[] buffer = aout.toByteArray();
    // get the filename from the document.
    String fileName = doc.getOriginalFileName();
    String filePath = fileName.replace("\\", "\\\\");
    // create the SQL command.
    String commandString = "INSERT INTO Documents (FileName, FileContent) VALUES('" + filePath + "', '" + buffer + "')";
    Statement statement = mConnection.createStatement();
    statement.executeUpdate(commandString);
}  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="خيارات التحويل الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-rtf/" name="MHTML ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-wordml/" name="MHTML ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-odt/" name="MHTML ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-flatopc/" name="MHTML ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-ps/" name="MHTML ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-pcl/" name="MHTML ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-mhtml/" name="MHTML ل MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-dotm/" name="MHTML ل DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-ott/" name="MHTML ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-dotx/" name="MHTML ل DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-xamlflow/" name="MHTML ل XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/mhtml-to-markdown/" name="MHTML ل MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}