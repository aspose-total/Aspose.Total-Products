---
title: Esporta EPUB in OTP tramite API C#
description: API .NET per convertire EPUB in OTP senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da EPUB a OTP tramite .NET" h2="API .NET per esportare EPUB in OTP su Windows, macOS e Linux senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando un pacchetto di potenti API di automazione del formato file [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente eseguire il rendering da EPUB a OTP in due semplici passaggi. Utilizzando l'API di elaborazione PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), è possibile trasformare il formato di file EPUB in PPTX. Successivamente, utilizzando l'API di elaborazione della presentazione [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire EPUB in OTP" %}}
1. Aprire il file EPUB utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti EPUB in PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file PPTX utilizzando la classe [Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato OTP utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e impostare `Otp` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP dal file EPUB tramite .NET" %}}
Durante la conversione da EPUB a OTP, potresti aver bisogno di ulteriori informazioni sui metadati XMP per dare priorità al processo di conversione batch. Ad esempio, puoi ottenere e ordinare i tuoi documenti di conversione in base alla data di creazione ed elaborare i documenti di conseguenza. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) consente di accedere ai metadati XMP di un file EPUB. Per ottenere i metadati di un file EPUB, puoi creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il file EPUB di input. Successivamente, puoi ottenere i metadati del file utilizzando la proprietà [Metadata](https://apiference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea file OTP di sola lettura tramite .NET" %}}
Utilizzando l'API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi migliorare ulteriormente le funzionalità della tua applicazione di conversione. Una delle funzionalità può essere quella di creare il file di output in sola lettura per aumentare la sicurezza. L'API ti consente di impostare il tuo file OTP su Sola lettura, il che significa che gli utenti (dopo aver aperto la presentazione) vedono la raccomandazione Sola lettura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EPUB a OTP mediante programación: casos de uso" %}}
I utilizzo il codice di lingua di Google per tradurre il testo in italiano:

I file di pubblicazione elettronica (E-book) vengono utilizzati per archiviare contenuti digitali, rendendoli ideali per la creazione di contenuti dinamici e esperienze interattive. Tuttavia, quando si lavora con dati offline, i file di testo diventano fondamentali per lo storico e l'archiviazione.

La conversione dei file E-book in file di testo offline è necessaria per rivelare la piena potenzialità delle capacità degli archivi e delle biblioteche. Questa conversione consente di:

**Casi d'uso:**

*   **Preservazione digitale**: Convertire i file E-book per creare archivi permanenti, garantendo che il contenuto digitale rimanga accessibile nel tempo.
*   **Lettura e condivisione offline**: Utilizzare i file di testo offline per distribuire il contenuto digitale senza dipendere dalla connessione internet, rendendoli ideali per le aree con limitata accessibilità o in situazioni in cui Wi-Fi è inesistente.
*   **Gestione delle biblioteche e l'organizzazione**: Convertire i file E-book per creare raccolte strutturate e organizzate di dati di testo, facilitando la ricerca, la categorizzazione e l'acquisizione di informazioni specifiche.
*   **Archiviazione digitale e restauro**: Utilizzare i file di testo offline per archiviare artefatti digitali e restaurare contenuti danneggiati, garantendo che l'informazione preziosa rimanga integra per le generazioni future.
*   **Creazione e editing di contenuto offline**: Convertire i file E-book per creare contenuto editabile senza dipendere dalla connessione internet, rendendoli ideali per gli autori, gli scrittori e i pubblicatori che devono lavorare in isolamento o con limitata accessibilità alle risorse online.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}