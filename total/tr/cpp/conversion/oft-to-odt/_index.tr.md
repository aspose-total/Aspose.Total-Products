---
title: OFT'i C++ aracılığıyla ODT'ye aktarın
description: Microsoft Word veya Outlook kullanmadan OFT'i ODT'ye Dönüştürmek için C++ API
url: /tr/cpp/conversion/oft-to-odt/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: ODT
otherformats: WORDML DOTX DOC PNG DOTM EMF MD PS DOCX TIFF GIF RTF DOT PDF XPS JPEG FLATOPC EPUB BMP DOCM OTT PCL SVG TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="OFT'i ODT'ye Dışa Aktarmak için C++ API" h2="Microsoft Word veya Outlook gerektirmeden OFT'i C++ uygulaması içinde ODT'ye dönüştürün" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınıza e-posta dönüştürme özellikleri eklemek isteyen bir C++ geliştiricisi misiniz? [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) kullanarak OFT dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API'sini kullanarak HTML'yi ODT'ye aktarabilirsiniz. Her iki API de [Aspose.Total for C++](https://products.aspose.com/total/cpp/) paketi kapsamında gelir. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="OFT'i ODT'ye Dönüştürmek için C++ API" %}}
1. [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message) sınıf referansını kullanarak OFT dosyasını açın
2. [Kaydet](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) üye işlevini kullanarak OFT'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) sınıfını kullanarak yükleyin
4. [Kaydet](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) yöntemini kullanarak belgeyi ODT formatına kaydedin ve Odt'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ``nuget install Aspose.Total.Cpp``` veya Visual Studio Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total.Cpp`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [downloads](https://downloads.aspose.com/total/cpp) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Odt as save format
doc->Save(u"convertedFile.Odt");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını C++ ile Ayrıştırma" %}}
Yalnızca OFT'inizi ODT'ye dönüştürmekle kalmaz, aynı zamanda OFT belgesini okuyabilir, değiştirebilir ve ayrıştırabilirsiniz. [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API'sinin MapiMessage sınıfını kullanarak e-postanın konu, adres, gövde, alıcı bilgilerini alabilirsiniz. Örneğin, get_SenderOftAddress() özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.
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

{{% blocks/products/pf/feature-page-section  h2="ODT Dosya Biçimi Düzenlemesini Kısıtlamak için C++ API" %}}
Belgeyi OFT'den ODT'ye aktarırken uygulamanıza belge koruma özellikleri de ekleyebilirsiniz. Belgenize koruma eklemek basit bir işlemdir, çünkü tek yapmanız gereken koruma yöntemini belgenize uygulamaktır. Kullanıcının belgeyi düzenlemesini kısıtlamak için koruma türünü Salt Okunur olarak ayarlayabilirsiniz.
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
{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-wordml/" name="OFT İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-dotx/" name="OFT İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-doc/" name="OFT İle DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-png/" name="OFT İle PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-dotm/" name="OFT İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-emf/" name="OFT İle EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-md/" name="OFT İle MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-ps/" name="OFT İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-docx/" name="OFT İle DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-tiff/" name="OFT İle TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-gif/" name="OFT İle GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-rtf/" name="OFT İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-dot/" name="OFT İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-pdf/" name="OFT İle PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-xps/" name="OFT İle XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-jpeg/" name="OFT İle JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-flatopc/" name="OFT İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-epub/" name="OFT İle EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-odt/" name="OFT İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-docm/" name="OFT İle DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-ott/" name="OFT İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-pcl/" name="OFT İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-svg/" name="OFT İle SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/cpp/conversion/oft-to-text/" name="OFT İle TEXT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}