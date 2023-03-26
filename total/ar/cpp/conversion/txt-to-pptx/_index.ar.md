---
title: تحويل TXT إلى PPTX عبر C++ أو مع محول مجاني على الإنترنت
description: قم بتصدير TXT إلى PPTX في تطبيقات C++ دون استخدام Microsoft Word of PowerPoint أو عبر الإنترنت. اختبر محول POT إلى CSV على الإنترنت مجانًا بسرعة قبل دمج الكود.

family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: PPTX
otherformats: POT POWERPOINT PPT POTX PPSX ODP POTM PPSM PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل TXT إلى PPTX أو التطبيق عبر الإنترنت" h2="تصدير TXT إلى PPTX داخل تطبيقات C++ دون استخدام Microsoft Word <sup>&reg;</sup> ؛ أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يتكون [Aspose.Total for C++](https://products.aspose.com/total/cpp/) من واجهات برمجة تطبيقات قوية لأتمتة الملفات تسمح بأتمتة تحويل TXT إلى PPTX أثناء استخدام اثنين من واجهات برمجة التطبيقات الخاصة به. قم بتحميل مستند TXT باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) وقم بتحويله إلى HTML ، ثم قم بتحميل HTML عبر معالجة PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإنشاء عرض تقديمي جديد وحفظه كـ PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل TXT إلى PPTX على C++" %}}
1. افتح ملف TXT باستخدام [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument) مرجع فئة
2. تحويل TXT إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions)
3. تهيئة كائن [عرض تقديمي] جديد(https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. إضافة شكل تلقائي في الشريحة الخاصة بك ، وإضافة AddTextFrame فيه
5. قم بتحميل محتوى HTML واكتبه في ملف العرض التقديمي الخاص بك
6. احفظ المستند بتنسيق PPTX باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Pptx على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TXT file with an instance of Txtument
Txtument txtument = new Txtument("template.txt");
System::SharedPtr<Txtument> txt = System::MakeObject<Txtument>(u"sourceFile.txt");
// save the txtument in HTML file format
txt->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>محول مجاني على الإنترنت لـ TXT إلى PPTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند TXT المحمي بكلمة مرور عبر C++" %}}
بصرف النظر عن تحويل المستندات ، تسمح واجهة برمجة التطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) بالعديد من ميزات معالجة المستندات لمطوري C++. إذا كان تنسيق ملف Microsoft Word TXT محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام API. لتحميل المستند المشفر ، يمكنك استخدام مُنشئ خاص زائد التحميل ، والذي يقبل كائن [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). يحتوي هذا الكائن على خاصية كلمة المرور ، والتي تحدد سلسلة كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أضف التعليقات في مستند PPTX عبر C++" %}}
أثناء حفظ TXT كـ PPTX ، يمكنك أيضًا استخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإضافة المزيد من الميزات في مستند PPTX الخاص بك. على سبيل المثال ، يمكنك إضافة تعليقات في العرض التقديمي الخاص بك. يرتبط تعليق شريحة العرض التقديمي بمؤلف معين. يتضمن فصل العرض التقديمي مجموعة المؤلفين في ICommentAuthorCollection المسؤولة عن إضافة تعليقات الشرائح. لكل مؤلف ، هناك مجموعة من التعليقات في ICommentCollection.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}