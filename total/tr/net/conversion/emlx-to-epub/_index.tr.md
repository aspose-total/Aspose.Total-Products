---
title: E-POSTA'yı EPUB'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EMLX'i EPUB'ye dönüştürün
url_ignore: /tr/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMLX'i .NET aracılığıyla EPUB'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EMLX'i EPUB'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EMLX to EPUB dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EMLX dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi EPUB'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX'i EPUB'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) sınıfını kullanarak EMLX dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EMLX'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi EPUB formatına kaydedin ve Epub'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EMLX'i EPUB'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EMLX belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/email) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile EPUB Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EMLX'den EPUB'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX Dosyasını Programatik Olarak EPUB'e Dönüştürme: Kullanım Örnekleri" %}}
EMLX (Elektronik Posta X Tabanlı Başlıklarla Oluşturulmuş Dosyalar) dosyaları, elektronik posta bilgilerinin kaydedildiği ve statik邮件ler oluşturmak veya mesaj arşivleri oluşturmak için uygun olan bir formatı temsil eder. Ancak, dinamik içeriklerle çalışan durumlarda ise ePUB formatları dijital yayın ve online içerik dağıtımları için kritik öneme sahiptir.

EMLX dosyalarının ePUB formatına çevrilmesi, size dijital yayın ve online içerik dağıtım yeteneklerinizi tam olarak kullanmanıza yardımcı olur. Bu çevrimiçi yayınlama ve içerik dağıtıma imkan sağlayan aşağıdaki işlevleri sağlar:

**Kullanım Durumları:**

* **Dijital Yayın**: EMLX dosyalarını ePUB formatına çevirerek etkileşimli dijital dergiler, gazete ve kitaplar oluşturarak çeşitli cihazlarda erişilebilir hale getirirsiniz.  
* **Eğitim İçerikleri Çevirmek**: ePUB formatını kullanarak online kurslar, rehberler ve eğitim materyallerini yayınlayarak öğrencilerin ve profesyonel的人们'in öğrenme deneyimlerini güçlendirin.  
* **Çevrimiçi Makale Yayınları**: EMLX dosyalarını ePUB formatına çevirerek görsel olarak çekici makaleler, hikayeler ve blog yazıları oluşturarak online etkileşim ve okuma memnuniyetini artıran içerikler yayınlayabilirsiniz.  
* **Dijital Komik ve Romanlar**: ePUB formatını kullanarak dijital komik, romanlar ve diğer etkileşimli anlatımların korunmasını ve dağıtımını yaparak okurulara benzersiz bir okuma deneyimi sunun.  
* **Web Sitesi İçerik Syndication**: EMLX dosyalarını ePUB formatına çevirerek web sitelerinde yayınlanan yazılar, ürün açıklamaları ve müşteri gözlemleri gibi dinamik web içerikleri oluşturarak kullanıcı etkileşimini ve çevrimiçi dönüşüm oranını artırabilirsiniz.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}