---
title: C++ API لتصدير TEX إلى PCL
description: تحويل TEX إلى PCL داخل تطبيقات C++.
url: /ar/cpp/conversion/tex-to-pcl/
family: total
platformtag: cpp
feature: conversion
informat: TEX
outformat: PCL
otherformats: XAMLFLOW WORDML FLATOPC OTT PS DOT DOCM DOTX RTF MARKDOWN ODT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتصدير TEX إلى PCL" h2="تقديم TEX إلى PCL داخل تطبيقات C++ دون الحاجة إلى أي تطبيق تابع لجهة خارجية" >}}

{{% blocks/products/pf/feature-page-summary %}}
تتيح مكتبات أتمتة تنسيق الملفات [Aspose.Total for C++](https://products.aspose.com/total/cpp/) لمطور C++ تحويل TEX إلى PCL في خطوتين بسيطتين. أولاً ، يمكنك استخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) API لتحويل تنسيق ملف TEX إلى DOC. ثانيًا ، باستخدام واجهة برمجة تطبيقات معالجة مستندات Word المتقدمة [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير DOC إلى PCL. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="واجهة برمجة تطبيقات C++ لتقديم TEX إلى PCL" %}}
1. افتح ملف TEX باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) مرجع فئة
2. تحويل TEX إلى DOC باستخدام وظيفة العضو [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. تحميل ملف DOC باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة Aspose.Words API
4. احفظ المستند بتنسيق PCL باستخدام وظيفة العضو [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TEX file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.tex");
// save TEX as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Pcl
wordDoc->Save(u"output.Pcl");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تغيير كلمة مرور مستند TEX عبر C++" %}}
في عملية تقديم TEX إلى PCL ، يمكنك فتح TEX محمية بكلمة مرور وكذلك تغيير كلمة المرور الخاصة بها. لتغيير كلمة مرور ملف TEX ، يجب أن تعرف كلمة مرور مالك هذا المستند. يمكنك تحميل مستند PDF محمي بكلمة مرور باستخدام [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) من خلال تحديد كلمة مرور مالكه واستخدام طريقة ChangePasswords لتغيير كلمة المرور.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing TEX Document
auto doc = MakeObject<Document>(L"input.tex", L"owner");
// change password of TEX Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="تقييد تحرير ملف PCL عبر C++" %}}
يمكنك أيضًا تقييد تحرير ملف PCL باستخدام واجهة برمجة تطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/). قد تحتاج في بعض الأحيان إلى تقييد القدرة على تحرير مستند والسماح فقط بإجراءات معينة معه. تمكّنك واجهة برمجة التطبيقات من التحكم في طريقة تقييد المحتوى باستخدام معلمة التعداد [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). يوضح المثال التالي من التعليمات البرمجية كيفية تقييد التحرير في مستند بحيث لا يكون التحرير ممكنًا إلا في حقول النموذج.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Pcl");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-xamlflow/" name="TEX إلى XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-wordml/" name="TEX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-flatopc/" name="TEX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-ott/" name="TEX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-ps/" name="TEX إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-dot/" name="TEX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-pcl/" name="TEX إلى PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-dotx/" name="TEX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-rtf/" name="TEX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-markdown/" name="TEX إلى MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-odt/" name="TEX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/tex-to-mhtml/" name="TEX إلى MHTML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}