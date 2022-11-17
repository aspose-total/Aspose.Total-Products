---
title: واجهة برمجة تطبيقات Android لتقديم TEX إلى PS
description: قم بتحويل TEX إلى PS عبر Android عبر Java API

family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PS
otherformats: MHTML DOT XAMLFLOW MARKDOWN DOCM PCL ODT DOTM FLATOPC DOTX OTT WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم TEX إلى PS على Android عبر Java" h2="قم بتحويل TEX إلى PS في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل TEX إلى PS في تطبيقات الهاتف المحمول الخاصة بك باستخدام اثنين من واجهات برمجة التطبيقات من حزمة [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). تحتاج أولاً إلى تحويل ملف TEX إلى DOC باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). ثانيًا ، باستخدام واجهة برمجة تطبيقات معالجة الكلمات [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) ، يمكنك عرض DOC إلى PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل TEX إلى PS على Android عبر Java" %}}
1. افتح ملف TEX باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل TEX إلى DOC باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق PS باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، int)) وقم بتعيين PS باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) و تثبيت [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX file with an instance of Document class
Document document = new Document("template.tex");
// save TEX as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.PS
outputDocument.save("output.ps", SaveFormat.PS);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على معلومات ملف TEX على Android عبر Java" %}}
قبل تحويل TEX إلى PS ، قد تحتاج إلى معلومات حول المستند بما في ذلك المؤلف وتاريخ الإنشاء والكلمات الرئيسية وتعديل التاريخ والموضوع والعنوان. هذه المعلومات مفيدة لاتخاذ القرار لعملية التحويل. باستخدام [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API ، يمكنك الحصول على كل ذلك. للحصول على معلومات خاصة بالملف حول ملف TEX ، احصل أولاً على كائن [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) باستخدام [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) طريقة. بمجرد استرداد كائن DocumentInfo ، يمكنك الحصول على قيم الخصائص الفردية.
{{% blocks/products/pf/feature-page-code %}}

```java
// load TEX document
Document doc = new Document("template.tex");
// get document information
DocumentInfo docInfo = doc.getInfo();
// show document information
System.out.println("Author: " + docInfo.getAuthor());
System.out.println("Creation Date: " + docInfo.getCreationDate());
System.out.println("Keywords: " + docInfo.getKeywords());
System.out.println("Modify Date: " + docInfo.getModDate());
System.out.println("Subject: " + docInfo.getSubject());
System.out.println("Title: " + docInfo.getTitle());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أدخل التعليقات الختامية في مستند PS في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يمكنك أيضًا إضافة مجموعة من الميزات الأخرى داخل تطبيقات Android باستخدام واجهة برمجة تطبيقات [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). إحدى هذه الميزات هي إدراج التعليقات الختامية والترقيم في مستند PS. إذا كنت ترغب في إدراج حاشية سفلية أو تعليق ختامي في مستند PS ، فيرجى استخدام طريقة DocumentBuilder.InsertFootnote. تقوم هذه الطريقة بإدراج حاشية سفلية أو تعليق ختامي في المستند. تمثل فئات EndnoteOptions و FootnoteOptions خيارات الترقيم للحاشية السفلية والتعليق الختامي.
{{% blocks/products/pf/feature-page-code %}}

```java
// load document
Document doc = new Document("input.DOC");
// initialize document builder
DocumentBuilder builder = new DocumentBuilder(doc);
// add text in it
builder.write("Some text");
// insert footnote
builder.insertFootnote(FootnoteType.ENDNOTE, "Endnote text.");
// initialize endnote options
EndnoteOptions option = doc.getEndnoteOptions();
// set restart rule
option.setRestartRule(FootnoteNumberingRule.RESTART_PAGE);
// set position
option.setPosition(EndnotePosition.END_OF_SECTION);
// save the document to disk.
doc.save("output.ps", SaveFormat.PS);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-mhtml/" name="TEX إلى MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-dot/" name="TEX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-xamlflow/" name="TEX إلى XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-markdown/" name="TEX إلى MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-ps/" name="TEX إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-pcl/" name="TEX إلى PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-odt/" name="TEX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-dotm/" name="TEX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-flatopc/" name="TEX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-dotx/" name="TEX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-ott/" name="TEX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/android-java/conversion/tex-to-wordml/" name="TEX إلى WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}