---
title: Converti CGM in PSD tramite API C#
description: Esporta CGM in PSD nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url_ignore: /it/net/conversion/cgm-to-psd/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PSD
otherformats: IMAGE  JPEG2000 TGA WMF SVGZ PSD EMZ WMZ DXF DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file CGM in PSD tramite C#" h2="Esporta CGM in PSD all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine CGM in PSD all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare CGM in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file CGM in PSD tramite .NET" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di CGM in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato PSD utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti file CGM in PSD in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file CGM in PSD in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento CGM in un file TIFF e successivamente puoi esportare il file TIFF in PSD. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato PSD usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file CGM in PSD tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine PSD di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a PSD mediante programación: casos de uso" %}}
I'll translate the given text into Italian using Google Translate. 

File CMG (Metafile di Computer Graphics) vengono utilizzati per archiviare informazioni di grafica a vetri, rendendoli ideali per la creazione di grafiche statiche e illustrazioni.

Tuttavia, quando si lavora con dati dinamici, gli editori di immagini a raster come Photoshop diventano essenziali per visualizzare e editare le immagini.

La conversione dei file CMG in formati PSD è necessaria per sfruttare pienamente la tua capacità di progettazione grafica. Questa conversione ti consente di:

**Casi d'uso:**

*   **Design di logo**: Convertire file CMG per creare loghi scalabili a vetri che possono essere utilizzati su vari mezzi, come carte da visita, poster e siti web.
*   **Brand Identity and Consistency**: Utilizzare PSD per visualizzare le linee guida del marchio, creare identità visiva coerente e mantenere la consistenza visiva in tutti i materiali di marketing.
*   **Illustrazioni e Arte**: Convertire file CMG per creare illustrazioni complesse, editare arte a vetri e rifinire concetti di design.
*   **Design per stampa**: Utilizzare PSD per visualizzare le progettazioni di stampa, ottimizzare i layout e assicurarsi una buona qualità dell'output per varie applicazioni di stampa.
*   **Risorse di design grafica**: Convertire file CMG per creare risorse di design grafico editabili che possono essere riutilizzate su più progetti, economizzando tempo e fatica.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}