---
title: E-POSTA'yı EPUB'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EML'i EPUB'ye dönüştürün
url_ignore: /tr/net/conversion/eml-to-epub/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOCM PCL PNG JPEG TIFF FLATOPC MD DOTM PS DOT DOCX EMF DOC WORDML ODT TEXT EPUB SVG OTT DOTX GIF RTF PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EML'i .NET aracılığıyla EPUB'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EML'i EPUB'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EML to EPUB dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EML dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi EPUB'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i EPUB'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EML'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi EPUB formatına kaydedin ve Epub'yi SaveFormat olarak ayarlayın
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

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EML'i EPUB'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EML belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/eml) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile EPUB Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EML'den EPUB'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML Dosyasını Programatik Olarak EPUB'e Dönüştürme: Kullanım Örnekleri" %}}
Elektronik Posta Dosyaları (EML), metin tabanlı bilgi depolarında kullanılarak, kişisel yazışmalar ve iş birliği için ideal olarak tasarlanmıştır. Ancak, yapılandırılmış veri ve multimedya içeriği ile çalışan durumlarda, EPUB (Elektronik Yayın Formatları) formatları, dijital yayın ve dağıtım için esas hale gelir.

**Kullanım Durumları:**

- **Dijital Yayın:** EML dosyalarını etkileşimli digital yayınlar, dergi, magazin ve bültenler oluşturarak çeşitli cihazlarda erişilebilir hale getirmek için dönüştürmek.
  
- **E-kitap Oluşturma:** EPUB formatlarını kullanarak EML dosyalarını e-kitaplar haline dönüştürerek, e-okuyucular, tabletler ve cep telefonlarında okunacak şekilde hazırlamak.

- **Blog Yazısı Yayınlama:** EML dosyalarını yapılandırılmış bir formatta blog yazılarını yayınlamak için dönüştürmek, bulunabilirliği ve erişilebilirliği artırır.

- **Araştırma Makalesi Oluşturma:** EPUB formatlarını kullanarak EML dosyalarını araştırma makalesi haline dönüştürerek, kolayca paylaşılabilir ve cite edilebilir hale getirmek.

- **Belge İş Birliği:** EML dosyalarını paylaşılır ve editlenebilir belgeler oluşturarak iş birliği ve geri bildirimleri kolayca sağlamak için dönüştürmek.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}