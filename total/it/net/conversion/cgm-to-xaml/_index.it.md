---
title: Esporta CGM in XAML tramite API C#
description: API .NET per convertire CGM in XAML senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/cgm-to-xaml/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: XAML
otherformats: SWF POT PPTM OTP PPT XAML PPSX PPSM POTX POTM POWERPOINT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da CGM a XAML tramite .NET" h2="API .NET per esportare CGM in XAML su Windows, macOS e Linux senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando un pacchetto di potenti API di automazione del formato file [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente eseguire il rendering da CGM a XAML in due semplici passaggi. Utilizzando l'API di elaborazione PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), è possibile trasformare il formato di file CGM in PPTX. Successivamente, utilizzando l'API di elaborazione della presentazione [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire CGM in XAML" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti CGM in PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file PPTX utilizzando la classe [Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato XAML utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e impostare `Xaml` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP dal file CGM tramite .NET" %}}
Durante la conversione da CGM a XAML, potresti aver bisogno di ulteriori informazioni sui metadati XMP per dare priorità al processo di conversione batch. Ad esempio, puoi ottenere e ordinare i tuoi documenti di conversione in base alla data di creazione ed elaborare i documenti di conseguenza. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) consente di accedere ai metadati XMP di un file CGM. Per ottenere i metadati di un file CGM, puoi creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il file CGM di input. Successivamente, puoi ottenere i metadati del file utilizzando la proprietà [Metadata](https://apiference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file XAML di sola lettura tramite .NET" %}}
Utilizzando l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi migliorare ulteriormente le funzionalità della tua applicazione di conversione. Una delle funzionalità può essere quella di creare il file di output in sola lettura per aumentare la sicurezza. L'API ti consente di impostare il tuo file XAML su Sola lettura, il che significa che gli utenti (dopo aver aperto la presentazione) vedono la raccomandazione Sola lettura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a XAML mediante programación: casos de uso" %}}
Il convertire i file CGM in formati XAML è fondamentale per sbloccare la piena potenzialità delle tue capacità di progettazione dell'interfaccia utente.

La conversione dei file CGM in XAML è necessaria per sbloccare la piena potenzialità delle tue capacità di progettazione dell'interfaccia utente. Questa conversione consente a te:

**Casi d'uso:**

*   **Sviluppo di una biblioteca di componenti UI**: convertire i file CGM per creare una raccolta di componenti UI reutilizzabili, riducendo il tempo di sviluppo e migliorando la consistenza nelle applicazioni.
*   **Implementazione del sistema di design**: utilizzare XAML per visualizzare e implementare sistemi di design, garantendo un'esperienza utente coerente su diverse piattaforme.
*   **Prototipazione e test dell'utilizzo**: convertire i file CGM per creare prototipi interattivi e conduct test di utilizzo, informando le decisioni di progettazione e migliorando l'engagement utente globale.
*   **Ottimizzazione della fruibilità**: utilizzare XAML per analizzare e ottimizzare la fruibilità UI, assicurandosi che le applicazioni siano accessibili a tutti, indipendentemente dalla capacità.
*   **Design data-driven**: convertire i file CGM per creare design data-driven, usando l'analisi e il feedback utente per informare le decisioni di progettazione e migliorare gli outcome aziendali.

Nota: La traduzione è stata realizzata utilizzando il codice linguaggio Google Translate. Se hai bisogno di una traduzione di alta qualità, ti consiglio di considerare i servizi di traduzione professionale o di editare il testo per l'accuratezza e la fluidità.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}