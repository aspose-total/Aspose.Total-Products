---
title: E-POSTA'yı MD'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EML'i MD'ye dönüştürün
url_ignore: /tr/net/conversion/eml-to-md/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: MD
otherformats: MD RTF FLATOPC PS ODT DOCM DOTX EMF GIF XPS WORDML OTT DOCX TIFF PNG SVG TEXT JPEG EPUB DOC PCL DOT PDF DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EML'i .NET aracılığıyla MD'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EML'i MD'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EML to MD dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EML dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi MD'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EML'i MD'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) sınıfını kullanarak EML dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EML'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi MD formatına kaydedin ve Md'yi SaveFormat olarak ayarlayın
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

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EML'i MD'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EML belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/eml) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile MD Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EML'den MD'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EML Dosyasını Programatik Olarak MD'e Dönüştürme: Kullanım Örnekleri" %}}
E-posta Dosyaları (Electronic Mail - EML), metin tabanlı bilgi depoları oluşturmak için ideal bir araçtır. Bu dosyalarda basit e-postalar ve iletişim işlemleri için uygun şekilde kullanılabilmelerdir. Ancak karmaşık veri işlemleri ve görsel hale getirilen verilerin ele alınması durumunda, Documentation ve sunumlarda önemli bir rol oynayan Markdown (MD) formatları kullanılır hale gelir.

EML dosyalarının Markdown formatına çevirmesi, belgeleme yeteneklerinizi ve sunum kabiliyetinizi daha fazla açar. Bu conversion, aşağıdaki işlevleri sağlar:

**Kullanım Durumları:**

- **E-posta Belgeleme:** EML dosyalarını kullanarak okunabilir ve yapılandırılmış e-posta belgeleri oluşturmak için başlıklar, alt başlıklar ve içerikleri dahil olarak belgeyi hazırlayabilirsiniz.

- **Blog Yazımı Oluşturma:** Blog yazıları yazma ve formatlamayı kolaylaştıran Markdown kullanarak yazıcılar arasında kolay paylaşım ve iş birliği sağlar.

- **Teknik Yazıtlama:** Kullanıcı kitapları, rehberler ve talimatları清晰且简洁 bir şekilde oluşturmak için EML dosyalarını çevirmektedir.

- **Sosyal Medya Gönderileri:** Resimler, bağlantılar ve videolar gibi unsurları içeren sosyal medya gönderilerini formatlamak için Markdown kullanılır. Bu, daha iyi etkileşim ve görünürlik elde edilmesini sağlar.

- **Sunumlar ve Raporlar:** Interaktif sunumlar ve raporları oluşturmak için Markdown dilbilgisi kullanarak EML dosyalarını çevirmektedir. Bu, ortaklaştırma ve paylaşıma kolaylaştırarak stakeholderler arasında iş birliği sağlar.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}