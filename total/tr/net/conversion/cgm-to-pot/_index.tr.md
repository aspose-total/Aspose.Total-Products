---
title: CGM'yi C# API aracılığıyla POT'ye aktarın
description: Microsoft Word kullanmadan CGM'yi POT'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/cgm-to-pot/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POT
otherformats: PPS POWERPOINT POTX PPT POT XAML OTP PPSX POTM PPSM SWF PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM'yi .NET üzerinden POT'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta CGM'yi POT'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak CGM'yi iki basit adımda POT'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i POT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi POT'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak CGM'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi POT formatına kaydedin ve 'Pot'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla CGM Dosyasından XMP Meta Verilerini Alın" %}}[Document]
CGM'yi POT'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir CGM dosyasının XMP meta verilerine erişmenizi sağlar. Bir CGM dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi CGM dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur POT Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, POT dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pot", SaveFormat.Pot);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM Dosyasını Programatik Olarak POT'e Dönüştürme: Kullanım Örnekleri" %}}
CGM (Computer Graphics Metafile) dosyalarını POT (Plain Old Text) formatına çevirmek, veri vizualizasyonu ve analizi için daha fazla potansiyel açığın açılmasını sağlar. Bu çeviri:

**Kullanma Örnekleri:**

- **Tarihsel Veri Analizi**: CGM dosyalarını tarihsel verileri analiz etmek, trendleri izlemek ve desenleri belirlemek için kullanma.
  
- **Dokümanterici Belge Oluşturma**: Kompleks CGM grafiklerini kullanarak geliştiriciler ve mühendisler için kolayca anlaşılır ve uygulayıcı bir belge oluşturma.

- **Erişilebilirlik Özelliklerinin Uygulaması**: CGM dosyalarını kullanıcıların engellilikleri olanlarla erişilebilir hale getirmek için imgeler ve alt metinler eklemek.

- **Sanatsal Ifade ve Tasarım**: Belirli tasarım öğelerini CGM dosyalarından çıkarmak, sanatçılar ve tasarımcılar için yeni yaratıcı projelerde yeniden kullanma imkanını sağlar.

- **Araştırma ve Geliştirme**: Araştırmacılara araştırma verileri vizualize etmek, deneyimleri simüle etmek ve hipotezlerini doğrulamak için CGM dosyalarını kullanma.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}
 

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}