---
title: تحويل DOTX إلى PPTM عبر C++
description: قم بتصدير DOTX إلى PPTM في تطبيقات C++ دون استخدام Microsoft Word of PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: PPTM
otherformats: PPSM POWERPOINT PPTX PPT ODP POT POTM POTX PPS PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOTX إلى PPTM" h2="تصدير DOTX إلى PPTM داخل تطبيقات C++ دون استخدام Microsoft Word <sup>&reg;</sup> ؛ أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يتكون [Aspose.Total for C++](https://products.aspose.com/total/cpp/) من واجهات برمجة تطبيقات قوية لأتمتة الملفات تسمح بأتمتة تحويل DOTX إلى PPTM أثناء استخدام اثنين من واجهات برمجة التطبيقات الخاصة به. قم بتحميل مستند DOTX باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) وقم بتحويله إلى HTML ، ثم قم بتحميل HTML عبر معالجة PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإنشاء عرض تقديمي جديد وحفظه كـ PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOTX إلى PPTM على C++" %}}
1. افتح ملف DOTX باستخدام [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) مرجع فئة
2. تحويل DOTX إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. تهيئة كائن [عرض تقديمي] جديد(https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. إضافة شكل تلقائي في الشريحة الخاصة بك ، وإضافة AddTextFrame فيه
5. قم بتحميل محتوى HTML واكتبه في ملف العرض التقديمي الخاص بك
6. احفظ المستند بتنسيق PPTM باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Pptm على أنه SaveFormat
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ DOTX إلى PPTM</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptm&from=dotx" id="child-iframe" width="80%"></iframe>

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

{{% blocks/products/pf/feature-page-section  h2="أضف التعليقات في مستند PPTM عبر C++" %}}
أثناء حفظ DOTX كـ PPTM ، يمكنك أيضًا استخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإضافة المزيد من الميزات في مستند PPTM الخاص بك. على سبيل المثال ، يمكنك إضافة تعليقات في العرض التقديمي الخاص بك. يرتبط تعليق شريحة العرض التقديمي بمؤلف معين. يتضمن فصل العرض التقديمي مجموعة المؤلفين في ICommentAuthorCollection المسؤولة عن إضافة تعليقات الشرائح. لكل مؤلف ، هناك مجموعة من التعليقات في ICommentCollection.
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-ppsm/" name="DOTX إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-powerpoint/" name="DOTX إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-pptx/" name="DOTX إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-ppt/" name="DOTX إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-pptm/" name="DOTX إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-pot/" name="DOTX إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-potm/" name="DOTX إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-potx/" name="DOTX إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-pps/" name="DOTX إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/dotx-to-ppsx/" name="DOTX إلى PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}