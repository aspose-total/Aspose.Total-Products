---
title: تحويل DOTX إلى POTM عبر C++ أو مع محول مجاني على الإنترنت
description: قم بتصدير DOTX إلى POTM في تطبيقات C++ دون استخدام Microsoft Word of PowerPoint أو عبر الإنترنت. اختبر محول DOTX إلى POTM على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: POTM
otherformats: POTX POWERPOINT PPT PPTM PPSM ODP POT PPS PPSX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOTX إلى POTM أو التطبيق عبر الإنترنت" h2="تصدير DOTX إلى POTM داخل تطبيقات C++ دون استخدام Microsoft Word <sup>&reg;</sup> ؛ أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يتكون [Aspose.Total for C++](https://products.aspose.com/total/cpp/) من واجهات برمجة تطبيقات قوية لأتمتة الملفات تسمح بأتمتة تحويل DOTX إلى POTM أثناء استخدام اثنين من واجهات برمجة التطبيقات الخاصة به. قم بتحميل مستند DOTX باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) وقم بتحويله إلى HTML ، ثم قم بتحميل HTML عبر معالجة PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإنشاء عرض تقديمي جديد وحفظه كـ POTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOTX إلى POTM على C++" %}}
1. افتح ملف DOTX باستخدام [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) مرجع فئة
2. تحويل DOTX إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. تهيئة كائن [عرض تقديمي] جديد(https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. إضافة شكل تلقائي في الشريحة الخاصة بك ، وإضافة AddTextFrame فيه
5. قم بتحميل محتوى HTML واكتبه في ملف العرض التقديمي الخاص بك
6. احفظ المستند بتنسيق POTM باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Potm على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ DOTX إلى POTM</h3>

<iframe title="potm to dotx" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=potm&from=dotx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند DOTX المحمي بكلمة مرور عبر C++" %}}
بصرف النظر عن تحويل المستندات ، تسمح واجهة برمجة التطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) بالعديد من ميزات معالجة المستندات لمطوري C++. إذا كان تنسيق ملف Microsoft Word DOTX محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام API. لتحميل المستند المشفر ، يمكنك استخدام مُنشئ خاص زائد التحميل ، والذي يقبل كائن [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). يحتوي هذا الكائن على خاصية كلمة المرور ، والتي تحدد سلسلة كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أضف التعليقات في مستند POTM عبر C++" %}}
أثناء حفظ DOTX كـ POTM ، يمكنك أيضًا استخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإضافة المزيد من الميزات في مستند POTM الخاص بك. على سبيل المثال ، يمكنك إضافة تعليقات في العرض التقديمي الخاص بك. يرتبط تعليق شريحة العرض التقديمي بمؤلف معين. يتضمن فصل العرض التقديمي مجموعة المؤلفين في ICommentAuthorCollection المسؤولة عن إضافة تعليقات الشرائح. لكل مؤلف ، هناك مجموعة من التعليقات في ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
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
                          <span itemprop="name"><b>كيف يمكنني تحويل DOTX إلى POTM Online؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">يمكنك العثور على التطبيق عبر الإنترنت لتحويل DOTX أعلاه. لبدء عملية التحويل ، يمكنك إضافة ملف DOTX إما عن طريق سحبه وإفلاته أو بالنقر داخل المنطقة البيضاء لاستيراد المستند. بمجرد إضافة الملف ، يمكنك ببساطة النقر فوق الزر "تحويل". بعد اكتمال تحويل DOTX إلى POTM ، يمكنك تنزيل ملفك المحول بنقرة واحدة فقط.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>كم من الوقت يستغرق تحويل DOTX؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">تعتمد سرعة هذا المحول عبر الإنترنت بشكل كبير على حجم ملف DOTX الذي يتم تحويله. يمكن تحويل ملفات DOTX الصغيرة إلى POTM في بضع ثوانٍ فقط. إذا كنت تستخدم رمز التحويل داخل تطبيق C++ ، فستعتمد سرعة التحويل على مدى جودة تطبيقك.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>هل من الآمن تحويل DOTX إلى POTM باستخدام محول Aspose.Total المجاني؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">بالطبع! بعد تحويل ملف DOTX الخاص بك إلى POTM باستخدام المحول عبر الإنترنت ، سيكون رابط تنزيل ملف POTM متاحًا على الفور. نحن نأخذ أمان وخصوصية الملفات التي تم تحميلها على محمل الجد ونحذفها بعد 24 ساعة من اكتمال عملية التحويل. كن مطمئنًا ، لن يتمكن أي شخص من الوصول إلى ملفاتك. عملية التحويل لدينا ، بما في ذلك تحويل DOTX ، آمنة تمامًا. نحن نقدم تطبيقًا مجانيًا لأغراض الاختبار بحيث يمكنك التحقق من النتائج قبل دمج الكود.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>ما المتصفح الذي يجب أن أستخدمه لتحويل DOTX؟</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">لتحويل DOTX عبر الإنترنت ، يمكنك استخدام أي متصفح حديث ، مثل Google Chrome أو Firefox أو Opera أو Safari. ومع ذلك ، إذا كنت تقوم بتطوير تطبيق سطح مكتب ، فمن المستحسن Aspose.Total DOTX Conversion API للحصول على أداء سلس.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}