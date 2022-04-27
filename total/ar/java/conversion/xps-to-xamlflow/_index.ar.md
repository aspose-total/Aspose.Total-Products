---
title: Java API لتصدير XPS إلى XAMLFLOW
description: قم بتحويل XPS إلى XAMLFLOW باستخدام Java API في مكان العمل
url: /ar/java/conversion/xps-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: XAML_FLOW
otherformats: MHTML RTF PS FLATOPC PCL WORDML OTT DOT DOTM MARKDOWN XAMLFLOW ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل XPS إلى XAMLFLOW عبر Java" h2="في Premise Java API لتقديم XPS إلى XAMLFLOW دون استخدام أي تطبيق تابع لجهة خارجية" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل XPS إلى XAMLFLOW باستخدام خطوتين بسيطتين. تحتاج أولاً إلى تقديم ملف XPS إلى DOC باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تحويل DOC إلى XAMLFLOW. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل XPS إلى XAMLFLOW" %}}
1. افتح ملف XPS باستخدام فئة [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل XPS إلى DOC باستخدام [Save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق XAMLFLOW باستخدام طريقة [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.int)) وقم بتعيين XAMLFLOW باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XPS file with an instance of Document class
Document document = new Document("template.xps");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.XAML_FLOW
outputDocument.save("output.xaml_flow", SaveFormat.XAML_FLOW);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحويل XPS إلى XAMLFLOW ، حتى إذا كان المستند محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام واجهة برمجة تطبيقات معالجة PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). لفتح الملف المشفر ، تحتاج إلى إنشاء كائن [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) وفتح XPS باستخدام كلمة مرور المالك.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.xps", "password");
// save XPS as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح مستند XPS المحمي بكلمة مرور عبر Java" %}}
أثناء حفظ مستند الإدخال بتنسيق ملف XAMLFLOW ، يمكنك أيضًا حفظ المستند في قاعدة البيانات بدلاً من نظام الملفات. قد تحتاج إلى تنفيذ تخزين واسترجاع كائنات المستند من قاعدة البيانات وإليها. سيكون هذا ضروريًا إذا كنت تقوم بتنفيذ أي نوع من أنظمة إدارة المحتوى. من أجل حفظ XAMLFLOW في قاعدة البيانات ، غالبًا ما يكون من الضروري إجراء تسلسل للوثيقة للحصول على مصفوفة بايت. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for Java](https://products.aspose.com/words/Java/). بعد الحصول على مصفوفة البايت الخاصة بك ، يمكنك تخزينها في قاعدة البيانات باستخدام جملة SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.XAML_FLOW);
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-rtf/" name="XPS ل RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-wordml/" name="XPS ل WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-odt/" name="XPS ل ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-flatopc/" name="XPS ل FLAلPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-ps/" name="XPS ل PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-pcl/" name="XPS ل PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-mhtml/" name="XPS ل MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-dotm/" name="XPS ل DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-ott/" name="XPS ل OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-dotx/" name="XPS ل DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-xamlflow/" name="XPS ل XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/net/conversion/xps-to-markdown/" name="XPS ل MARKDOWN" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}