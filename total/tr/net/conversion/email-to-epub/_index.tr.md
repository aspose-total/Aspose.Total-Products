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

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
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
.aspose.com
{{% blocks/products/pf/feature-page-section  h2=".NET ile EPUB Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EMAIL'den EPUB'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-pcl/" name="MSG'den PCL'ye" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-pdf/" name="MSG'DEN PDF'E" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dot/" name="Noktaya MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-flatopc/" name="MSG'DEN FLATOPC'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-jpeg/" name="MSG'den JPEG'e" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-png/" name="PNG'ye MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-rtf/" name="MSG'DEN RTF'ye" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-tiff/" name="TIFF'YE MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-docm/" name="DOCM'YE MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-ps/" name="MSG'DEN PS'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-gif/" name="GIF'E MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-xps/" name="MSG'DEN XPS'E" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-odt/" name="MSG'DEN ODT'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-docx/" name="MSG'DEN DOCX'E" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-doc/" name="DOC'A MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-wordml/" name="MSG'DEN WORDML'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-svg/" name="MSG'den SVG'ye" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-epub/" name="EPUB'A MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-md/" name="MSG'DEN MD'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-emf/" name="MSG'DEN EMF'YE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dotm/" name="MSG'DEN DOTM'A" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-ott/" name="OTT'YE MSG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-dotx/" name="MSG'DEN DOTX'E" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/msg-to-text/" name="METİN İÇİN MSG" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}