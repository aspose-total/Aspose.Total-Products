---
title: EMAIL'i C++ aracılığıyla ODT'ye aktarın
description: Microsoft Word veya Outlook kullanmadan EMAIL'i ODT'ye Dönüştürmek için C++ API

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: ODT
otherformats: DOTX XPS TIFF DOC DOTM EPUB GIF SVG PDF PS OTT PNG DOCM RTF MD BMP PCL JPEG TEXT DOCX WORDML EMF DOT FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EMAIL'i ODT'ye Dışa Aktarmak için C++ API" h2="Microsoft Word veya Outlook gerektirmeden EMAIL'i C++ uygulaması içinde ODT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınıza e-posta dönüştürme özellikleri eklemek isteyen bir C++ geliştiricisi misiniz? [Aspose.Email for C++](https://products.aspose.com/email/cpp/) kullanarak EMAIL dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak HTML'yi ODT'ye aktarabilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL'i ODT'ye Dönüştürmek için C++ API" %}}
1. [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message) sınıf referansını kullanarak EMAIL dosyasını açın
2. [Kaydet](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) üye işlevini kullanarak EMAIL'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) yöntemini kullanarak belgeyi ODT formatına kaydedin ve Odt'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Odt as save format
doc->Save(u"convertedFile.Odt");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını C++ ile Ayrıştırma" %}}
Yalnızca EMAIL'inizi ODT'ye dönüştürmekle kalmaz, aynı zamanda EMAIL belgesini okuyabilir, değiştirebilir ve ayrıştırabilirsiniz. [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API'sinin MapiMessage sınıfını kullanarak e-postanın konu, adres, gövde, alıcı bilgilerini alabilirsiniz. Örneğin, get_SenderEmailAddress() özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ODT Dosya Biçimi Düzenlemesini Kısıtlamak için C++ API" %}}
Belgeyi EMAIL'den ODT'ye aktarırken uygulamanıza belge koruma özellikleri de ekleyebilirsiniz. Belgenize koruma eklemek basit bir işlemdir, çünkü tek yapmanız gereken koruma yöntemini belgenize uygulamaktır. Kullanıcının belgeyi düzenlemesini kısıtlamak için koruma türünü Salt Okunur olarak ayarlayabilirsiniz.
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