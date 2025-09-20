---
title: Converti il formato JSON in EMZ tramite Java
description: Analizza JSON in EMZ in Java senza utilizzare Microsoft PowerPoint
url_ignore: /it/java/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: EMZ SVGZ DXF JPEG2000 PSD WMF WMZ TGA DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti il formato JSON in EMZ tramite Java" h2="API Java per analizzare il formato JSON in EMZ all'interno di qualsiasi applicazione Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for Java](https://products.aspose.com/total/java/), puoi convertire il formato JSON in EMZ all'interno di qualsiasi applicazione Java in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puoi analizzare JSON in JPEG. Successivamente, utilizzando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), puoi convertire JPEG in EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in EMZ tramite Java" %}}
1. Crea un nuovo oggetto [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) e apri il file JSON
2. Salva JSON come JPEG utilizzando [save](https://apiference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) metodo
3. Caricare il documento JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salvare il documento in formato EMZ utilizzando [save](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) metodo
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Puoi facilmente utilizzare Aspose.Total per Java direttamente da un progetto basato su [Maven](https://releases.aspose.com/total/java/) e includi le librerie nel tuo pom.xml.

In alternativa, puoi ottenere un file ZIP da [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisiti di conversione" %}}
Inoltre, l'API consente di analizzare JSON in EMZ con opzioni di layout specificate. Per specificare le opzioni di layout, puoi utilizzare la classe [JsonLayoutOptions](https://apiference.aspose.com/cells/java/com.aspose.cells/jsonlayoutions). Ti consente di elaborare un array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Imposta il layout e converti il formato JSON in EMZ tramite Java" %}}
Utilizzando l'API, puoi anche convertire JSON in EMZ con filigrana nel tuo documento EMZ. Per aggiungere una filigrana, puoi prima convertire JSON in JPEG e aggiungere una filigrana. Per aggiungere una filigrana, caricare un file immagine utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Image), creare un oggetto di [Graphics](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inizializzarlo con l'oggetto Image, creare una nuova [Matrix](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e imposta la traduzione e la trasformazione all'angolo desiderato e aggiungi la filigrana usando [Graphics.drawString](https://apiference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Dopo aver aggiunto la filigrana all'immagine, puoi salvare il JPEG come formato EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
La conversione di **JSON in EMZ (Enhanced Metafile Compresso)** è cruciale per creare **grafica vettoriale compressa** da set di dati strutturati. I file EMZ memorizzano visuali di alta qualità con dimensioni ridotte, rendendoli ideali per un utilizzo scalabile, portatile e multipiattaforma. Trasformare JSON in EMZ consente un rendering efficiente dei dati strutturati in grafici professionali, diagrammi e schemi ottimizzando allo stesso tempo archiviazione e prestazioni.

## Casi d'Uso Principali

- **Grafici scalabili** – Genera grafici basati su dati da JSON per presentazioni e report.
- **Diagrammi aziendali** – Costruisci organigrammi, diagrammi di flusso e visuali di processo.
- **Schemi basati su JSON** – Converti set di dati strutturati in illustrazioni vettoriali tecniche.
- **Archiviazione vettoriale leggera** – Comprimi file vettoriali di grandi dimensioni per una distribuzione e archiviazione più semplici.
- **Integrazione grafica multipiattaforma** – Assicura la compatibilità tra applicazioni e piattaforme aziendali.

## Scenari di Automazione

- **Pipeline JSON-to-EMZ** – Automatizza la trasformazione di dati strutturati in grafica vettoriale compressa.
- **Compressione di diagrammi automatizzata** – Ottimizza i flussi di lavoro con output vettoriali pre-compressi.
- **Visuali di report basati su JSON** – Crea visuali leggeri e scalabili direttamente dai set di dati.
- **Standardizzazione grafica di grado enterprise** – Garantisci formati vettoriali coerenti e compressi in tutti i flussi di lavoro organizzativi.

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}