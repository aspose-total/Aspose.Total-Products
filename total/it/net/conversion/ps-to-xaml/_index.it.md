---
title: Esporta PS in XAML tramite API C#
description: API .NET per convertire PS in XAML senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendering da PS a XAML tramite .NET" h2="API .NET per esportare PS in XAML su Windows, macOS e Linux senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando un pacchetto di potenti API di automazione del formato file [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente eseguire il rendering da PS a XAML in due semplici passaggi. Utilizzando l'API di elaborazione PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), è possibile trasformare il formato di file PS in PPTX. Successivamente, utilizzando l'API di elaborazione della presentazione [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET per convertire PS in XAML" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Converti PS in PPTX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Caricare il file PPTX utilizzando la classe [Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato XAML utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e impostare `Xaml` come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni metadati XMP dal file PS tramite .NET" %}}
Durante la conversione da PS a XAML, potresti aver bisogno di ulteriori informazioni sui metadati XMP per dare priorità al processo di conversione batch. Ad esempio, puoi ottenere e ordinare i tuoi documenti di conversione in base alla data di creazione ed elaborare i documenti di conseguenza. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) consente di accedere ai metadati XMP di un file PS. Per ottenere i metadati di un file PS, puoi creare un oggetto [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e aprire il file PS di input. Successivamente, puoi ottenere i metadati del file utilizzando la proprietà [Metadata](https://apiference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a XAML mediante programación: casos de uso" %}}
Il formato di documento portatile (Portable Document Format) viene utilizzato per archiviare le informazioni sulla grafica a vettore, rendendolo ideale per la creazione di grafiche statiche, loghi e illustrazioni. Tuttavia, quando si lavora con dati dinamici, il linguaggio di markup estensibile applicativo (XAML) diventa fondamentale per costruire interfaccia utente e applicazioni.

La conversione dei file PS in formati XAML è necessaria per attivare le capacità complete della tua capacità di sviluppo di applicazioni. Questa conversione consente di:

**Casi d'uso:**

*   **Sviluppo delle app mobili**: Convertire i file PS per creare app native mobili con un'interfaccia utente intuitiva, sfruttando il potere del linguaggio XAML per una esperienza utente senza macchiature.
*   **Sviluppo delle applicazioni desktop**: Utilizzare XAML per costruire applicazioni desktop robuste e scalabili, sfruttando le forze della lingua nei legami di dati, gli effetti animati e la tematizzazione.
*   **Librerie di componenti UI**: Convertire i file PS per creare componenti UI reutilizzabili, come pulsanti, campi di testo e menu, utilizzando XAML per un progetto efficiente e mantenibile.
*   ** Grafiche 3D e animazioni**: Utilizzare XAML per portare alle vita le grafiche 3D e le animazioni nelle tue applicazioni, combinando il potere delle grafiche a vettore con la flessibilità di un linguaggio di markup.
*   **Accessibilità e personalizzazione**: Convertire i file PS per creare elementi UI accessibili ed personalizzabili, garantendo che le tue applicazioni soddisfino le esigenze e preferenze dei vari utenti.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}