---
title: CGM'yi C# API aracılığıyla POWERPOINT'ye aktarın
description: Microsoft Word kullanmadan CGM'yi POWERPOINT'ye dönüştürmek için .NET API
url_ignore: /tr/net/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPT
otherformats: OTP PPSM PPS XAML PPSX PPT POTX PPTM POWERPOINT POT POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM'yi .NET üzerinden POWERPOINT'ye işleyin" h2="Microsoft<sup>&reg;</sup> PowerPoint kullanmadan Windows, macOS ve Linux'ta CGM'yi POWERPOINT'ye Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Güçlü Dosya Formatı Otomasyonu API'leri [Aspose.Total for .NET](https://products.aspose.com/total/net/) paketini kullanarak CGM'yi iki basit adımda POWERPOINT'ye kolayca Render edebilirsiniz. PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak CGM dosya biçimini PPTX'e dönüştürebilirsiniz. Bundan sonra, Sunum İşleme API'sini [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) kullanarak PPTX'i POWERPOINT'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="CGM'yi POWERPOINT'ye Dönüştürmek için .NET API" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak CGM dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak CGM'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PPTX dosyasını yükleyin
4. [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) yöntemini kullanarak belgeyi POWERPOINT formatına kaydedin ve 'Powerpoint'yi SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://releases.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla CGM Dosyasından XMP Meta Verilerini Alın" %}}[Document]
CGM'yi POWERPOINT'ye dönüştürürken, toplu dönüştürme işleminize öncelik vermek için fazladan XMP meta veri bilgilerine ihtiyacınız olabilir. Örneğin, dönüştürme belgelerinizi oluşturulma tarihine göre alıp sıralayabilir ve belgeleri buna göre işleyebilirsiniz. [.NET için Aspose.PDF](https://products.aspose.com/pdf/net/) bir CGM dosyasının XMP meta verilerine erişmenizi sağlar. Bir CGM dosyasının meta verilerini almak için bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturabilir ve girdi CGM dosyasını açabilirsiniz. Bundan sonra, [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) özelliğini kullanarak dosyanın meta verilerini alabilirsiniz.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden Salt Okunur POWERPOINT Dosyası Oluşturun" %}}
[Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API'sini kullanarak dönüştürme uygulamanızın özelliklerini daha da geliştirebilirsiniz. Özelliklerden biri, güvenliği artırmak için çıktı dosyanızı salt okunur olarak oluşturmak olabilir. API, POWERPOINT dosyanızı Salt Okunur olarak ayarlamanıza olanak tanır; bu, kullanıcıların (sunuyu açtıktan sonra) Salt Okunur önerisini görmeleri anlamına gelir. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-pot/" name="CGM İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-ppsx/" name="CGM İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-swf/" name="CGM İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-powerpoint/" name="CGM İle POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-otp/" name="CGM İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-potm/" name="CGM İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-ppt/" name="CGM İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-pps/" name="CGM İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-potx/" name="CGM İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-xaml/" name="CGM İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-ppsm/" name="CGM İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/cgm-to-pptm/" name="CGM İle PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}