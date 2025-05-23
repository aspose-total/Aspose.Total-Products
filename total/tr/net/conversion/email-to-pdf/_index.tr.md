---
title: E-POSTA'yı PDF'ye Dışa Aktarmak için C# API
description: .NET üzerinde Microsoft Word veya Outlook kullanmadan EMAIL'i PDF'ye dönüştürün
url_ignore: /tr/net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML PDF EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="EMAIL'i .NET aracılığıyla PDF'ye aktarın" h2="Windows, macOS ve Linux'ta Word veya Outlook kullanmadan EMAIL'i PDF'ye Oluşturmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Uygulamalarınızın içine EMAIL to PDF dönüştürme özelliklerini eklemek isteyen bir .NET geliştiricisiyseniz, [Aspose.Total for .NET](https://products.aspose.com/total/net/) dosya biçimi işleme API'leri doğru yoldur. ileri. [Aspose.Email for .NET](https://products.aspose.com/email/net/) kullanarak EMAIL dosya biçimini HTML'ye dönüştürebilirsiniz. Bundan sonra, [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak HTML'yi PDF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="EMAIL'i PDF'ye Dönüştürmek için C# API" %}}
1. [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) sınıfını kullanarak EMAIL dosyasını açın
2. [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) yöntemini kullanarak EMAIL'i HTML'ye dönüştürün
3. HTML'yi [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak belgeyi PDF formatına kaydedin ve Pdf'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="E-POSTA Dosyasını .NET ile Ayrıştırma" %}}
EMAIL'i PDF'ye dönüştürmeden önce, doğru e-postayı dönüştürdüğünüzden emin olmak istiyorsanız, EMAIL belgesini yükleyebilir, ayrıştırabilir ve istediğiniz özelliğe bir göz atabilirsiniz. [Aspose.Email for .NET](https://products.aspose.com/email) [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) sınıfını kullanarak /net/) API, gönderici ve alıcı bilgilerini alabilirsiniz. Örneğin, [GönderenAdı](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) özelliğini kullanarak dönüşüm için belirli bir gönderen e-postasını kontrol edebilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET ile PDF Belge Düzenlemesini Kısıtlayın" %}}
Belgeyi EMAIL'den PDF'ye kaydederken çıktı belgenizi korumanız gerekebilir. Bazen bir belgeyi düzenleme yeteneğini sınırlamanız ve onunla yalnızca belirli işlemlere izin vermeniz gerekebilir. Bu, diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için yararlı olabilir. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresi. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="EMAIL Dosyasını Programatik Olarak PDF'e Dönüştürme: Kullanım Örnekleri" %}}
E-posta dosyanızı PDF formatına çevirmek, belge yönetim yeteneklerinizi tam olarak kullanmanıza yardımcı olabilir. Bu çevrim, aşağıdaki kullanımlar için önemli bir adımdır:

**Kullanım Durumları:**

* **Resmi Belge ve Denetlenme:** E-posta dosyalarını PDF formatına çevirmek resmi belgeler oluşturmak, denetleme proseslerini kolaylaştırmak ve denetlenmeleri sağlamak için kullanılır.
  
* **Pazarlama Malzemeleri ve Kampaniyalar:** PDF çeviriyle print-ready pazarlama malzemeleri, broşürler ve kampaniyalar oluşturabilir ve marka imgenizi etkili bir şekilde sunabilirsiniz.

* **Eğitim ve Öğretme İçindeğı:** E-posta dosyalarını PDF formatına çevirmek etkileşimli eğitim kitapları, kurs malzemeleri ve öğrenci/dönemsel olarak kullanılan çalışma kitapları oluşturmayı sağlar.

* **İşProposalları ve Sözleşmeler:** Profesyonel görünüm sunmak için iş teklifleri, sözleşmeler ve anlaşmaları PDF formatında oluşturabilir.

* **Sanat ve Yaratıcı Proje:** E-posta dosyalarını PDF formatına çevirmek dijital sanat eserlerini, resimleri veya tasarıları korumak ve bunları basıncaya uygun hale getirmek için kullanılır.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}