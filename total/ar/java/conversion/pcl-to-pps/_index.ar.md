---
title: تحويل ملفات PCL إلى PPS عبر الإنترنت أو تطوير تطبيق قائم على Java لتحويل ملفات PCL
description: تطبيق مجاني عبر الإنترنت لتحويل ملفات PCL إلى ملفات PPS. كود مكتبة تحويل Java لمستندات PCL. 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: PPS
otherformats: PPTM POT XAML PPSM PPT OTP SWF POTX PPS POWERPOINT POTM PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تطبيق تحويل PCL إلى PPS عبر الإنترنت ورمز Java لتحويل ملفات PCL" h2="تطوير تطبيق قوي لتحويل PCL وتصديره استنادًا إلى Java. تحويل ملفات PCL الفردية أو المتعددة إلى PPS وغيرها من التنسيقات عبر واجهة برمجة تطبيقات أتمتة Java. قم بتحويل ملفات PCL بحرية عبر الإنترنت من خلال التطبيق مع التنزيل الفوري." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="تطبيق مجاني عبر الإنترنت لتحويل PCL إلى PPS" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pps&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل ملفات PCL إلى PPS عبر الإنترنت باستخدام التطبيق" %}}

1. قم بتحميل ملفات PCL للتحويل
1. انتظر بضع ثوانٍ أو أكثر حسب حجم PCL
1. راقب شريط حالة التحميل
1. انقر على زر "تحويل"
1. سيتم تحويل PCL إلى مستند PPS
1. تنزيل الملف المُحوَّل PPS

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="تحويل PCL إلى PPS عبر Java Automation API" %}}


1. افتح ملف PCL باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. تحويل PCL إلى PPTX باستخدام طريقة [Save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. قم بتحميل مستند PPTX باستخدام فئة [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. احفظ المستند بتنسيق PPS باستخدام طريقة [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) واضبط `` Pps` كـ SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="كود جافا لتحويل PCL إلى PPS" offSpacer="" %}}


```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);   
```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

هناك حالات قليلة أخرى لحفظ PCL في PPS باستخدام ميزات أخرى مثل متطلبات التحويل, افتح ملف PCL المشفر عبر Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pps format
presentation.save("output.pps", SaveFormat.Pps);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>تطوير تطبيق تحويل الملفات PCL باستخدام Java</h2>

هل تحتاج إلى تطوير تطبيق برمجي قائم على Java لحفظ وتصدير ملفات PCL إلى مستند PPS بسهولة؟ باستخدام [Aspose.Total for Java](https://products.aspose.com/total/ar/java/)، يمكن لأي مطور Java دمج كود API أعلاه لبرمجة تطبيق التحويل عبر مجموعة متنوعة من التنسيقات بما في ذلك Microsoft Word (DOC، DOCX)، وExcel (XLS، XLSX)، وPowerpoint (PPT، PPTX)، وPDF، وملفات البريد الإلكتروني، والصور (JPG، PNG، BMP، GIF) وغيرها من التنسيقات. مكتبة Java قوية لتحويل المستندات، تدعم العديد من التنسيقات الشائعة بما في ذلك تنسيق PCL. عند تصدير المستندات وتقديمها إلى تنسيقات أخرى، يمكن للمبرمجين استخدام واجهات برمجة التطبيقات الفرعية Aspose.Total for Java بما في ذلك [Aspose.Words for Java](https://products.aspose.com/words/ar/java/) و[Aspose.Cells for Java](https://products.aspose.com/cells/ar/java/) و[Aspose.Slides for Java](https://products.aspose.com/slides/ar/java/) و[Aspose.PDF for Java](https://products.aspose.com/pdf/ar/java/) و[Aspose.Imaging for Java](https://products.aspose.com/imaging/ar/java/) والمزيد.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="مكتبة التحويل PCL لـ Java" %}}

تتوفر خيارات بديلة لدمج Aspose.Total for Java على نظامك. الرجاء اختيار ما يشبه احتياجاتك واتبع التعليمات خطوة بخطوة:<br /><br />

- استخدم Aspose.Total for Java مباشرةً من مشروع قائم على Maven وقم بتضمين واجهة برمجة التطبيقات الفرعية ذات الصلة في pom.xml.
- وبدلاً من ذلك، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="حفظ PCL في PPS متطلبات التطبيق" %}}

يمكن لأي نظام تشغيل قادر على تشغيل بيئة تشغيل Java (JRE) تشغيل Aspose.Total for Java. تتضمن القوائم التالية معظم أنظمة التشغيل المدعومة، ولكن ليس كلها. <br /><br />
- مايكروسوفت ويندوز
- Linux: Ubuntu، OpenSUSE، CentOS وغيرها
- macOS: 10.9 (Mavericks) والإصدارات الأحدث
- الجوال : أندرويد، iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}