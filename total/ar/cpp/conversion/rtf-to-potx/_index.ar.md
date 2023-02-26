---
title: تحويل RTF إلى POTX عبر C++ أو مع محول مجاني على الإنترنت
description: قم بتصدير RTF إلى POTX في تطبيقات C++ دون استخدام Microsoft Word of PowerPoint أو عبر الإنترنت. اختبر محول POT إلى CSV على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: POTX
otherformats: POT POWERPOINT POTM PPT PPS ODP PPTM PPSX PPSM PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل RTF إلى POTX أو عبر الإنترنت" h2="تصدير RTF إلى POTX داخل تطبيقات C++ دون استخدام Microsoft Word <sup>&reg;</sup> ؛ أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يتكون [Aspose.Total for C++](https://products.aspose.com/total/cpp/) من واجهات برمجة تطبيقات قوية لأتمتة الملفات تسمح بأتمتة تحويل RTF إلى POTX أثناء استخدام اثنين من واجهات برمجة التطبيقات الخاصة به. قم بتحميل مستند RTF باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) وقم بتحويله إلى HTML ، ثم قم بتحميل HTML عبر معالجة PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإنشاء عرض تقديمي جديد وحفظه كـ POTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل RTF إلى POTX على C++" %}}
1. افتح ملف RTF باستخدام [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) مرجع فئة
2. تحويل RTF إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions)
3. تهيئة كائن [عرض تقديمي] جديد(https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. إضافة شكل تلقائي في الشريحة الخاصة بك ، وإضافة AddTextFrame فيه
5. قم بتحميل محتوى HTML واكتبه في ملف العرض التقديمي الخاص بك
6. احفظ المستند بتنسيق POTX باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Potx على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load RTF file with an instance of Rtfument
Rtfument rtfument = new Rtfument("template.rtf");
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"sourceFile.rtf");
// save the rtfument in HTML file format
rtf->Save(u"HtmlOutput.HTML");
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ RTF إلى POTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=rtf" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند RTF المحمي بكلمة مرور عبر C++" %}}
بصرف النظر عن تحويل المستندات ، تسمح واجهة برمجة التطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) بالعديد من ميزات معالجة المستندات لمطوري C++. إذا كان تنسيق ملف Microsoft Word RTF محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام API. لتحميل المستند المشفر ، يمكنك استخدام مُنشئ خاص زائد التحميل ، والذي يقبل كائن [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). يحتوي هذا الكائن على خاصية كلمة المرور ، والتي تحدد سلسلة كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected rtfument, the password is passed to the rtfument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"rtfPassword");
// load the rtfument from the local file system by filename:
SharedPtr<Rtfument> rtf = MakeObject<Rtfument>(u"Encrypted.rtf", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أضف التعليقات في مستند POTX عبر C++" %}}
أثناء حفظ RTF كـ POTX ، يمكنك أيضًا استخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإضافة المزيد من الميزات في مستند POTX الخاص بك. على سبيل المثال ، يمكنك إضافة تعليقات في العرض التقديمي الخاص بك. يرتبط تعليق شريحة العرض التقديمي بمؤلف معين. يتضمن فصل العرض التقديمي مجموعة المؤلفين في ICommentAuthorCollection المسؤولة عن إضافة تعليقات الشرائح. لكل مؤلف ، هناك مجموعة من التعليقات في ICommentCollection.
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-pot/" name="RTF إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-powerpoint/" name="RTF إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-potm/" name="RTF إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-ppt/" name="RTF إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-pps/" name="RTF إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-potx/" name="RTF إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-pptm/" name="RTF إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-ppsx/" name="RTF إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-ppsm/" name="RTF إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/rtf-to-pptx/" name="RTF إلى PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}