---
title: Converti MD in JPEG2000 tramite API C#
description: Esporta MD in JPEG2000 nelle tue applicazioni .NET senza utilizzare applicazioni di terze parti
url_ignore: /it/net/conversion/md-to-jpeg2000/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: JPEG2000
otherformats: WMF EMZ  DXF JPEG2000 WMZ TGA IMAGE SVGZ PSD DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti file MD in JPEG2000 tramite C#" h2="Esporta MD in JPEG2000 all'interno di applicazioni .NET senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader o altre applicazioni di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi facilmente esportare un'immagine MD in JPEG2000 all'interno di qualsiasi applicazione .NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), puoi esportare MD in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), è possibile convertire JPEG in JPEG2000.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti file MD in JPEG2000 tramite .NET" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
2. Inizializzare l'oggetto classe [JpegDevice](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering di MD in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato JPEG2000 utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converti file MD in JPEG2000 in un singolo file tramite C#" %}}
Utilizzando l'API, puoi anche convertire il file MD in JPEG2000 in un singolo file immagine. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento MD in un file TIFF e successivamente puoi esportare il file TIFF in JPEG2000. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. È possibile ottenere una singola immagine TIFF utilizzando il metodo [Process](https://apiference.aspose.com/pdf/net/aspose.pdf.devices.documentdevice/process/methods/3) di [TiffDevice](https://reference.aspose.com/pdf/net/aspose.pdf.devices/tiffdevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
e salvalo in formato JPEG2000 usando il metodo [Save](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-single-file.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti e ruota il file MD in JPEG2000 tramite C#" %}}
Utilizzando l'API, puoi anche ruotare l'immagine JPEG2000 di output secondo le tue esigenze. Il metodo Image.RotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine è possibile caricare l'immagine JPEG convertita utilizzando il metodo di fabbrica esposto dalla classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e chiamare l'immagine .RotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/net/aspose.imaging/rotatefliptype). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-and-rotate-pdf-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}