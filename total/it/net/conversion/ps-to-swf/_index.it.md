---
title: Esporta PS in SWF tramite API C#
description: API .NET per convertire PS in SWF senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: PPSM POTM OTP POWERPOINT PPS PPTM POT POTX XAML SWF PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da PS a SWF tramite .NET" h2="API .NET per esportare PS in SWF su Windows, macOS e Linux senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando un pacchetto di potenti API di automazione del formato file [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente eseguire il rendering da PS a SWF in due semplici passaggi. Utilizzando l'API di elaborazione PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), è possibile trasformare il formato di file PS in PPTX. Successivamente, utilizzando l'API di elaborazione della presentazione [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in SWF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire PS in SWF" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti PS in PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file PPTX utilizzando la classe [Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato SWF utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e impostare `Swf` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP dal file PS tramite .NET" %}}
Durante la conversione da PS a SWF, potresti aver bisogno di ulteriori informazioni sui metadati XMP per dare priorità al processo di conversione batch. Ad esempio, puoi ottenere e ordinare i tuoi documenti di conversione in base alla data di creazione ed elaborare i documenti di conseguenza. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) consente di accedere ai metadati XMP di un file PS. Per ottenere i metadati di un file PS, puoi creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il file PS di input. Successivamente, puoi ottenere i metadati del file utilizzando la proprietà [Metadata](https://apiference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file SWF di sola lettura tramite .NET" %}}
Utilizzando l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi migliorare ulteriormente le funzionalità della tua applicazione di conversione. Una delle funzionalità può essere quella di creare il file di output in sola lettura per aumentare la sicurezza. L'API ti consente di impostare il tuo file SWF su Sola lettura, il che significa che gli utenti (dopo aver aperto la presentazione) vedono la raccomandazione Sola lettura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.swf", SaveFormat.Swf);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a SWF mediante programación: casos de uso" %}}
**File di PS vengono utilizzati per archiviare informazioni relative ai documenti, rendendoli ideali per la creazione di documenti statici e grafici. Tuttavia, quando si lavora con contenuti multimediali interattivi, i file SWF (Formato Piccolo della Web) diventano essenziali per l'ascolto e la visualizzazione.

La conversione dei file PS in formati SWF è necessaria per sfruttare al meglio il tuo contenuto multimediale interattivo. Questa conversione consente di:

**Casi d'uso:**

*   **Contenuti di Apprendimento Interattivi**: Convertire i file PS per creare contenuti di apprendimento online attivi, tutorial e materiali educativi che possono essere giocati su vari dispositivi.
*   **Fragmenti di Film e Programmi TV Animati**: Utilizzare i file SWF per aggiungere interattività a clip di film e programmi TV, rendendole più coinvolgenti per gli spettatori.
*   **Asset E Effetti dei Giochi Video**: Convertire i file PS per creare asset interattivi dei giochi video, effetti e animazioni che migliorano l'esperienza di gioco.
*   **Applicazioni Web Interattive e Simulazioni**: Utilizzare i file SWF per costruire applicazioni web interattive, simulazioni e contenuti interattivi che offrono esperienze immersive.
*   **Contenuto delle App Mobili e Annonci**: Convertire i file PS per creare contenuto interattivo per le app mobili, ad anuncii e giochi che affascinano gli utenti in movimento.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}