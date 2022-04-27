---
title: Converti PDF in IMAGE tramite API C#
description: Esporta PDF in IMAGE nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url: /it/net/conversion/pdf-to-image/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: JPEG2000
otherformats: JPEG2000 EMZ  WMZ TGA PSD DXF WMF SVGZ IMAGE DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file PDF in IMAGE tramite C#" h2="Esporta PDF in IMAGE all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine PDF in IMAGE all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare PDF in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file PDF in IMAGE tramite .NET" %}}
1. Aprire il file PDF utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di PDF in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato IMAGE utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti file PDF in IMAGE in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file PDF in IMAGE in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento PDF in un file TIFF e successivamente puoi esportare il file TIFF in IMAGE. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https:// apireference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato IMAGE usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file PDF in IMAGE tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine IMAGE di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-emz/" name="PDF A EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-tga/" name="PDF A TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-jpeg2000/" name="PDF A JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-image/" name="PDF A IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-psd/" name="PDF A PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-wmz/" name="PDF A WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-svgz/" name="PDF A SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to/" name="PDF A" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-wmf/" name="PDF A WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-dxf/" name="PDF A DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/pdf-to-dicom/" name="PDF A DICOM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}