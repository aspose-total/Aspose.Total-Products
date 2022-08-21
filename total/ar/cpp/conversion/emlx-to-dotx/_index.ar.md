---
title: قم بتصدير EMLX إلى DOTX عبر C++
description: C++ API لتحويل البريد الإلكتروني إلى DOTX دون استخدام Microsoft Word أو Outlook
url: /ar/cpp/conversion/emlx-to-dotx/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOTX
otherformats: JPEG GIF RTF EPUB PDF XPS SVG DOC BMP PNG DOTM PS WORDML PCL ODT MD DOCM OTT FLATOPC EMF DOCX TIFF DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتصدير البريد الإلكتروني إلى DOTX" h2="قم بتحويل EMLX إلى DOTX داخل تطبيق C++ دون الحاجة إلى Microsoft Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزات تحويل البريد الإلكتروني داخل تطبيقاتك؟ باستخدام [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) يمكنك تحويل تنسيق ملف EMLX إلى HTML. بعد ذلك ، باستخدام واجهة برمجة تطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير HTML إلى DOTX. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل البريد الإلكتروني إلى DOTX" %}}
1. افتح ملف EMLX باستخدام مرجع فئة [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. تحويل EMLX إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. احفظ المستند بتنسيق DOTX باستخدام طريقة [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) وقم بتعيين Dotx كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dotx as save format
doc->Save(u"convertedFile.Dotx");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر C++" %}}
لا يمكنك فقط تحويل بريدك الإلكتروني إلى DOTX ، ولكن يمكنك قراءة مستند EMLX ومعالجته وتحليله. يمكنك الحصول على معلومات عن الموضوع والعنوان والجسم والمستلمين للبريد الإلكتروني باستخدام فئة MapiMessage من [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية get_SenderEmlxAddress ().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API لتقييد تحرير تنسيق ملف DOTX" %}}
يمكنك أيضًا إضافة ميزات حماية المستندات في تطبيقك أثناء تصدير المستند من EMLX إلى DOTX. تعد إضافة الحماية إلى المستند الخاص بك عملية بسيطة ، حيث أن كل ما عليك فعله هو تطبيق طريقة الحماية على المستند الخاص بك. يمكنك تعيين نوع الحماية للقراءة فقط لتقييد المستخدم لتحرير المستند.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dotx");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="التحويلات المدعومة الأخرى" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-jpeg/" name="EMLX إلى JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-gif/" name="EMLX إلى GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-rtf/" name="EMLX إلى RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-epub/" name="EMLX إلى EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-pdf/" name="EMLX إلى PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-xps/" name="EMLX إلى XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-svg/" name="EMLX إلى SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-doc/" name="EMLX إلى DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-dotx/" name="EMLX إلى DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-png/" name="EMLX إلى PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-dotm/" name="EMLX إلى DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-ps/" name="EMLX إلى PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-wordml/" name="EMLX إلى WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-pcl/" name="EMLX إلى PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-odt/" name="EMLX إلى ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-md/" name="EMLX إلى MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-docm/" name="EMLX إلى DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-ott/" name="EMLX إلى OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-flatopc/" name="EMLX إلى FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-emf/" name="EMLX إلى EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-docx/" name="EMLX إلى DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-tiff/" name="EMLX إلى TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-dot/" name="EMLX إلى DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ar/cpp/conversion/emlx-to-text/" name="EMLX إلى TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}