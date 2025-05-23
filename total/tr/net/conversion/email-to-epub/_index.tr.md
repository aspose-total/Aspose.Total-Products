---
title: E-POSTA'yı EPUB'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EMAIL'i EPUB'ye dönüştürün
url_ignore: /tr/net/conversion/email-to-epub/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: EPUB
otherformats: DOTM PNG PS SVG TIFF JPEG ODT DOT DOCM PCL OTT EPUB WORDML DOTX RTF MD PDF GIF FLATOPC EMF TEXT XPS DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMAIL'i .NET aracılığıyla EPUB'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EMAIL'i EPUB'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EMAIL to EPUB dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EMAIL dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi EPUB'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL'i EPUB'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) sınıfını kullanarak EMAIL dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EMAIL'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi EPUB formatına kaydedin ve Epub'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EMAIL'i EPUB'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EMAIL belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/email) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile EPUB Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EMAIL'den EPUB'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL Dosyasını Programatik Olarak EPUB'e Dönüştürme: Kullanım Örnekleri" %}}
E-posta dosyası, metin tabanlı mesajları kaydetmek için ideal bir formattır. Bu formatın en önemli özelliği, özelleştirilmiş iletişim ve haber bültenleri oluşturmak için uygun olmasıdır. Ancak, multimedya içeriklerle çalışan durumlarda ise EPUB (Elektronik Yayın) formatları vazgeçilmez bir seçenektir.

E-posta dosyasının EPUB formatına çevirmek, dijital yayın yeteneklerinizi tamamen kullanmanıza yardımcı olur. Bu çevrim, aşağıdaki işlevleri mümkün hale getirir:

**Kullanım Durumları:**

* **Özelleştirilmiş E-Bültenler**: E-posta dosyalarını kullanarak özelleştirilmiş ve etkileyici e-bültenler oluşturun, okunma yeteneklerini göz önünde bulundurarak kullanıcı adlarını ve ilgilerini dikkate alarak.

* **Dijital Dergi Yayınları**: EPUB formatını kullanarak çeşitli cihazlarda okunabilir şekilde dergi, gazete ve periodik yayınlar yayınlayabilirsiniz.

* **E-Kitap Yayınları**: E-posta dosyalarını kullanarak etkileşimli e-kitaplar oluşturun, içerikte bağlantılar, resimler ve multimedya içeriğiyle birlikte.

* **Şirket İletişimleri**: EPUB formatını kullanarak şirket raporları, politikalar ve işlemleri员工 ve stakeholderlara erişilebilir bir şekilde dağıtabilirsiniz.

* **Dijital İçerik Dağıtımı**: E-posta dosyalarını kullanarak blog yazıları, makaleler ve video gibi içerikleri çeşitli platformlarda yayınlayabilirsiniz.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}