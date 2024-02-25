---
title: قم بتصدير EML إلى ODT عبر C++
description: C++ API لتحويل البريد الإلكتروني إلى ODT دون استخدام Microsoft Word أو Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: ODT
otherformats: OTT PDF EPUB DOC SVG GIF EMF DOCX WORDML TEXT DOT MD RTF BMP PCL DOTM PS FLATOPC DOTX JPEG TIFF PNG XPS DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API لتصدير البريد الإلكتروني إلى ODT" h2="قم بتحويل EML إلى ODT داخل تطبيق C++ دون الحاجة إلى Microsoft Word أو Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
هل أنت مطور C++ تتطلع إلى إضافة ميزات تحويل البريد الإلكتروني داخل تطبيقاتك؟ باستخدام [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) يمكنك تحويل تنسيق ملف EML إلى HTML. بعد ذلك ، باستخدام واجهة برمجة تطبيقات [Aspose.Words for C++](https://products.aspose.com/words/cpp/) ، يمكنك تصدير HTML إلى ODT. تأتي كلتا واجهات برمجة التطبيقات ضمن حزمة [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API لتحويل البريد الإلكتروني إلى ODT" %}}
1. افتح ملف EML باستخدام مرجع فئة [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. تحويل EML إلى HTML باستخدام وظيفة العضو [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. قم بتحميل HTML باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. احفظ المستند بتنسيق ODT باستخدام طريقة [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) وقم بتعيين Odt كـ SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات التحويل" %}}
قم بالتثبيت من سطر الأوامر كـ `` nuget install Aspose.Total.Cpp '' أو عبر Package Manager Console في Visual Studio مع `` Install-Package Aspose.Total.Cpp ''.

بدلاً من ذلك ، احصل على مثبّت MSI غير المتصل أو مكتبات DLL في ملف ZIP من [التنزيلات](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Odt as save format
doc->Save(u"convertedFile.Odt");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="تحليل ملف البريد الإلكتروني عبر C++" %}}
لا يمكنك فقط تحويل بريدك الإلكتروني إلى ODT ، ولكن يمكنك قراءة مستند EML ومعالجته وتحليله. يمكنك الحصول على معلومات عن الموضوع والعنوان والجسم والمستلمين للبريد الإلكتروني باستخدام فئة MapiMessage من [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API. على سبيل المثال ، يمكنك التحقق من وجود بريد إلكتروني معين لمرسل التحويل باستخدام خاصية get_SenderEmlAddress ().
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

{{% blocks/products/pf/feature-page-section  h2="C++ API لتقييد تحرير تنسيق ملف ODT" %}}
يمكنك أيضًا إضافة ميزات حماية المستندات في تطبيقك أثناء تصدير المستند من EML إلى ODT. تعد إضافة الحماية إلى المستند الخاص بك عملية بسيطة ، حيث أن كل ما عليك فعله هو تطبيق طريقة الحماية على المستند الخاص بك. يمكنك تعيين نوع الحماية للقراءة فقط لتقييد المستخدم لتحرير المستند.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Odt");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}