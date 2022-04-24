---
title: TEX'yi RTF'ye Dışa Aktarmak için C# API'si
description: Microsoft Word kullanmadan TEX'yi RTF'ye dönüştürün
url: /tr/net/conversion/tex-to-rtf/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: RTF
otherformats: DOTM OTT MHTML ODT RTF PCL DOT FLATOPC DOTX PS WORDML MARKDOWN
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEX'yi .NET üzerinden RTF'ye işleyin" h2="Microsoft Word kullanmadan Windows, macOS ve Linux'ta TEX'yi RTF'ye Dışa Aktarmak için .NET API" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/), .NET uygulamanızın içine belge işleme ve dönüştürme özellikleri eklemek için güçlü bir API'dir. Gelişmiş PDF İşleme API'sini [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) kullanarak, TEX dosya biçimini DOC'a dönüştürebilirsiniz. Bundan sonra, güçlü Belge İşleme API'sini [Aspose.Words for .NET](https://products.aspose.com/words/net/) kullanarak DOC'yi RTF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TEX'yi RTF'ye Dönüştürmek için C# API'si" %}}
1. [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) sınıfını kullanarak TEX dosyasını açın
2. [Kaydet](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) yöntemini kullanarak TEX'yi Dokümana dönüştürün
3. Aspose.Words'ün [Document](https://apireference.aspose.com/words/net/aspose.words/document) sınıfını kullanarak Doc dosyasını yükleyin
4. [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) yöntemini kullanarak dokümanı RTF formatına kaydedin ve Rtf'i SaveFormat olarak ayarlayın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Komut satırından ```nuget install Aspose.Total``` veya Visual Studio'nun Paket Yönetici Konsolu üzerinden ```Install-Package Aspose.Total`` ile kurun.

Alternatif olarak, çevrimdışı MSI yükleyicisini veya DLL'leri [indirilenler](https://downloads.aspose.com/total/net) adresinden bir ZIP dosyasında alın.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.rtf", SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2=".NET aracılığıyla Sahip Parolasını kullanarak TEX Dosyasının Şifresini Çözme" %}}
TEX'yi RTF'ye dönüştürmeden önce, belgenizin şifresini çözmek istiyorsanız bunu API'yi kullanarak yapabilirsiniz. PDF dosyasının şifresini çözmek için önce bir [Belge](https://apireference.aspose.com/pdf/net/aspose.pdf/document) nesnesi oluşturmanız ve sahibinin parolasını kullanarak TEX'yi açmanız gerekir. Bundan sonra Document nesnesinin [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) yöntemini çağırmanız gerekir. Son olarak, Document nesnesinin Save yöntemini kullanarak güncellenen dosyayı kaydedin.  
{{% blocks/products/pf/feature-page-code %}}
```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=".NET üzerinden ReadOnly RTF- Dosyası Oluşturun" %}}
RTF'nizi düzenlemeden korumak ve diğer kişilerin belgenizdeki hassas ve gizli bilgileri düzenlemesini önlemek için API'yi kullanarak belgenin korumasını da ayarlayabilirsiniz. Bir belgeyi düzenleme yeteneğini sınırlayabilir ve onunla yalnızca belirli eylemlere izin verebilirsiniz. Bu, [Aspose.Words for .NET](https://products.aspose.com/words/net/) API kullanılarak yapılabilir. [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) numaralandırma parametresini kullanarak içeriği kısıtlama şeklinizi kontrol etmenizi sağlar. Aşağıdaki kod satırlarını kullanarak belgenizi salt okunur olarak ayarlayabilirsiniz. 
```cs
```cs
Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ott/" name="TEX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-mhtml/" name="TEX İle MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-wordml/" name="TEX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dot/" name="TEX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-odt/" name="TEX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-rtf/" name="TEX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-ps/" name="TEX İle PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-flatopc/" name="TEX İle FLAİlePC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-pcl/" name="TEX İle PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-markdown/" name="TEX İle MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-xamlflow/" name="TEX İle XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/tex-to-dotx/" name="TEX İle DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}