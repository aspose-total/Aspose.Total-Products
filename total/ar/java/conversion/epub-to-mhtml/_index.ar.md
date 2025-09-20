---
title: Java API لتصدير EPUB إلى MHTML
description: قم بتحويل EPUB إلى MHTML باستخدام Java API في مكان العمل
url_ignore: /ar/java/conversion/epub-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: MHTML
otherformats: PS WORDML MARKDOWN PCL ODT RTF FLATOPC OTT XAMLFLOW DOTX MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل EPUB إلى MHTML عبر Java" h2="في Premise Java API لتقديم EPUB إلى MHTML دون استخدام أي تطبيق تابع لجهة خارجية" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل EPUB إلى MHTML باستخدام خطوتين بسيطتين. تحتاج أولاً إلى تقديم ملف EPUB إلى DOC باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تحويل DOC إلى MHTML. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل EPUB إلى MHTML" %}}
1. افتح ملف EPUB باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل EPUB إلى DOC باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق MHTML باستخدام طريقة [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.int)) وقم بتعيين MHTML باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-epub-to-mhtml.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحويل EPUB إلى MHTML ، حتى إذا كان المستند محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام واجهة برمجة تطبيقات معالجة PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). لفتح الملف المشفر ، تحتاج إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) وفتح EPUB باستخدام كلمة مرور المالك.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "653b558bf7959a8c45b266a48527b17d" "convert-password-proteted-epub-file.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح مستند EPUB المحمي بكلمة مرور عبر Java" %}}
أثناء حفظ مستند الإدخال بتنسيق ملف MHTML ، يمكنك أيضًا حفظ المستند في قاعدة البيانات بدلاً من نظام الملفات. قد تحتاج إلى تنفيذ تخزين واسترجاع كائنات المستند من قاعدة البيانات وإليها. سيكون هذا ضروريًا إذا كنت تقوم بتنفيذ أي نوع من أنظمة إدارة المحتوى. من أجل حفظ MHTML في قاعدة البيانات ، غالبًا ما يكون من الضروري إجراء تسلسل للوثيقة للحصول على مصفوفة بايت. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for Java](https://products.aspose.com/words/Java/). بعد الحصول على مصفوفة البايت الخاصة بك ، يمكنك تخزينها في قاعدة البيانات باستخدام جملة SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.MHTML);
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
```
{{< blocks/products/pf/agp/feature-section >}}
تحويل **EPUB إلى MHTML (Web Archive)** مهم لإنشاء **مستندات ويب منفردة** من النشرات الرقمية. تجمع ملفات MHTML بين جميع الموارد - HTML والصور والأنماط - في أرشيف واحد، مما يضمن القابلية للنقل والقراءة دون اتصال وتوافق المتصفح. من خلال تحويل EPUB إلى MHTML، يمكن للناشرين والمعلمين والشركات تقديم الكتب الإلكترونية كمستندات ويب مكتملة الذات محسنة للاستخدام على الإنترنت وخارجه.

{{% blocks/products/pf/agp/feature-section-col title="حالات الاستخدام الرئيسية" %}}
- **قراءة الكتب الإلكترونية دون اتصال** - توفير كتب رقمية كاملة يمكن الوصول إليها بدون اتصال بالإنترنت.
- **أرشفة الويب** - الحفاظ على محتوى الكتب الإلكترونية كأرشيفات متوافقة مع المتصفح في ملف واحد.
- **نشر رقمي للمتصفحات** - مشاركة محتوى EPUB في تنسيق ويب جاهز للفتح.
- **تغليف محتوى تعليمي** - توزيع دروس ومواد دراسية وكتب إلكترونية في ملفات قابلة للنقل.
- **أنظمة العمل الوثائقية للشركات** - تبسيط النشر الداخلي إلى مستندات جاهزة للمتصفح.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التأتير" %}}
- **أنابيب EPUB-to-MHTML** - أتمتة تحويل النشرات الرقمية إلى أرشيفات ويب منفردة.
- **سير العمل التلقائي للكتب الإلكترونية إلى الويب** - تبسيط نشر EPUBs مباشرة في تنسيقات تدعمها المتصفحات.
- **نشر السائل للوصول دون اتصال** - تحويل مكتبات الكتب الإلكترونية بأكملها إلى MHTML للقابلية.
- **نشر متوافق مع المتصفح عبر منصات متعددة** - ضمان قراءة سلسة عبر جميع المتصفحات الرئيسية.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}