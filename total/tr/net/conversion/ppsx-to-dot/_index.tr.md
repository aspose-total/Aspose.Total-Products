---
title: PPSX'yi C# .NET aracılığıyla DOT'ye dönüştürün 
url: /tr/net/conversion/ppsx-to-dot/ 
description: PowerPoint ppsx belgelerini C# ile Word dot dosyalarına dönüştürün. ASP.NET veya diğer .NET uygulamaları içinde birden çok dosyayı dönüştürün.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="C# kullanarak PPSX'yi DOT'ye dönüştürün" h2=".NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformlarında Microsoft PowerPoint PPSX Sunumunu Word DOT belge dönüştürme uygulamalarına oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPSX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOTM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" dotsLink="https://dots.aspose.com/total/net" installationsDotsLink="https://dots.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://dots.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak PPSX'yi DOT'ye Dönüştürme" %}}

Herhangi bir PowerPoint ppsx sunumunun Word dot dosyalarına toplu dönüştürme işlemini otomatikleştirmek için, [Aspose.Slides for .NET](https://products.aspose.com/slides/net) ve [Aspose.Words'ü kullanacağız. .NET](https://products.aspose.com/words/net) API'leri için. İlki, Microsoft PowerPoint slaytları oluşturmanıza veya değiştirmenize izin veren bir PowerPoint sunum işleme API'sidir. İkincisi, Microsoft Word belgelerini işlemek veya işlemek için bir kelime işlem API'sidir. Her iki API de [Aspose.Total for .NET](https://products.aspose.com/total/net) paketinin bir parçasıdır. Nuget'ten doğrudan [indirebilir](https://downloads.aspose.com/) veya Paket Yöneticisi Konsolundan aşağıdaki komutları kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PPSX'yi DOT'ye C# ile Dönüştürme Adımları" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aspose.Slides for .NET ve Aspose.Words for .NET referanslarını ekleyin
1. [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) sınıfını kullanarak PowerPoint PPSX sunumunu yükleyin
1. Belgeyi [MemoryStream](https://dots.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Nesnesine kaydedin
1. [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) oluşturun ve bunu MemoryStream Object ile başlatın
1. Belgeyi [Aspose.Words.Document.Save("output.dot", SaveFormat.Dot)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods) kullanarak kaydedin /3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Windows Azure, Mono veya Xamarin Platformları ile uyumlu bir işletim sistemi.
- Microsoft Visual Studio gibi geliştirme ortamı.
- Projenizde referans verilen Aspose.Slides for .NET ve Aspose.Words for .NET DLL.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Bu kod örneği, C# kullanarak bir PPSX'nin DOT'ye nasıl dönüştürüleceğini gösterir." offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPSX file
Aspose.Slides.Presentation ppsx = new Aspose.Slides.Presentation("source.ppsx");

var stream = new MemoryStream();

ppsx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var dot = new Aspose.Words.Document(stream);
      
// Save the Word DOT document
dot.Save("output.dot", Aspose.Words.SaveFormat.Dot);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="PPSX'yi DOT'ye Dönüştürmek için Ücretsiz Uygulama" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOTM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPSX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Desteklenen Diğer Dönüşümler" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dot" name="PPSX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotx" name="PPSX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-rtf" name="PPSX İle RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dot" name="PPSX İle DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotx" name="PPSX İle DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotm" name="PPSX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-dotm" name="PPSX İle DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-flatopc" name="PPSX İle FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-odt" name="PPSX İle ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-ott" name="PPSX İle OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-wordml" name="PPSX İle WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/ppsx-to-txt" name="PPSX İle TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}