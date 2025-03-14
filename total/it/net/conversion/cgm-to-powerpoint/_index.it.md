---
title: Esporta CGM in POWERPOINT tramite API C#
description: API .NET per convertire CGM in POWERPOINT senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/cgm-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: POWERPOINT
otherformats: OTP PPSM PPS XAML PPSX PPT POTX PPTM POWERPOINT POT POTM SWF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da CGM a POWERPOINT tramite .NET" h2="API .NET per esportare CGM in POWERPOINT su Windows, macOS e Linux senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando un pacchetto di potenti API di automazione del formato file [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente eseguire il rendering da CGM a POWERPOINT in due semplici passaggi. Utilizzando l'API di elaborazione PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), è possibile trasformare il formato di file CGM in PPTX. Successivamente, utilizzando l'API di elaborazione della presentazione [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in POWERPOINT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire CGM in POWERPOINT" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti CGM in PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file PPTX utilizzando la classe [Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato POWERPOINT utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e impostare `Powerpoint` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP dal file CGM tramite .NET" %}}
Durante la conversione da CGM a POWERPOINT, potresti aver bisogno di ulteriori informazioni sui metadati XMP per dare priorità al processo di conversione batch. Ad esempio, puoi ottenere e ordinare i tuoi documenti di conversione in base alla data di creazione ed elaborare i documenti di conseguenza. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) consente di accedere ai metadati XMP di un file CGM. Per ottenere i metadati di un file CGM, puoi creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il file CGM di input. Successivamente, puoi ottenere i metadati del file utilizzando la proprietà [Metadata](https://apiference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file POWERPOINT di sola lettura tramite .NET" %}}
Utilizzando l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi migliorare ulteriormente le funzionalità della tua applicazione di conversione. Una delle funzionalità può essere quella di creare il file di output in sola lettura per aumentare la sicurezza. L'API ti consente di impostare il tuo file POWERPOINT su Sola lettura, il che significa che gli utenti (dopo aver aperto la presentazione) vedono la raccomandazione Sola lettura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;
// call save method while passing SaveFormat.Ppt
presentation.Save("output.ppt", SaveFormat.Ppt);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a POWERPOINT mediante programación: casos de uso" %}}
La metafile dei grafici computer (CGM) vengono utilizzati per archiviare informazioni di grafiche a punti, rendendoli ideali per la creazione di grafiche statiche e illustrazioni.

Tuttavia, quando si lavora con dati dinamici, presentazioni come PowerPoint diventano essenziali per consegnare visualizzazioni coinvolgenti e storie.

La conversione dei file CGM in formati PowerPoint è necessaria per attivare la piena potenzialità delle tue capacità di presentazione. Questa conversione ti consente di:

**Uso del software:**

*   **Presentazioni corporate**: Converti i file CGM per creare presentazioni corporate coinvolgenti, trasmettere dati complessi e condividere risultati con gli stakeholder.
*   **Sviluppo dei materiali didattici**: Utilizza PowerPoint per visualizzare il contenuto di formazione, simulare scenari reali e fornire esperienze di apprendimento interattive.
*   **Creazione di materiali marketing**: Converti i file CGM per progettare visualmente attiranti materiali marketing come brochure, volantini e poster che catturano l'attenzione e stimolano l'engagement.
*   **Presentazioni scientifiche**: Utilizza PowerPoint per creare presentazioni interattive di ricerca, visualizzare dati complessi e comunicare risultati in modo efficace.
*   **Sviluppo di corsi online**: Converti i file CGM per creare corsi di formazione immersivi, utilizzare animazioni ed interazioni e migliorare l'engagement degli studenti.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}