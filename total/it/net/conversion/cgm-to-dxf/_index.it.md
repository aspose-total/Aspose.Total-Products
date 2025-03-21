---
title: Converti CGM in DXF tramite API C#
description: Esporta CGM in DXF nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url_ignore: /it/net/conversion/cgm-to-dxf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DXF
otherformats: WMF PSD DXF  JPEG2000 SVGZ EMZ WMZ IMAGE TGA DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file CGM in DXF tramite C#" h2="Esporta CGM in DXF all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine CGM in DXF all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare CGM in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in DXF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file CGM in DXF tramite .NET" %}}
1. Aprire il file CGM utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di CGM in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato DXF utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti file CGM in DXF in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file CGM in DXF in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento CGM in un file TIFF e successivamente puoi esportare il file TIFF in DXF. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato DXF usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file CGM in DXF tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine DXF di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos CGM a DXF mediante programación: casos de uso" %}}
Utilizzare file CGM (Graphic Metafile Computer) per convertire i file DXF (Formatto di scambio Disegno) è fondamentale per sfruttare al meglio le capacità del tuo design CAD e delle tue competenze manifatturiere. Questa conversione consente a te:

**Casi d'uso:**

*   **Integrazione con il software di progettazioneCAD**: convertire file CGM in modo da poter integrare con il software CAD, consentendo collaborazioni di progetto senza problemi e scambi dati efficienti.
*   **Ottimizzazione dei processi di produzione**: utilizzare i file DXF per ottimizzare i processi di produzione, ridurre costi di produzione e migliorare la qualità dei prodotti.
*   **Design for Manufacturability (DFM)**: convertire file CGM in modo da creare disegni DFM, tenendo conto fattori come proprietà dei materiali, richieste del materiale e vincoli di montaggio.
*   **Comunicazione con le macchine CNC**: utilizzare i file DXF per scambiare dati di progettazione con le macchine CNC, garantendo tagli accurate e lavorazioni corrette dei pezzi.
*   **Sviluppo e test di prodotti**: convertire file CGM in modo da creare modelli prototipici, testare i disegni e valutare la funzionalità del prodotto prima dell'industria.

Nota: ho utilizzato lo stesso pattern descritto per la conversione della fonte formato :CGM->formato di target:Dxf
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}