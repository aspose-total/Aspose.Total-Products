---
title: تحويل SXC إلى WORD باستخدام C++ أو مع محول مجاني على الإنترنت
description: تحويل SXC إلى WORD داخل تطبيقات C++ أو عبر الإنترنت. اختبر محول CSV إلى DOC على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: DOC
otherformats: DOC POWERPOINT PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل SXC إلى WORD عبر C++ أو عبر الإنترنت" h2="تصدير Excel <sup>&reg;</sup> ؛ SXC إلى WORD ضمن تطبيقات C++ كاملة الوظائف" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SXC إلى WORD التحويل على C++" %}}
1. افتح ملف SXC باستخدام وظيفة عضو [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) في [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) مرجع الفئة
2. تحويل SXC إلى PDF وتعيين SaveFormat إلى Pdf
3. قم بتحميل ملف PDF المحول باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument) مرجع فئة
4. احفظ المستند بتنسيق WORD باستخدام وظيفة العضو [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) وقم بتعيين Word على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>محول عبر الإنترنت لـ SXC إلى WORD</h3>

<iframe title="docx to sxc" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=docx&from=sxc" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/sxc-to-docx/">جرب تطبيقنا المجاني لتحويل SXC إلى WORD</a></p>
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
                          <span itemprop="name"><b>كيف يمكنني تحويل SXC إلى WORD Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل SXC أعلاه. لبدء عملية تحويل SXC إلى WORD ، ما عليك سوى إضافة ملف SXC الخاص بك عن طريق سحبه وإفلاته في المنطقة المخصصة أو بالنقر داخل المربع الأبيض لاستيراد الملف. بمجرد استيراد الملف ، انقر فوق الزر "تحويل" لبدء عملية التحويل. بعد اكتمال تحويل SXC إلى WORD ، يمكنك على الفور تنزيل ملف WORD المحول حديثًا بنقرة واحدة فقط.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل SXC؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تعتمد سرعة هذا المحول عبر الإنترنت بشكل كبير على حجم ملف SXC. يمكن تحويل ملفات SXC الأصغر إلى WORD في بضع ثوانٍ فقط. بالإضافة إلى ذلك ، ستختلف كفاءة عملية التحويل اعتمادًا على كيفية تحسين التطبيق الخاص بك إذا قمت بدمج كود التحويل في تطبيق C ++.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل SXC إلى WORD باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بعد اكتمال تحويل SXC إلى WORD ، ستتمكن من تنزيل الملف المحول على الفور من خلال رابط التنزيل المقدم. نحذف الملفات التي تم تحميلها بعد 24 ساعة ، ولن تعمل روابط التنزيل بعد هذه الفترة الزمنية. يمكنك التأكد من أن تحويل الملفات ، بما في ذلك SXC ، آمن تمامًا وآمن ، حيث لا يمكن لأي شخص الوصول إلى ملفاتك. تم دمج التطبيق المجاني أعلاه لأغراض الاختبار ، مما يتيح لك التحقق من النتائج قبل دمج الكود.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل SXC؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك الوصول إلى هذا المحول عبر الإنترنت باستخدام أي متصفح ويب حديث مثل Google Chrome أو Firefox أو Opera أو Safari. ومع ذلك ، إذا كنت تعمل على تطبيق سطح مكتب ، فإن Aspose.Total SXC Conversion API توفر حلاً سلسًا.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}