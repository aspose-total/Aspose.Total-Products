---
title: Converti MHTML in PSD tramite Java
description: Esporta file MHTML in PSD nelle tue applicazioni Java senza utilizzare applicazioni di terze parti
url_ignore: /it/java/conversion/mhtml-to-psd/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PSD
otherformats: WMF WMZ TGA DXF EMZ  IMAGE PSD SVGZ JPEG2000 DICOM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti MHTML in PSD tramite Java" h2="Esporta file MHTML in PSD all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME senza utilizzare Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire il file mhtml in un'immagine PSD in Java in due semplici passaggi. Innanzitutto, utilizzando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), puoi esportare MHTML in JPEG. Successivamente, utilizzando l'API di elaborazione delle immagini [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), è possibile eseguire il rendering di JPEG in PSD. Entrambe le API rientrano nel pacchetto [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Esporta MHTML in PSD tramite Java" %}}
1. Aprire il file MHTML utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Inizializzare l'oggetto classe ed eseguire il rendering di MHTML in JPEG utilizzando [Process](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/JpegDevice#process-com.aspose.pdf.Page-java.io.OutputStream-).
3. Caricare il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salvare il documento in formato PSD utilizzando [save](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Converti MHTML in PSD in un singolo file tramite Java" %}}
L'API consente inoltre di esportare file MHTML in PSD in un unico file. Per convertire tutte le pagine, puoi prima eseguire il rendering del tuo documento MHTML in un file TIFF e, successivamente, puoi esportare il file TIFF in PSD. È possibile aprire il file di input utilizzando la classe [Document](https://apiference.aspose.com/pdf/java/com.aspose.pdf/Document) e creare oggetti dispositivo Resolution, TiffSettings e TIFF. Puoi ottenere una singola immagine TIFF utilizzando [process](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) metodo della classe [TiffDevice](https://apiference.aspose.com/pdf/java/com.aspose.pdf.devices/TiffDevice). Infine, puoi caricare il file TIFF usando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image) e salvarlo in formato PSD usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-).  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-single-file.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti MHTML in PSD con Watermark tramite Java" %}}
Utilizzando l'API, puoi anche esportare file MHTML in PSD con filigrana nel documento PSD. Per aggiungere una filigrana, puoi prima convertire MHTML in JPEG e aggiungere una filigrana. Per aggiungere una filigrana, caricare un file immagine utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image), creare un oggetto di [Graphics](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inizializzarlo con l'oggetto Image, creare una nuova [Matrix](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e imposta la traduzione e la trasformazione all'angolo desiderato e aggiungi la filigrana usando [Graphics.drawString](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Dopo aver aggiunto la filigrana all'immagine, puoi salvare il JPEG come formato PSD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converti e ruota MHTML in file PSD tramite Java" %}}
Utilizzando l'API, puoi anche ruotare l'immagine PSD di output secondo le tue esigenze. Il metodo Image.rotateFlip può essere utilizzato per ruotare l'immagine di 90/180/270 gradi e capovolgere l'immagine orizzontalmente o verticalmente. La libreria fornisce metodi semplici per eseguire operazioni complesse mentre incapsula tutti i dettagli brutti. È possibile specificare il tipo di rotazione e capovolgimento da applicare all'immagine. Per ruotare e capovolgere l'immagine, è possibile caricare l'immagine JPEG convertita utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image) e chiamare l'immagine. rotateFlip mentre si specifica l'appropriato [RotateFlipType](https://apiference.aspose.com/imaging/java/com.aspose.imaging/RotateFlipType). 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-and-rotate-pdf-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
"""
{{< blocks/products/pf/agp/feature-section >}}



La conversione di MHTML in PSD (Adobe Photoshop) trasforma le grafiche web in immagini stratificate completamente modificabili. PSD è ideale per designer e marketer che necessitano di capacità avanzate di modifica.



{{% blocks/products/pf/agp/feature-section-col title="Casi d'Uso Principali" %}}



* Modifica di banner, intestazioni o grafiche UI basate sul web in Photoshop.

* Estrazione di infografiche stratificate per campagne di marketing.

* Creazione di modelli web modificabili da contenuti archiviati.

* Progetti di design grafico che richiedono immagini web originali.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di Automazione" %}}



* Creazione batch di PSD da pagine web MHTML per team di design.

* Conversione attivata per aggiornamenti regolari di materiale di marketing.

* Integrazione nei flussi di risorse di design per l'automazione di Photoshop.

* Generazione programmata di PSD per flussi di lavoro web-to-print.



{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
"""
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}