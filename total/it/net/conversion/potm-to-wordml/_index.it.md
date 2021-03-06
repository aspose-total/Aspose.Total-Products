---
title: Converti POTM in WORDML tramite C# .NET 
url: /it/net/conversion/potm-to-wordml/ 
description: Converti documenti PowerPoint in file wordml di Word con C#. Converti più file all'interno di ASP.NET o altre applicazioni .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti POTM in WORDML usando C#" h2="Crea app di conversione di documenti Microsoft PowerPoint POTM Presentation in Word WORDML su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="POTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/total/aspose_total-for-net.svg" apiHomeLink="https://products.aspose.com/total/family/" codeSamplesLink="https://github.com/aspose-total" liveDemosLink="" wordmlsLink="https://wordmls.aspose.com/total/net" installationsWordmlsLink="https://wordmls.aspose.com/total/net" nugetLink="https://www.nuget.org/packages/aspose.total" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/total/net" learnAsLink="https://wordmls.aspose.com/total/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire POTM in WORDML usando C#" %}}

Per automatizzare il processo di conversione batch di qualsiasi presentazione PowerPoint potm in file wordml di Word, utilizzeremo [Aspose.Slides for .NET](https://products.aspose.com/slides/net) e [Aspose.Words per .NET](https://products.aspose.com/words/net) API. Il primo è un'API di manipolazione della presentazione di PowerPoint che consente di creare o modificare diapositive di Microsoft PowerPoint. Considerando che quest'ultima è un'API di elaborazione testi per l'elaborazione o la manipolazione di documenti Microsoft Word. Entrambe le API fanno parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net). Puoi [scaricare](https://downloads.aspose.com/) direttamente da Nuget o utilizzare i seguenti comandi dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire POTM in WORDML tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aggiungi riferimento ad Aspose.Slides per .NET e Aspose.Words per .NET
1. Caricare la presentazione PowerPoint POTM utilizzando la classe [Aspose.Slides.Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
1. Salva il documento in [MemoryStream](https://wordmls.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0) Oggetto
1. Crea [Aspose.Words.Document](https://apiference.aspose.com/words/net/aspose.words/document) e inizializzalo con l'oggetto MemoryStream
1. Salvare il documento utilizzando [Aspose.Words.Document.Save("output.wordml", SaveFormat.Wordml)](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/3)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Slides per .NET e Aspose.Words per .NET DLL a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo esempio di codice mostra come convertire un POTM in WORDML usando C#" offSpacer="" %}}

```cs
// Load the Microsoft PowerPoint POTM file
Aspose.Slides.Presentation potm = new Aspose.Slides.Presentation("source.potm");

var stream = new MemoryStream();

potm.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Load the content of the presentation to a Word document
var wordml = new Aspose.Words.Document(stream);
      
// Save the Word WORDML document
wordml.Save("output.wordml", Aspose.Words.SaveFormat.Wordml);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire POTM in WORDML" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant POTM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-wordml" name="POTM Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-docx" name="POTM Per DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-rtf" name="POTM Per RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-dot" name="POTM Per DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-dotx" name="POTM Per DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-dotm" name="POTM Per DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-docm" name="POTM Per DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-flatopc" name="POTM Per FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-odt" name="POTM Per ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-ott" name="POTM Per OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-wordml" name="POTM Per WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/potm-to-txt" name="POTM Per TXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}