---
title: Converti PS in PSD tramite API C#
description: Esporta PS in PSD nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url_ignore: /it/net/conversion/ps-to-psd/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PSD
otherformats: JPEG2000  WMZ EMZ PSD DXF TGA WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file PS in PSD tramite C#" h2="Esporta PS in PSD all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine PS in PSD all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare PS in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in PSD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file PS in PSD tramite .NET" %}}
1. Aprire il file PS utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di PS in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
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

{{% blocks/products/pf/feature-page-section  h2="Converti file PS in PSD in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file PS in PSD in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento PS in un file TIFF e successivamente puoi esportare il file TIFF in PSD. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato PSD usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file PS in PSD tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine PSD di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}