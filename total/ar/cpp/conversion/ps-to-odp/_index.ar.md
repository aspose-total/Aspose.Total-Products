---
title: C++ API لتحويل PS إلى ODP
description: قم بتحويل PS إلى ODP عبر C++ دون استخدام Microsoft Word أو Adobe Acrobat Reader
url: /ar/cpp/conversion/ps-to-odp/
family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: ODP
otherformats: PPSM PPS POT PPT XAML POTX POWERPOINT PPTM OTP POTM PPSX SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="عرض PS إلى ODP ضمن تطبيقات C++" h2="تحويل PS إلى ODP داخل تطبيقات C++ دون استخدام Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزة دمج PS إلى ODP داخل تطبيقات C++؟ يمكنك القيام بذلك في خطوتين بسيطتين. يمكنك تصدير PS إلى PPTX باستخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). ثانيًا ، باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ، يمكنك تحويل PPTX إلى ODP. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتصدير PS إلى ODP" %}}
1. افتح ملف PS باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) مرجع فئة
2. تحويل PS إلى PPTX باستخدام وظيفة الأسلوب [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. تحميل مستند PPTX باستخدام [عرض تقديمي](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) مرجع فئة
4. احفظ المستند بتنسيق ODP باستخدام وظيفة العضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وقم بتعيين "Odp" على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.ps");
// save PS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Odp format
prs->Save(u"output.odp", Aspose::Slides::Export::SaveFormat::Odp);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تغيير كلمة مرور مستند PS عبر C++" %}}
في عملية تقديم PS إلى ODP ، يمكنك فتح PS محمي بكلمة مرور وكذلك تغيير كلمة المرور الخاصة به. لتغيير كلمة مرور ملف PS ، يجب أن تعرف كلمة مرور مالك هذا المستند. يمكنك تحميل مستند PDF محمي بكلمة مرور باستخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) من خلال تحديد كلمة مرور مالكه واستخدام طريقة ChangePasswords لتغيير كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PS Document
auto doc = MakeObject<Document>(L"input.ps", L"owner");
// change password of PS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="أضف صورًا من الويب في ملف ODP عبر C++" %}}
بعد تحويل PS إلى ODP ، يمكنك أيضًا إضافة صور من الويب إلى المستند الناتج. يدعم [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) العمليات مع الصور بهذه التنسيقات الشائعة: JPEG و PNG و BMP و GIF وغيرها. يمكنك إضافة صورة واحدة أو عدة صور على جهاز الكمبيوتر الخاص بك إلى شريحة في عرض تقديمي. يوضح لك نموذج التعليمات البرمجية هذا في C++ كيفية إضافة صورة إلى ملف ODP
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a ODP file
auto pres = System::MakeObject<Presentation>("output.odp");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.odp", SaveFormat::Odp);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-ppsm/" name="PS إلى PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-pps/" name="PS إلى PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-pot/" name="PS إلى POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-ppt/" name="PS إلى PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-xaml/" name="PS إلى XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-potx/" name="PS إلى POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-powerpoint/" name="PS إلى POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-pptm/" name="PS إلى PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-otp/" name="PS إلى OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-potm/" name="PS إلى POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-ppsx/" name="PS إلى PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/ps-to-swf/" name="PS إلى SWF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}