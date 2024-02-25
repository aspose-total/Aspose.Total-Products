---
title: قم بتصدير OFT إلى DOT عبر C++
description: C++ API لتحويل البريد الإلكتروني إلى DOT دون استخدام Microsoft Word أو Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: DOT
otherformats: DOTX BMP GIF DOCM FLATOPC XPS DOCX PS WORDML PNG OTT DOC DOTM PCL JPEG EMF RTF TIFF MD EPUB SVG ODT TEXT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتصدير البريد الإلكتروني إلى DOT" h2="قم بتحويل OFT إلى DOT داخل تطبيق C++ دون الحاجة إلى Microsoft Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزات تحويل البريد الإلكتروني داخل تطبيقاتك؟ باستخدام [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) يمكنك تحويل تنسيق ملف OFT إلى HTML. بعد ذلك ، باستخدام واجهة برمجة تطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير HTML إلى DOT. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل البريد الإلكتروني إلى DOT" %}}
1. افتح ملف OFT باستخدام مرجع فئة [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. تحويل OFT إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. احفظ المستند بتنسيق DOT باستخدام طريقة [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) وقم بتعيين Dot كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Dot as save format
doc->Save(u"convertedFile.Dot");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر C++" %}}
لا يمكنك فقط تحويل بريدك الإلكتروني إلى DOT ، ولكن يمكنك قراءة مستند OFT ومعالجته وتحليله. يمكنك الحصول على معلومات عن الموضوع والعنوان والجسم والمستلمين للبريد الإلكتروني باستخدام فئة MapiMessage من [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية get_SenderOftAddress ().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++ API لتقييد تحرير تنسيق ملف DOT" %}}
يمكنك أيضًا إضافة ميزات حماية المستندات في تطبيقك أثناء تصدير المستند من OFT إلى DOT. تعد إضافة الحماية إلى المستند الخاص بك عملية بسيطة ، حيث أن كل ما عليك فعله هو تطبيق طريقة الحماية على المستند الخاص بك. يمكنك تعيين نوع الحماية للقراءة فقط لتقييد المستخدم لتحرير المستند.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Dot");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}