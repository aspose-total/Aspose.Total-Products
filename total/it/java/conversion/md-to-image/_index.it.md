---
title: Converti MD in IMAGE tramite Java
description: Esporta file MD in IMAGE nelle tue applicazioni Java senza utilizzare applicazioni di terze parti
url_ignore: /it/java/conversion/md-to-image/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: JPEG2000
otherformats: PSD JPEG2000 WMF EMZ SVGZ DXF TGA IMAGE WMZ DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti MD in IMAGE tramite Java" h2="Esporta file MD in IMAGE all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire il file md in un'immagine IMAGE in Java in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare MD in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), è possibile eseguire il rendering di JPEG in IMAGE. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Esporta MD in IMAGE tramite Java" %}}
1. Aprire il file MD utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inizializzare l'oggetto classe ed eseguire il rendering di MD in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-).
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salvare il documento in formato IMAGE utilizzando [save](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converti MD in IMAGE in un singolo file tramite Java" %}}
L'API consente inoltre di esportare file MD in IMAGE in un unico file. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento MD in un file TIFF e, successivamente, puoi esportare il file TIFF in IMAGE. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. Puoi ottenere una singola immagine TIFF utilizzando [process](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metodo della classe [TiffDevice](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image) e salvarlo in formato IMAGE usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti MD in IMAGE con Watermark tramite Java" %}}
Utilizzando l'API, puoi anche esportare file MD in IMAGE con filigrana nel documento IMAGE. Per aggiungere una filigrana, puoi prima convertire MD in JPEG e aggiungere una filigrana. Per aggiungere una filigrana, caricare un file immagine utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image), creare un oggetto di [Graphics](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inizializzarlo con l'oggetto Image, creare una nuova [Matrix](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e imposta la traduzione e la trasformazione all'angolo desiderato e aggiungi la filigrana usando [Graphics.drawString](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Dopo aver aggiunto la filigrana all'immagine, puoi salvare il JPEG come formato IMAGE. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti e ruota MD in file IMAGE tramite Java" %}}
Utilizzando l'API, puoi anche ruotare l'immagine IMAGE di output secondo le tue esigenze. Il metodo Image.rotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. La libreria fornisce metodi semplici per eseguire operazioni complesse mentre incapsula tutti i dettagli brutti. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine, è possibile caricare l'immagine JPEG convertita utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image) e chiamare l'immagine. rotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre opzioni di conversione" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-emz/" name="MD A EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-tga/" name="MD A TGA" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-jpeg2000/" name="MD A JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-image/" name="MD A IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-psd/" name="MD A PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-wmz/" name="MD A WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-svgz/" name="MD A SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to/" name="MD A" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-wmf/" name="MD A WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-dxf/" name="MD A DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/net/conversion/md-to-dicom/" name="MD A DICOM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}