---
title: SVG'yi DOTX'ye Dışa Aktarmak için C# API'si
description: Microsoft Word kullanmadan SVG'yi DOTX'ye dönüştürün
url: /tr/net/conversion/svg-to-dotx/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: DOTX
otherformats: DOTM PS FLATOPC WORDML DOT MARKDOWN PCL XAMLFLOW MHTML ODT DOTX RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="SVG'yi .NET üzerinden DOTX'ye işleyin" h2="Microsoft Word kullanmadan Windows, macOS ve Linux'ta SVG'yi DOTX'ye Dışa Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/), .NET uygulamanızın içine belge işleme ve dönüştürme özellikleri eklemek için güçlü bir API'dir. Gelişmiş PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak, SVG dosya biçimini DOC'a dönüştürebilirsiniz. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOC'yi DOTX'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="SVG'yi DOTX'ye Dönüştürmek için C# API'si" %}}
1. [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak SVG dosyasını açın
2. [Kaydet](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak SVG'yi Dokümana dönüştürün
3. Aspose.Words'ün [Document](https://apireference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak Doc dosyasını yükleyin
4. [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak dokümanı DOTX formatına kaydedin ve Dotx'i SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.svg");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dotx", SaveFormat.Dotx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla Sahip Parolasını kullanarak SVG Dosyasının Şifresini Çözme" %}}
SVG'yi DOTX'ye dönüştürmeden önce, belgenizin şifresini çözmek istiyorsanız bunu API'yi kullanarak yapabilirsiniz. PDF dosyasının şifresini çözmek için önce bir [Belge](https://apireference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturmanız ve sahibinin parolasını kullanarak SVG'yi açmanız gerekir. Bundan sonra Document nesnesinin [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) yöntemini çağırmanız gerekir. Son olarak, Document nesnesinin Save yöntemini kullanarak güncellenen dosyayı kaydedin.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.svg", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden ReadOnly DOTX- Dosyası Oluşturun" %}}
DOTX'nizi düzenlemeden korumak ve diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için API'yi kullanarak belgenin korumasını da ayarlayabilirsiniz. Bir belgeyi düzenleme yeteneğini sınırlayabilir ve onunla yalnızca belirli eylemlere izin verebilirsiniz. Bu, [Aspose.Words for .NET](https://products.aspose.com/words/net/) API kullanılarak yapılabilir. [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
```cs
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-ott/" name="SVG İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-mhtml/" name="SVG İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-wordml/" name="SVG İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-dot/" name="SVG İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-odt/" name="SVG İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-rtf/" name="SVG İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-ps/" name="SVG İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-flatopc/" name="SVG İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-pcl/" name="SVG İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-markdown/" name="SVG İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-xamlflow/" name="SVG İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/svg-to-dotx/" name="SVG İle DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}