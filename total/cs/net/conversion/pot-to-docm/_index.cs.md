---
title: Převést POT na DOCM přes C# .NET 
url: /cs/net/conversion/pot-to-docm/ 
description: Převádějte dokumenty pot aplikace PowerPoint na soubory dokumentů Word pomocí C#. Převeďte více souborů v rámci ASP.NET nebo jiných aplikací .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Převést POT na DOCM pomocí C#" h2="Vytvářejte aplikace Microsoft PowerPoint POT Presentation do aplikací pro převod dokumentů Word DOCM na platformách .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docmsLink="https://docms.aspose.com/total/net" installationsDocmsLink="https://docms.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docms.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak převést POT na DOCM pomocí C#" %}}

Abychom zautomatizovali proces jakékoli prezentace pot v PowerPointu na dávkovou konverzi souborů dokumentů aplikace Word, použijeme [Aspose.Slides for .NET](https://products.aspose.com/slides/net) a [Aspose.Words pro .NET](https://products.aspose.com/words/net) API. První z nich je rozhraní API pro manipulaci s prezentacemi aplikace PowerPoint, které umožňuje vytvářet nebo upravovat snímky aplikace Microsoft PowerPoint. Zatímco druhý je rozhraním pro zpracování textu pro zpracování nebo manipulaci s dokumenty Microsoft Word. Obě rozhraní API jsou součástí balíčku [Aspose.Total for .NET](https://products.aspose.com/total/net). Můžete přímo [stáhnout](https://downloads.aspose.com/) z Nuget nebo můžete použít následující příkazy z konzoly Správce balíčků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly Správce balíčků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro převod POT na DOCM přes C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Přidejte odkaz na Aspose.Slides pro .NET a Aspose.Words pro .NET
1. Načtěte prezentaci PowerPoint POT pomocí třídy [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Uložte dokument do [MemoryStream](https://docms.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Objekt
1. Vytvořte [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) a inicializujte jej pomocí objektu MemoryStream
1. Uložte dokument pomocí [Aspose.Words.Document.Save("output.docm", SaveFormat.Docm)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows nebo kompatibilní OS s platformami .NET Framework, .NET Core, Windows Azure, Mono nebo Xamarin.
- Vývojové prostředí jako Microsoft Visual Studio.
- Aspose.Slides pro .NET a Aspose.Words pro .NET DLL odkazované ve vašem projektu.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Tato ukázka kódu ukazuje, jak převést POT na DOCM pomocí C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POT file
Aspose.Slides.Presentation pot = new Aspose.Slides.Presentation("source.pot");

var stream = new MemoryStream();

pot.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var docm = new Aspose.Words.Document(stream);
      
// Save the Word DOCM document
docm.Save("output.docm", Aspose.Words.SaveFormat.Docm);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezplatná aplikace pro převod POT na DOCM" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POT file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další ppotorované konverze" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-docm" name="POT Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-docx" name="POT Na DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-rtf" name="POT Na RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-dot" name="POT Na DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-dotx" name="POT Na DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-dotm" name="POT Na DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-docm" name="POT Na DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-flatopc" name="POT Na FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-odt" name="POT Na ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-ott" name="POT Na OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-wordml" name="POT Na WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/pot-to-txt" name="POT Na TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}