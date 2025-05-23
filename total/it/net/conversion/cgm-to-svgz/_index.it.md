---
title: Converti CGM in SVGZ tramite API C#
description: Esporta CGM in SVGZ nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url_ignore: /it/net/conversion/cgm-to-svgz/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: SVGZ
otherformats: TGA JPEG2000 IMAGE SVGZ WMF  WMZ PSD EMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file CGM in SVGZ tramite C#" h2="Esporta CGM in SVGZ all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine CGM in SVGZ all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare CGM in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in SVGZ.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file CGM in SVGZ tramite .NET" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di CGM in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato SVGZ utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti file CGM in SVGZ in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file CGM in SVGZ in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento CGM in un file TIFF e successivamente puoi esportare il file TIFF in SVGZ. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato SVGZ usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file CGM in SVGZ tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine SVGZ di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a SVGZ mediante programación: casos de uso" %}}
Ili utilizzare i file CGM (Metafile per Grafica Computer) per archiviare le informazioni relative alle grafiche a forma di vettore, rendendoli ideali per la creazione di grafiche statiche e illustrazioni. Tuttavia, quando si lavora con dati dinamici, i fogli di calcolo come Excel diventano fondamentali per la visualizzazione e l'analisi dei dati.

La conversione dei file CGM in formati SVGZ è necessaria per sfruttare appieno le capacità delle grafiche a forma di vettore e delle illustrazioni. Questa conversione consente di:

**Casi d'uso:**

*   **Creazione di Grafiche Statiche**: Convertire i file CGM per creare grafiche statiche di alta qualità, illustrazioni e loghi ideali per l'imprenta o il web.
*   **Design delle Identità delle Marche**: Utilizzare SVGZ per progettare identità marchiali, icone e grafiche che sono scalabili e mantengono la loro qualità anche quando vengono risize.
*   **Design del Pacchetto e della Etichetta**: Convertire i file CGM per creare disegni di pacchetti e etichette visivamente accattivanti che si distinguono sui scaffali delle bancarelle commerciali.
*   **Gestione degli Asset Digitali**: Archiviare i file CGM in formato SVGZ per la gestione efficiente degli asset digitali, permettendo l'accesso facile e la condivisione di grafiche a forma di vettore tra team.
*   **Ottimizzazione delle Grafiche per Web e Smartphone**: Utilizzare SVGZ per ottimizzare i file CGM per dispositivi web e smartphone, garantendo tempi di caricamento veloci e qualità visiva elevata.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}