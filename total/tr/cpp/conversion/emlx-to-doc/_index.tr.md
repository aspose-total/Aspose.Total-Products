---
title: EMLX'i C++ aracılığıyla DOC'ye aktarın
description: Microsoft Word veya Outlook kullanmadan EMLX'i DOC'ye Dönüştürmek için C++ API

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOC
otherformats: SVG TIFF FLATOPC XPS GIF MD EMF RTF ODT PS WORDML DOTM DOCM BMP JPEG DOTX DOT PNG OTT PCL PDF DOCX TEXT EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="EMLX'i DOC'ye Dışa Aktarmak için C++ API" h2="Microsoft Word veya Outlook gerektirmeden EMLX'i C++ uygulaması içinde DOC'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınıza e-posta dönüştürme özellikleri eklemek isteyen bir C++ geliştiricisi misiniz? [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) kullanarak EMLX dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak HTML'yi DOC'ye aktarabilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX'i DOC'ye Dönüştürmek için C++ API" %}}
1. [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message) sınıf referansını kullanarak EMLX dosyasını açın
2. [Kaydet](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) üye işlevini kullanarak EMLX'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) yöntemini kullanarak belgeyi DOC formatına kaydedin ve Doc'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://releases.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Doc as save format
doc->Save(u"convertedFile.Doc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını C++ ile Ayrıştırma" %}}
Yalnızca EMLX'inizi DOC'ye dönüştürmekle kalmaz, aynı zamanda EMLX belgesini okuyabilir, değiştirebilir ve ayrıştırabilirsiniz. [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API'sinin MapiMessage sınıfını kullanarak e-postanın konu, adres, gövde, alıcı bilgilerini alabilirsiniz. Örneğin, get_SenderEmlxAddress() özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.
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

{{% blocks/products/pf/feature-page-section  h2="DOC Dosya Biçimi Düzenlemesini Kısıtlamak için C++ API" %}}
Belgeyi EMLX'den DOC'ye aktarırken uygulamanıza belge koruma özellikleri de ekleyebilirsiniz. Belgenize koruma eklemek basit bir işlemdir, çünkü tek yapmanız gereken koruma yöntemini belgenize uygulamaktır. Kullanıcının belgeyi düzenlemesini kısıtlamak için koruma türünü Salt Okunur olarak ayarlayabilirsiniz.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}