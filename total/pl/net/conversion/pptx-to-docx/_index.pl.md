---
title: Konwertuj PPTX na DOCX przez C# .NET 
url: /pl/net/conversion/pptx-to-docx/ 
description: Konwertuj dokumenty pptx programu PowerPoint na pliki docx programu Word za pomocą C#. Konwertuj wiele plików w ASP.NET lub innych aplikacjach .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj PPTX na DOCX za pomocą C#" h2="Twórz aplikacje Microsoft PowerPoint PPTX Presentation do Word DOCX do konwersji dokumentów na platformach .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTX" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" docxsLink="https://docxs.aspose.com/total/net" installationsDocxsLink="https://docxs.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://docxs.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować PPTX na DOCX za pomocą C#" %}}

Aby zautomatyzować proces konwersji wsadowej dowolnej prezentacji PowerPoint pptx na pliki docx programu Word , użyjemy [Aspose.Slides for .NET](https://products.aspose.com/slides/net) i [Aspose.Words dla .NET](https://products.aspose.com/words/net) API. Pierwszy z nich to interfejs API do manipulacji prezentacjami programu PowerPoint, który umożliwia tworzenie lub modyfikowanie slajdów programu Microsoft PowerPoint. Natomiast ten ostatni jest interfejsem API do przetwarzania tekstu do przetwarzania lub manipulowania dokumentami Microsoft Word. Oba interfejsy API są częścią pakietu [Aspose.Total for .NET](https://products.aspose.com/total/net). Możesz bezpośrednio [pobrać](https://downloads.aspose.com/) z Nuget lub użyć następujących poleceń z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować PPTX na DOCX za pomocą C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Dodaj odwołanie do Aspose.Slides dla .NET i Aspose.Words dla .NET
1. Załaduj prezentację PowerPoint PPTX za pomocą klasy [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation)
1. Zapisz dokument w obiekcie [MemoryStream](https://docxs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0)
1. Utwórz [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) i zainicjuj go za pomocą obiektu MemoryStream
1. Zapisz dokument za pomocą [Aspose.Words.Document.Save("output.docx", SaveFormat.Docx)](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z platformami .NET Framework, .NET Core, Windows Azure, Mono lub Xamarin.
- Środowisko programistyczne, takie jak Microsoft Visual Studio.
- Aspose.Slides dla platformy .NET i Aspose.Words dla biblioteki DLL platformy .NET, do której odwołuje się projekt.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje, jak przekonwertować plik PPTX na DOCX przy użyciu C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint PPTX file
Aspose.Slides.Presentation pptx = new Aspose.Slides.Presentation("source.pptx");

var stream = new MemoryStream();

pptx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var docx = new Aspose.Words.Document(stream);
      
// Save the Word DOCX document
docx.Save("output.docx", Aspose.Words.SaveFormat.Docx);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do konwersji PPTX na DOCX" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTX file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-docx" name="PPTX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-docx" name="PPTX Do DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-rtf" name="PPTX Do RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-dot" name="PPTX Do DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-dotx" name="PPTX Do DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-dotm" name="PPTX Do DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-docm" name="PPTX Do DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-flatopc" name="PPTX Do FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-odt" name="PPTX Do ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-ott" name="PPTX Do OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-wordml" name="PPTX Do WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/pptx-to-txt" name="PPTX Do TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}