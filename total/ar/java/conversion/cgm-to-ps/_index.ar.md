---
title: Java API لتصدير CGM إلى PS
description: قم بتحويل CGM إلى PS باستخدام Java API في مكان العمل
url_ignore: /ar/java/conversion/cgm-to-ps/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PS
otherformats: MHTML MARKDOWN ODT DOT WORDML OTT RTF PS FLATOPC DOTM DOTX PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="تحويل CGM إلى PS عبر Java" h2="في Premise Java API لتقديم CGM إلى PS دون استخدام أي تطبيق تابع لجهة خارجية" >}}
{{% blocks/products/pf/feature-page-summary %}}
يمكنك تحويل CGM إلى PS باستخدام خطوتين بسيطتين. تحتاج أولاً إلى تقديم ملف CGM إلى DOC باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java/). بعد ذلك ، باستخدام واجهة برمجة تطبيقات معالجة المستندات القوية [Aspose.Words for Java](https://products.aspose.com/words/java/) ، يمكنك تحويل DOC إلى PS. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API لتحويل CGM إلى PS" %}}
1. افتح ملف CGM باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل CGM إلى DOC باستخدام [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق PS باستخدام طريقة [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String.int)) وقم بتعيين PS باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتشمل [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) و [Aspose.Words for Java](https://docs.aspose.com/words/java/installation/) في ملف pom.xml الخاص بك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="متطلبات التحويل" %}}
أثناء تحويل CGM إلى PS ، حتى إذا كان المستند محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام واجهة برمجة تطبيقات معالجة PDF [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/). لفتح الملف المشفر ، تحتاج إلى إنشاء كائن [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) وفتح CGM باستخدام كلمة مرور المالك.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// open encrypted document
Document document = new Document("input.cgm", "password");
// save CGM as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="افتح مستند CGM المحمي بكلمة مرور عبر Java" %}}
أثناء حفظ مستند الإدخال بتنسيق ملف PS ، يمكنك أيضًا حفظ المستند في قاعدة البيانات بدلاً من نظام الملفات. قد تحتاج إلى تنفيذ تخزين واسترجاع كائنات المستند من قاعدة البيانات وإليها. سيكون هذا ضروريًا إذا كنت تقوم بتنفيذ أي نوع من أنظمة إدارة المحتوى. من أجل حفظ PS في قاعدة البيانات ، غالبًا ما يكون من الضروري إجراء تسلسل للوثيقة للحصول على مصفوفة بايت. يمكن القيام بذلك باستخدام واجهة برمجة تطبيقات [Aspose.Words for Java](https://products.aspose.com/words/Java/). بعد الحصول على مصفوفة البايت الخاصة بك ، يمكنك تخزينها في قاعدة البيانات باستخدام جملة SQL. 
{{% blocks/products/pf/feature-page-code %}}

```java
public static void StoreToDatabase(Document doc, Connection mConnection) throws Exception {
    // create an output stream which uses byte array to save data
    ByteArrayOutputStream aout = new ByteArrayOutputStream();
    // save the document to byte array
    doc.save(aout, SaveFormat.PS);
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
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="الحالات الرئيسية للاستخدام" %}}
- **طباعة الرسوم البيانية الناعمة عالية الجودة** – إنتاج رسوم بيانية فنية دقيقة وقابلة للتوسيع للتصنيع والهندسة والوثائق المعمارية.
- **أرشفة الرسوم التوضيحية التقنية في أنظمة PostScript** – تخزين الأصول الناعمة بتنسيق محسن للوصول على المدى الطويل وتوافق الطباعة.
- **إعداد الرسوم التوضيحية CGM للطباعة** – ضمان التكامل السلس في تخطيط الصفحات المهني وسير العمل في الطباعة.
- **إنتاج الوثائق الفعلية** – إنشاء ملفات جاهزة للطباعة للدلائل والكتالوجات والرسوم البيانية التقنية بتنسيق كبير.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="سيناريوهات التشغيل التلقائي" %}}
- **مولدات تدفق الطباعة القائمة على Java** – تحويل ملفات CGM برمجيًا إلى إخراج PS عالي الدقة لسير العمل في الشركات.
- **محولات دفعية من الناعمة إلى PostScript** – أتمتة عمليات التحويل بمقياس كبير للتعامل بكفاءة مع أرشيفات الرسوم البيانية الشاملة.
- **تكامل خط الإنتاج النشري** – تضمين تحويل CGM إلى PS في عمليات عرض المستندات التلقائية وأنظمة النشر المهنية لنتائج عالية الجودة ومتسقة.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}