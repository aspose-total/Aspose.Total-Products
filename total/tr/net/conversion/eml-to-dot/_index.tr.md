---
title: E-POSTA'yı DOT'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EML'i DOT'ye dönüştürün
url_ignore: /tr/net/conversion/eml-to-dot/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOT
otherformats: GIF EPUB TIFF PCL PNG DOTX PDF ODT RTF MD XPS JPEG OTT DOT WORDML DOCM TEXT PS DOC DOCX FLATOPC DOTM EMF SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EML'i .NET aracılığıyla DOT'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EML'i DOT'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EML to DOT dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EML dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi DOT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i DOT'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [Save](https://reference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3) yöntemini kullanarak EML'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi DOT formatına kaydedin ve Dot'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.dot", SaveFormat.Dot); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EML'i DOT'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EML belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/eml) [MapiMessage](https://reference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2=".NET ile DOT Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EML'den DOT'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);  
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