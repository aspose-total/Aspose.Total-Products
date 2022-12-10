---
title: MD'yi C# API aracılığıyla POTM'ye aktarın
description: Microsoft Word kullanmadan MD'yi POTM'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/md-to-potm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: POTM
otherformats: POTX PPTM PPSM PPS POWERPOINT POTM PPT PPSX SWF XAML OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MD'yi .NET üzerinden POTM'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta MD'yi POTM'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak MD'yi iki basit adımda POTM'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak MD dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i POTM'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi POTM'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak MD dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak MD'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi POTM formatına kaydedin ve 'Potm'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.md");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla MD Dosyasından XMP Meta Verilerini Alın" %}}[Document]
MD'yi POTM'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir MD dosyasının XMP meta verilerine erişmenizi sağlar. Bir MD dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi MD dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.md");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur POTM Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, POTM dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.potm", SaveFormat.Potm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-pot/" name="MD İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-ppsx/" name="MD İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-swf/" name="MD İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-powerpoint/" name="MD İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-otp/" name="MD İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-potm/" name="MD İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-ppt/" name="MD İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-pps/" name="MD İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-potx/" name="MD İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-xaml/" name="MD İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-ppsm/" name="MD İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-pptm/" name="MD İle PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}