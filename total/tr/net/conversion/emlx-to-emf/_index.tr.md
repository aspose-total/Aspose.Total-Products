---
title: E-POSTA'yı EMF'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EMLX'i EMF'ye dönüştürün
url_ignore: /tr/net/conversion/emlx-to-emf/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EMF
otherformats: PS PNG XPS OTT DOC DOCM MD TIFF DOT DOCX TEXT JPEG DOTX PDF RTF GIF FLATOPC EMF WORDML ODT DOTM SVG PCL EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMLX'i .NET aracılığıyla EMF'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EMLX'i EMF'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EMLX to EMF dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EMLX dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi EMF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMLX'i EMF'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) sınıfını kullanarak EMLX dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EMLX'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi EMF formatına kaydedin ve Emf'yi SaveFormat olarak ayarlayın
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

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EMLX'i EMF'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EMLX belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/email) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile EMF Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EMLX'den EMF'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMLX Dosyasını Programatik Olarak EMF'e Dönüştürme: Kullanım Örnekleri" %}}
EMF (Enhanced Metafile) dosyası raster grafik bilgilerini kaydetmek için kullanılır ve statik resimler oluşturmak için idealdir. Ancak dinamik veri işlemleri sırasında tablolar gibi spreadsheet programları, özellikle Excel, veri vizualizasyonu ve analizi yapmak için vazgeçilmez hale gelir.

EMF dosyalarının Excel formatına çevirmek, verilerinize tam potansiyali açmak için zorunludur. Bu çevirme, aşağıdaki işlevleri yapmanıza sağlar:

**Kullanım Durumları:**

- **Resim İşleme**: EMF dosyalarını resimler için edit etmek, metin eklemek ve şekil eklemek gibi işlemler yapmak için kullanabilirsiniz.
- **Grafiksel Kullanıcı Arayüzü (GUI) Tasarımı**: Excel kullanarak interaktif GUI öğeleri, seperti butonlar, menüler ve grafikler tasarlamak için kullanabilirsiniz.
- **Teknik Çizimler ve Belgeleme**: EMF dosyalarını teknik çizimler, mühendislik projelerini destekleyen blueprints ve belgeler oluşturmak için kullanabilirsiniz.
- **Bilimsel İllüstrasyon**: Bilimsel verileri kullanarak grafikler, diyagramlar gibi illüstrasyonlar oluşturmak için Excel'i kullanabilirsiniz.
- **Elektronik Sanat ve Grafik**: EMF dosyalarını dijital sanat eserleri, grafikler ve desenler oluşturmak için pixel manipülasyonu teknikleriyle kullanabilirsiniz.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}