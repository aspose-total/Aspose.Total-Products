---
title: قم بتصدير EML إلى JPEG عبر C++
description: C++ API لتحويل البريد الإلكتروني إلى JPEG دون استخدام Microsoft Word أو Outlook
url: /ar/cpp/conversion/eml-to-jpeg/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: JPEG
otherformats: SVG XPS DOTM DOTX PS DOC EMF RTF MD PDF TIFF GIF DOCM DOCX BMP DOT FLATOPC PNG WORDML OTT TEXT ODT PCL EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتصدير البريد الإلكتروني إلى JPEG" h2="قم بتحويل EML إلى JPEG داخل تطبيق C++ دون الحاجة إلى Microsoft Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزات تحويل البريد الإلكتروني داخل تطبيقاتك؟ باستخدام [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام واجهة برمجة تطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير HTML إلى JPEG. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل البريد الإلكتروني إلى JPEG" %}}
1. افتح ملف EML باستخدام مرجع فئة [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. تحويل EML إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. احفظ المستند بتنسيق JPEG باستخدام طريقة [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) وقم بتعيين Jpeg كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Jpeg as save format
doc->Save(u"convertedFile.Jpeg");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر C++" %}}
لا يمكنك فقط تحويل بريدك الإلكتروني إلى JPEG ، ولكن يمكنك قراءة مستند EML ومعالجته وتحليله. يمكنك الحصول على معلومات عن الموضوع والعنوان والجسم والمستلمين للبريد الإلكتروني باستخدام فئة MapiMessage من [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية get_SenderEmlAddress ().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API لتقييد تحرير تنسيق ملف JPEG" %}}
يمكنك أيضًا إضافة ميزات حماية المستندات في تطبيقك أثناء تصدير المستند من EML إلى JPEG. تعد إضافة الحماية إلى المستند الخاص بك عملية بسيطة ، حيث أن كل ما عليك فعله هو تطبيق طريقة الحماية على المستند الخاص بك. يمكنك تعيين نوع الحماية للقراءة فقط لتقييد المستخدم لتحرير المستند.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Jpeg");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-svg/" name="EML إلى SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-xps/" name="EML إلى XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-dotm/" name="EML إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-dotx/" name="EML إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-ps/" name="EML إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-doc/" name="EML إلى DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-emf/" name="EML إلى EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-rtf/" name="EML إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-md/" name="EML إلى MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-pdf/" name="EML إلى PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-tiff/" name="EML إلى TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-gif/" name="EML إلى GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-docm/" name="EML إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-docx/" name="EML إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-jpeg/" name="EML إلى JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-dot/" name="EML إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-flatopc/" name="EML إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-png/" name="EML إلى PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-wordml/" name="EML إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-ott/" name="EML إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-text/" name="EML إلى TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-odt/" name="EML إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-pcl/" name="EML إلى PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/eml-to-epub/" name="EML إلى EPUB" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}