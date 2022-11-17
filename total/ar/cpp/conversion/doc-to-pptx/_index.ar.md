---
title: تحويل DOC إلى PPTX عبر C++
description: قم بتصدير DOC إلى PPTX في تطبيقات C++ دون استخدام Microsoft Word of PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPTX
otherformats: POWERPOINT ODP POTM POT PPS PPSM PPTM PPT POTX PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتحويل DOC إلى PPTX" h2="تصدير DOC إلى PPTX داخل تطبيقات C++ دون استخدام Microsoft Word <sup>&reg;</sup> ؛ أو PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
يتكون [Aspose.Total for C++](https://products.aspose.com/total/cpp/) من واجهات برمجة تطبيقات قوية لأتمتة الملفات تسمح بأتمتة تحويل DOC إلى PPTX أثناء استخدام اثنين من واجهات برمجة التطبيقات الخاصة به. قم بتحميل مستند DOC باستخدام [Aspose.Words for C++](https://products.aspose.com/words/cpp/) وقم بتحويله إلى HTML ، ثم قم بتحميل HTML عبر معالجة PowerPoint C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإنشاء عرض تقديمي جديد وحفظه كـ PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="تحويل DOC إلى PPTX على C++" %}}
1. افتح ملف DOC باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة
2. تحويل DOC إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. تهيئة كائن [عرض تقديمي] جديد(https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. إضافة شكل تلقائي في الشريحة الخاصة بك ، وإضافة AddTextFrame فيه
5. قم بتحميل محتوى HTML واكتبه في ملف العرض التقديمي الخاص بك
6. احفظ المستند بتنسيق PPTX باستخدام طريقة [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وتعيين Pptx على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
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

{{% blocks/products/pf/feature-page-section  h2="قم بتحميل مستند DOC المحمي بكلمة مرور عبر C++" %}}
بصرف النظر عن تحويل المستندات ، تسمح واجهة برمجة التطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) بالعديد من ميزات معالجة المستندات لمطوري C++. إذا كان تنسيق ملف Microsoft Word DOC محميًا بكلمة مرور ، فلا يزال بإمكانك فتحه باستخدام API. لتحميل المستند المشفر ، يمكنك استخدام مُنشئ خاص زائد التحميل ، والذي يقبل كائن [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). يحتوي هذا الكائن على خاصية كلمة المرور ، والتي تحدد سلسلة كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أضف التعليقات في مستند PPTX عبر C++" %}}
أثناء حفظ DOC كـ PPTX ، يمكنك أيضًا استخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) لإضافة المزيد من الميزات في مستند PPTX الخاص بك. على سبيل المثال ، يمكنك إضافة تعليقات في العرض التقديمي الخاص بك. يرتبط تعليق شريحة العرض التقديمي بمؤلف معين. يتضمن فصل العرض التقديمي مجموعة المؤلفين في ICommentAuthorCollection المسؤولة عن إضافة تعليقات الشرائح. لكل مؤلف ، هناك مجموعة من التعليقات في ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-powerpoint/" name="DOC إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-pptx/" name="DOC إلى PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-potm/" name="DOC إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-pot/" name="DOC إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-pps/" name="DOC إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-ppsm/" name="DOC إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-pptm/" name="DOC إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-ppt/" name="DOC إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-potx/" name="DOC إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/doc-to-ppsx/" name="DOC إلى PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}