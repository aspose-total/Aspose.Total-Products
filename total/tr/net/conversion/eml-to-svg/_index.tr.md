---
title: E-POSTA'yı SVG'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EML'i SVG'ye dönüştürün
url_ignore: /tr/net/conversion/eml-to-svg/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: SVG
otherformats: DOCX OTT PS DOTX WORDML GIF PNG SVG ODT RTF DOC PCL XPS MD DOT JPEG TIFF EMF TEXT PDF FLATOPC EPUB DOCM DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EML'i .NET aracılığıyla SVG'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EML'i SVG'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EML to SVG dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EML dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi SVG'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i SVG'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EML'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi SVG formatına kaydedin ve Svg'yi SaveFormat olarak ayarlayın
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

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EML'i SVG'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EML belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/eml) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile SVG Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EML'den SVG'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML Dosyasını Programatik Olarak SVG'e Dönüştürme: Kullanım Örnekleri" %}}
E-posta Dosyaları, metin tabanlı mesajları kaydetmek için kullanılır ve bu nedenle e-posta gönderme ve alma purposesinde idealdir. Ancak, grafiksel verilerle çalışan durumlarda, Scalable Vector Graphics (SVG) dosyaları, çözünürlük bağımsız ve ölçeklenebilir graphics oluşturmak için esas niteliğe sahiptir.

**Kullanım Durumları:**

* **Web Grafik Tasarımı**: E-posta dosyalarını kullanarak farklı ekran çözünürlüklerinde ölçeklenebilir ve vector tabanlı web grafikleri, logolar ve ikonlar oluşturun.
  
* **Desktop Yayıncılık**: Yayınlarla ve sunumlarda karmaşık grafiksel veriler vizualize etmek için SVG'yi kullanun.örneğin graflar, tablolar ve infografikler gibi veri görüntemlerini oluşturun.

* **Mobil Uygulama Geliştirme**: Mobil uygulamalar için ölçeklenebilir ve illüstrasyonlar oluşturmak için E-posta dosyalarını kullanun. Bu şekilde farklı cihazlarda kullanıcı deneyimini sabit hale getirebilirsiniz.

* **Eğitim İçerikleri Oluşturma**: E-posta dosyalarını kullanarak etkileşimli ve çekici vizualizasyonlar oluşturun.örneğin animasyonlu rehberler ve simülasyonlarla eğitim içerikleri oluşturun.

* **Veri Görüntüleme ve Raporlama**: E-posta dosyalarını kullanarak etkileşimli dashbordlar, raporlar ve görüntemler oluşturun. Bu şekilde karar verme yeteneklerini güçlendirebilirsiniz.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}