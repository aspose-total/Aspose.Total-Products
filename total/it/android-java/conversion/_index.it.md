---
title: Conversione di documenti tramite API Android 

description: Converti i formati Word, Excel, PowerPoint, HTML, PDF e Immagine utilizzando l'API di conversione Android. Android converte Office docx, xlsx, pptx in PDF. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversione di documenti utilizzando l'API Android" h2="Converti Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Immagini e vari altri formati utilizzando Aspose.Total for Android via Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) fornisce la soluzione di conversione e gestione dei documenti per le applicazioni Android senza fare affidamento su altri software. I programmatori possono automatizzare facilmente la soluzione di gestione e manipolazione dei documenti integrando l'API all'interno di nuove applicazioni sviluppate o in applicazioni esistenti. Integrando l'API, il programmatore può aggiungere facilmente funzionalità per creare, modificare o convertire documenti di vari formati all'interno dell'applicazione. PDF Converter API in Android gestisce casi di conversione come Office DOCX, XLSX, PPTX in PDF o viceversa. Inoltre, alcuni casi trattati dall'API sono elencati di seguito e pochi collegamenti forniti per i casi di conversione pertinenti. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converti PDF in CSV" %}}
Total Android API supporta la conversione da PDF a Excel XLSX e CSV. È un processo in due fasi. Due API totali [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) e [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) coinvolti. Il processo è che puoi convertire prima il formato PDF in Excel XLSX e poi XLSX in CSV. Più in dettaglio, carica il file PDF tramite la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) ed esegui il rendering in XLSX tramite [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-). Quindi carica il documento XLSX sottoposto a rendering utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e invoca [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android - Conversione da PDF a Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Conversione da Excel a Word" %}}
L'API Android gestisce anche la conversione di Excel. Il processo consiste nel caricare il file EXCEL XLSX utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e convertire EXCEL in PDF impostando innanzitutto SaveFormat su AUTO. Quindi carica il file PDF salvato utilizzando la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) e invoca [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) per salvare il documento in formato Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Conversione da Excel a Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti POWERPOINT in HTML e MHTML" %}}
Android Total API si occupa di vari formati, inclusi i file PowerPoint, in modo da poter convertire le presentazioni in HTML e MHTML. Il processo consiste nel caricare il file POWERPOINT PPT/PPTX utilizzando la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) e invocare [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) per convertire POWERPOINT in HTML. Inoltre, ora carica il documento HTML convertito utilizzando la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e chiama [save](https://reference.aspose.com/cells/java/com.aspose.cells/) per la conversione MHTML. 
{{% blocks/products/pf/feature-page-code h3="Android - Conversione diapositive PowerPoint in HTML e MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}