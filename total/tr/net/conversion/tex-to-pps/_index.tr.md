---
title: TEX'yi C# API aracılığıyla PPS'ye aktarın
description: Microsoft Word kullanmadan TEX'yi PPS'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/tex-to-pps/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: PPS
otherformats: PPSX POWERPOINT XAML POTX PPTM POTM PPSM PPT POT PPS OTP SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEX'yi .NET üzerinden PPS'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta TEX'yi PPS'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak TEX'yi iki basit adımda PPS'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak TEX dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i PPS'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX'yi PPS'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak TEX dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak TEX'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi PPS formatına kaydedin ve 'Pps'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.tex");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pps", SaveFormat.Pps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla TEX Dosyasından XMP Meta Verilerini Alın" %}}[Document]
TEX'yi PPS'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir TEX dosyasının XMP meta verilerine erişmenizi sağlar. Bir TEX dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi TEX dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.tex");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur PPS Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, PPS dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pps", SaveFormat.Pps);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-pot/" name="TEX İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ppsx/" name="TEX İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-swf/" name="TEX İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-powerpoint/" name="TEX İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-otp/" name="TEX İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-potm/" name="TEX İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ppt/" name="TEX İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-pps/" name="TEX İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-potx/" name="TEX İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-xaml/" name="TEX İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ppsm/" name="TEX İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-pptm/" name="TEX İle PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}