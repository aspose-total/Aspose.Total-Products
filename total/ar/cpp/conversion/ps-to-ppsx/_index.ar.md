---
title: C++ API لتحويل PS إلى PPSX
description: قم بتحويل PS إلى PPSX عبر C++ دون استخدام Microsoft Word أو Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: PPSX
otherformats: OTP POTX PPTM POT PPSM XAML POTM PPT ODP SWF POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="عرض PS إلى PPSX ضمن تطبيقات C++" h2="تحويل PS إلى PPSX داخل تطبيقات C++ دون استخدام Microsoft <sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزة دمج PS إلى PPSX داخل تطبيقات C++؟ يمكنك القيام بذلك في خطوتين بسيطتين. يمكنك تصدير PS إلى PPTX باستخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). ثانيًا ، باستخدام [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) ، يمكنك تحويل PPTX إلى PPSX. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتصدير PS إلى PPSX" %}}
1. افتح ملف PS باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) مرجع فئة
2. تحويل PS إلى PPTX باستخدام وظيفة الأسلوب [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. تحميل مستند PPTX باستخدام [عرض تقديمي](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) مرجع فئة
4. احفظ المستند بتنسيق PPSX باستخدام وظيفة العضو [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) وقم بتعيين "Ppsx" على أنه SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.ps");
// save PS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تغيير كلمة مرور مستند PS عبر C++" %}}
في عملية تقديم PS إلى PPSX ، يمكنك فتح PS محمي بكلمة مرور وكذلك تغيير كلمة المرور الخاصة به. لتغيير كلمة مرور ملف PS ، يجب أن تعرف كلمة مرور مالك هذا المستند. يمكنك تحميل مستند PDF محمي بكلمة مرور باستخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) من خلال تحديد كلمة مرور مالكه واستخدام طريقة ChangePasswords لتغيير كلمة المرور.
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

{{% blocks/products/pf/feature-page-section  h2="أضف صورًا من الويب في ملف PPSX عبر C++" %}}
بعد تحويل PS إلى PPSX ، يمكنك أيضًا إضافة صور من الويب إلى المستند الناتج. يدعم [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) العمليات مع الصور بهذه التنسيقات الشائعة: JPEG و PNG و BMP و GIF وغيرها. يمكنك إضافة صورة واحدة أو عدة صور على جهاز الكمبيوتر الخاص بك إلى شريحة في عرض تقديمي. يوضح لك نموذج التعليمات البرمجية هذا في C++ كيفية إضافة صورة إلى ملف PPSX
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
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
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}