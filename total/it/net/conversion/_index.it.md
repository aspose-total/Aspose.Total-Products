---
title: Conversione del formato file tramite C# 
url: /it/net/conversion/
description: Converti Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, immagini 3D, diagrammi, formati video e molti altri file popolari con poche righe di codice C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversione del formato file tramite C# .NET" h2="Converti file Microsoft<sup>&reg;</sup> Office, PDF, immagini, HTML e altri formati diversi senza utilizzare altri software." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Libreria totale .NET](https://products.aspose.com/total/net/) accelera lo sviluppo di soluzioni di gestione dei documenti da zero o il miglioramento delle applicazioni esistenti per gestire con facilità la manipolazione dei documenti. L'API non solo gestisce i documenti di Microsoft Office, ma gestisce anche PDF, HTML, immagini TIFF, JPG, PNG, BMP e SVG, file di posta elettronica, formati video, formati di dati GIS e molto altro. È un set completo di API per soluzioni di gestione e manipolazione dei documenti senza dipendenze software. I programmatori possono facilmente creare, aggiornare, eseguire il rendering, stampare e convertire tra i formati più diffusi all'interno di qualsiasi applicazione basata su .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converti Word in PDF" %}}
Total API supporta non solo l'interconversione dei formati Microsoft Word, ma anche la conversione di Word in PDF, HTML, Immagini, EPUB, Markdown e XPS. Il processo di conversione è semplice. Carica la classe Document tramite Document e chiama semplicemente il metodo Save con il formato di destinazione. È così semplice. Gli sviluppatori possono controllare il [risultato della conversione](https://products.aspose.com/words/net/conversion/word-to-pdf/) prima dell'integrazione del codice di **Word to PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Conversione da Word a PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Converti PDF in immagini" %}}
L'API supporta la conversione di PDF in immagini, Powerpoint, Excel e altri formati. Per la conversione da PDF a immagine, consideriamo l'immagine JPG come file di destinazione. Il processo consiste nel caricare il file PDF utilizzando la classe Document e inizializzare l'oggetto [JpegDevice class](https://apiference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) ed eseguire il rendering del PDF in JPEG tramite [Process](https ://apiference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1) metodo
Carica il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image) e infine chiama il metodo Save.

{{% blocks/products/pf/feature-page-code h3="C# - Conversione da PDF a immagine" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti Excel in Word e PowerPoint" %}}

Per convertire i formati di Microsoft Excel in file diversi, inclusi Word e PowerPoint, le API secondarie pertinenti hanno coinvolto l'API principale di Aspose.Total per .NET. Processo di conversione dei file Excel in un documento Word, caricare il file EXCEL utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook) e convertire prima EXCEL in PDF e impostare SaveFormat su Auto. Quindi carica il file PDF convertito utilizzando la classe Document e chiama il metodo Save e imposta Doc, Docx come SaveFormat. Codice elencato anche per la conversione da Microsoft **Excel a Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Conversione da JSON a Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Conversione da Excel a JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}