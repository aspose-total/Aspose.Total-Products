---
title: Conversione del formato file tramite Java 
url: /it/java/conversion/
description: Converti Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, immagini 3D, diagrammi, formati video e diversi altri formati con poche righe di codice Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversione del formato file tramite Java" h2="Converti documenti Microsoft<sup>&reg;</sup> Office, PDF, immagini, HTML e molti altri file senza utilizzare altri software." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Java Total Library](https://products.aspose.com/total/java/) accelera lo sviluppo di soluzioni di manipolazione dei documenti da zero o il miglioramento delle applicazioni esistenti per gestire con facilità la gestione dei documenti. L'API non solo crea, modifica e converte documenti di Microsoft Office, ma gestisce anche PDF, HTML, immagini TIFF, JPG, PNG, BMP e SVG, file di posta elettronica, formati video, 3D, CAD e molto altro. È una raccolta di API di soluzioni per la gestione e la manipolazione dei documenti senza alcuna dipendenza dal software all'interno delle applicazioni Java J2SE, J2EE, J2ME. I programmatori possono facilmente creare, aggiornare, eseguire il rendering, stampare e convertire tra i formati più diffusi all'interno di qualsiasi applicazione basata su Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Conversione da Word a Excel" %}}
Total API supporta non solo l'interconversione dei formati Microsoft Word, ma anche la conversione di Word in Excel, PDF, HTML, Immagini, EPUB, Markdown e XPS. Il processo di conversione è semplice. Consideriamo il caso della conversione **Word to Excel**. Carica il file Microsoft Word utilizzando la classe [Document](https://apiference.aspose.com/words/java/com.aspose.words/Document) e converti **WORD in HTML** utilizzando il [Metodo di salvataggio](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)). Quindi apri il documento HTML convertito utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) e salva il documento in formato XLSX usando [Save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Gli sviluppatori possono anche convertire [Word to PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Java Conversione da Word a Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Converti PDF in immagini" %}}
L'API supporta la conversione di PDF in immagini come JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel e altri formati. Per la conversione da PDF a immagine, consideriamo l'immagine JPG come file di destinazione. Il processo consiste nel caricare il file PDF utilizzando la classe Document e inizializzare l'oggetto [JpegDevice class](https://apiference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) ed eseguire il rendering del PDF in JPEG tramite [Process](https ://apireference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1) metodo
Carica il file JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/java/aspose.imaging/image) e infine chiama il metodo Save.

{{% blocks/products/pf/feature-page-code h3="Java PDF to Image Conversion" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti PowerPoint in file Excel" %}}

Per convertire i file di Microsoft PowerPoint in file diversi tra cui Excel Word, MHTML, API secondarie pertinenti coinvolte nell'API principale di Aspose.Total per Java. Processo di conversione dei file PowerPoint in un documento Excel, carica il file PowerPoint utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation) e converti **PowerPoint in HTML** di utilizzando il metodo [save](https://apiference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Quindi carica il documento HTML convertito utilizzando la classe [Workbook](https://apiference.aspose.com/cells/java/com.aspose.cells/Workbook) e salva il documento in formato EXCEL usando [save](https:/ /apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)). Elencato anche il codice per la conversione da **PowerPoint a Word**.

{{% blocks/products/pf/feature-page-code h3="Conversione da Java PowerPoint a Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Conversione da PowerPoint a Word in Java" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}