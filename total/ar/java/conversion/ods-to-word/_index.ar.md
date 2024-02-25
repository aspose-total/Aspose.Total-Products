---
title: تحويل ODS إلى WORD باستخدام Java أو مع محول مجاني على الإنترنت
description: Java API لتصدير ODS إلى WORD أو عبر الإنترنت باستخدام Excel أو Word أو عبر الإنترنت. اختبر محول CSV إلى DOC على الإنترنت مجانًا بسرعة قبل دمج الكود.
url_ignore: /ar/java/conversion/ods-to-word/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: WORD
otherformats: WORDX WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API لتصدير ODS إلى WORD أو عبر الإنترنت" h2="في Premise Java API لتصدير ODS إلى WORD أو عبر الإنترنت دون الاعتماد على Microsoft Excel & reg ؛" >}}
{{% blocks/products/pf/feature-page-summary %}}
يعتبر تحويل ODS إلى WORD عملية من خطوتين. ستستخدم أولاً واجهة برمجة تطبيقات [Aspose.Cells for Java](https://products.aspose.com/cells/java) لتحويل مستند ODS المحدد إلى PDF ، ثم باستخدام [Aspose.PDF for Java](https://products.aspose.com/pdf/java) API ، يمكنك بسهولة تحويل مستند PDF إلى WORD. تأتي كلتا واجهات برمجة التطبيقات ضمن مجموعة مكتبات أتمتة تنسيق الملفات [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="كيفية تحويل ODS إلى WORD عبر Java API" %}}
1. افتح ملف ODS باستخدام فئة [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
2. تحويل ODS إلى PDF وتعيين SaveFormat على AUTO
3. قم بتحميل ملف PDF المحول باستخدام فئة [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
4. احفظ المستند بتنسيق WORD باستخدام [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) طريقة وتعيين Word كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
يجب عليك استخدام Aspose.Total for Java مباشرة من مشروع قائم على [Maven](https://releases.aspose.com/total/java/) وتضمين مكتبات في ملفك pom.xml.

بدلاً من ذلك ، يمكنك الحصول على ملف ZIP من [التنزيلات](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>محول عبر الإنترنت لـ ODS إلى WORD</h3>

<iframe title="docx to ods" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=ods" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/ods-to-docx/">جرب تطبيقنا المجاني لتحويل ODS إلى WORD</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>أسئلة مكررة</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كيف يمكنني تحويل ODS إلى WORD Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل ODS أعلاه. تتضمن عملية التحويل إضافة ملف ODS إما عن طريق سحبه وإفلاته في المنطقة البيضاء أو النقر داخل المنطقة لاستيراد الملف. بمجرد إضافة الملف ، ما عليك سوى النقر فوق الزر "تحويل" لبدء عملية التحويل. بمجرد الانتهاء ، يمكنك تنزيل ملف WORD المحول حديثًا بنقرة واحدة فقط.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل ODS؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يتم تحديد سرعة هذا المحول عبر الإنترنت إلى حد كبير من خلال حجم ملف ODS الذي يتم تحويله. يمكن تحويل ملفات ODS الأصغر إلى WORD في غضون ثوانٍ قليلة. بالإضافة إلى ذلك ، إذا قمت بدمج كود التحويل في تطبيق Java ، فإن كفاءة التطبيق ستؤثر أيضًا على عملية التحويل.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل ODS إلى WORD باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بعد اكتمال عملية التحويل ، سيتم توفير رابط تنزيل ملف WORD على الفور. يتم حذف الملفات التي تم تحميلها تلقائيًا بعد 24 ساعة ، ولن تكون روابط التنزيل نشطة بعد ذلك الإطار الزمني. يمكنك التأكد من أن ملفاتك آمنة وأن تحويل الملفات ، بما في ذلك ODS ، آمن تمامًا. تم دمج التطبيق المجاني بشكل أساسي لأغراض الاختبار ، مما يتيح لك التحقق من النتائج قبل دمج الكود في مشروعك.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل ODS؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">للتحويل عبر الإنترنت ، يمكنك استخدام أي متصفح ويب حديث مثل Google Chrome أو Firefox أو Opera أو Safari. ومع ذلك ، إذا كنت تقوم بتطوير تطبيق سطح مكتب ، فإن Aspose.Total ODS Conversion API هو خيار ممتاز لأنه مصمم للعمل بسلاسة في مثل هذه البيئات.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}