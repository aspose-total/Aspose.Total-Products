---
title: C++ API لتحويل PPSX إلى ODT أو مع محول مجاني على الإنترنت
description: قم بتصدير PPSX إلى ODT داخل تطبيقات C++ الخاصة بك أو عبر الإنترنت. اختبر محول PPSX إلى ODT على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: PPSX
outformat: ODT
otherformats: TEXT DOCX RTF DOT DOTX DOTM DOCM FLATOPC DOC WORD WORDML OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتقديم PPSX إلى ODT أو التطبيق عبر الإنترنت" h2="تصدير PPSX إلى ODT في تطبيقات C++ بدون أي تبعيات Microsoft PowerPoint أو Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) عبارة عن حزمة كاملة من مكتبات أتمتة تنسيق الملفات C++. باستخدام الميزات الغنية لواجهات برمجة التطبيقات المتوفرة في pacakge ، يمكننا بسهولة تحويل PowerPoint PPSX إلى Word ODT. من أجل إجراء التحويل ، يمكنك أولاً استخدام واجهة برمجة تطبيقات [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لتحويل PPSX إلى HTML. بعد ذلك باستخدام واجهة برمجة تطبيقات معالجة الكلمات الغنية بالميزات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) يمكنك تحويل HTML إلى ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل PPSX إلى ODT" %}}
1. قم بتحميل ملف PPSX باستخدام مرجع فئة [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. عرض PPSX إلى HTML باستخدام funciton لعضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Html كـ SaveFormat
3. قم بتحميل ملف HTML المحول باستخدام مرجع الفئة [المستند](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. احفظ المستند بتنسيق ODT باستخدام [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string) fucntion
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsx");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ PPSX إلى ODT</h3>

<iframe title="odt to ppsx" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=odt&from=ppsx" id="child-iframe" width="80%"></iframe>

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
                          <span itemprop="name"><b>كيف يمكنني تحويل PPSX إلى ODT Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تم دمج التطبيق عبر الإنترنت لتحويل PPSX أعلاه. لتحويل ملف PPSX إلى ODT باستخدام هذه الأداة عبر الإنترنت ، يمكنك إما سحب ملف PPSX وإفلاته في المنطقة المخصصة أو النقر داخل المنطقة البيضاء لتحديد الملف من جهازك. بمجرد تحديد ملف PPSX ، انقر فوق الزر تحويل. بعد اكتمال تحويل PPSX إلى ODT ، يمكنك تنزيل ملف ODT المحول بنقرة واحدة فقط.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل PPSX؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تعتمد سرعة تحويل PPSX إلى ODT باستخدام هذا المحول عبر الإنترنت إلى حد كبير على حجم ملف PPSX. يمكن تحويل ملفات PPSX الأصغر إلى ODT في بضع ثوانٍ فقط. بالإضافة إلى ذلك ، إذا قمت بدمج كود التحويل في تطبيق C++ الخاص بك ، فستعتمد سرعة التحويل على مدى جودة تطبيقك لعملية التحويل.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل PPSX إلى ODT باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بعد عملية التحويل ، سيتوفر رابط تنزيل ملفات ODT على الفور. لضمان خصوصيتك ، يتم حذف الملفات التي تم تحميلها بعد 24 ساعة ، وستتوقف روابط التنزيل عن العمل بعد هذه الفترة. كن مطمئنًا أن تحويل الملفات ، بما في ذلك تحويل PPSX ، آمن وخصوصي تمامًا. تم دمج التطبيق المجاني بشكل أساسي لأغراض الاختبار ، مما يتيح لك التحقق من النتيجة قبل دمج الكود.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل PPSX؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">محول PPSX إلى ODT عبر الإنترنت متوافق مع أي متصفح ويب حديث ، بما في ذلك Google Chrome و Firefox و Opera و Safari وغيرها. ومع ذلك ، إذا كنت تعمل على تطبيق سطح مكتب ، فقد ترغب في التفكير في استخدام Aspose.Total PPSX Conversion API ، المصمم خصيصًا للتكامل السلس مع تطبيقات C++. توفر واجهة برمجة التطبيقات هذه تحويلًا عالي السرعة وميزات متقدمة يمكنها تحسين أداء تطبيقك. بالإضافة إلى ذلك ، فهو يدعم مجموعة واسعة من تنسيقات الملفات ، مما يجعله حلاً متعدد الاستخدامات لجميع احتياجات التحويل الخاصة بك. سواء اخترت استخدام المحول عبر الإنترنت أو واجهة برمجة التطبيقات ، يمكنك أن تطمئن إلى أن ملفاتك آمنة ومأمونة طوال عملية التحويل.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}