---
title: واجهة برمجة تطبيقات Android لتقديم SVG إلى FLATOPC
description: قم بتحويل SVG إلى FLATOPC عبر Android عبر Java API

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: FLAT_OPC
otherformats: XAMLFLOW DOT PS RTF PCL OTT MHTML WORDML DOTM MARKDOWN ODT DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تقديم SVG إلى FLATOPC على Android عبر Java" h2="قم بتحويل SVG إلى FLATOPC في تطبيقات الأجهزة المحمولة دون تثبيت أي برنامج" >}}

{{% blocks/products/pf/feature-page-summary %}}
يمكنك دمج ميزة تحويل SVG إلى FLATOPC في تطبيقات الهاتف المحمول الخاصة بك باستخدام اثنين من واجهات برمجة التطبيقات من حزمة [Aspose.Total for Android Java](https://products.aspose.com/total/android-java/). تحتاج أولاً إلى تحويل ملف SVG إلى DOC باستخدام [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/). ثانيًا ، باستخدام واجهة برمجة تطبيقات معالجة الكلمات [Aspose.Words for Android Java](https://products.aspose.com/words/android-java/) ، يمكنك عرض DOC إلى FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل SVG إلى FLATOPC على Android عبر Java" %}}
1. افتح ملف SVG باستخدام فئة [المستند](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل SVG إلى DOC باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة
3. قم بتحميل ملف DOC باستخدام فئة [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) من Aspose.Words
4. احفظ المستند بتنسيق FLATOPC باستخدام طريقة [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save (java.lang.String، int)) وقم بتعيين FLATOPC باسم SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يمكنك بسهولة استخدام Aspose.Total for Android via Java مباشرةً من [Maven](https://releases.aspose.com/total/java/) و تثبيت [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/installation/) و [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-via-java/#install-asposewords-for-android-via-java-from-maven-repository) في تطبيقاتك.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG file with an instance of Document class
Document document = new Document("template.svg");
// save SVG as a DOC 
document.save("DocOutput.doc", SaveFormat.DOC); 
// load DOC with an instance of Document
Document outputDocument = new com.aspose.words.Document("DocOutput.doc");
// call save method while passing SaveFormat.FLAT_OPC
outputDocument.save("output.flat_opc", SaveFormat.FLAT_OPC);   
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="احصل على معلومات ملف SVG على Android عبر Java" %}}
قبل تحويل SVG إلى FLATOPC ، قد تحتاج إلى معلومات حول المستند بما في ذلك المؤلف وتاريخ الإنشاء والكلمات الرئيسية وتعديل التاريخ والموضوع والعنوان. هذه المعلومات مفيدة لاتخاذ القرار لعملية التحويل. باستخدام [Aspose.PDF for Android via Java](https://docs.aspose.com/pdf/androidjava/) API ، يمكنك الحصول على كل ذلك. للحصول على معلومات خاصة بالملف حول ملف SVG ، احصل أولاً على كائن [DocumentInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/DocumentInfo) باستخدام [getInfo](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#getInfo--) طريقة. بمجرد استرداد كائن DocumentInfo ، يمكنك الحصول على قيم الخصائص الفردية.
{{% blocks/products/pf/feature-page-code %}}

```java
// load SVG document
Document doc = new Document("template.svg");
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

{{% blocks/products/pf/feature-page-section  h2="أدخل التعليقات الختامية في مستند FLATOPC في Android عبر Java" %}}
بصرف النظر عن تحويل المستندات ، يمكنك أيضًا إضافة مجموعة من الميزات الأخرى داخل تطبيقات Android باستخدام واجهة برمجة تطبيقات [Aspose.Words for Android via Java](https://products.aspose.com/words/androidjava/). إحدى هذه الميزات هي إدراج التعليقات الختامية والترقيم في مستند FLATOPC. إذا كنت ترغب في إدراج حاشية سفلية أو تعليق ختامي في مستند FLATOPC ، فيرجى استخدام طريقة DocumentBuilder.InsertFootnote. تقوم هذه الطريقة بإدراج حاشية سفلية أو تعليق ختامي في المستند. تمثل فئات EndnoteOptions و FootnoteOptions خيارات الترقيم للحاشية السفلية والتعليق الختامي.
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
doc.save("output.flat_opc", SaveFormat.FLAT_OPC);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}