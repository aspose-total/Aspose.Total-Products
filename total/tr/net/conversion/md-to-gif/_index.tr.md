---
title: MD'yi GIF'ye Dışa Aktarmak için C# API'si
description: Microsoft Word kullanmadan MD'yi GIF'ye dönüştürün
url_ignore: /tr/net/conversion/md-to-gif/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: GIF
otherformats: PCL XAMLFLOW PS ODT FLATOPC OTT RTF WORDML DOTM GIF DOT MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MD'yi .NET üzerinden GIF'ye işleyin" h2="Microsoft Word kullanmadan Windows, macOS ve Linux'ta MD'yi GIF'ye Dışa Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/), .NET uygulamanızın içine belge işleme ve dönüştürme özellikleri eklemek için güçlü bir API'dir. Gelişmiş PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak, MD dosya biçimini DOC'a dönüştürebilirsiniz. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOC'yi GIF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi GIF'ye Dönüştürmek için C# API'si" %}}
1. [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak MD dosyasını açın
2. [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak MD'yi Dokümana dönüştürün
3. Aspose.Words'ün [Document](https://reference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak Doc dosyasını yükleyin
4. [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak dokümanı GIF formatına kaydedin ve Gif'i SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.gif", SaveFormat.Gif);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla Sahip Parolasını kullanarak MD Dosyasının Şifresini Çözme" %}}[Document]
MD'yi GIF'ye dönüştürmeden önce, belgenizin şifresini çözmek istiyorsanız bunu API'yi kullanarak yapabilirsiniz. PDF dosyasının şifresini çözmek için önce bir [Belge](https://reference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturmanız ve sahibinin parolasını kullanarak MD'yi açmanız gerekir. Bundan sonra Document nesnesinin [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) yöntemini çağırmanız gerekir. Son olarak, Document nesnesinin Save yöntemini kullanarak güncellenen dosyayı kaydedin.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden ReadOnly GIF- Dosyası Oluşturun" %}}
GIF'nizi düzenlemeden korumak ve diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için API'yi kullanarak belgenin korumasını da ayarlayabilirsiniz. Bir belgeyi düzenleme yeteneğini sınırlayabilir ve onunla yalnızca belirli eylemlere izin verebilirsiniz. Bu, [Aspose.Words for .NET](https://products.aspose.com/words/net/) API kullanılarak yapılabilir. [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.gif", SaveFormat.Gif);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-ott/" name="MD İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-mhtml/" name="MD İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-wordml/" name="MD İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-dot/" name="MD İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-odt/" name="MD İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-rtf/" name="MD İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-ps/" name="MD İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-flatopc/" name="MD İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-pcl/" name="MD İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-markdown/" name="MD İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-xamlflow/" name="MD İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/md-to-dotx/" name="MD İle DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}