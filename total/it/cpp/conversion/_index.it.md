---
title: Conversione di documenti tramite C++ 
url: /it/cpp/conversion/
description: Converti vari formati di documenti come Word, Excel, PowerPoint, PDF, JSON, Immagini e altro utilizzando l'API C++. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversione di documenti utilizzando C++" h2="Converti Microsoft<sup>&reg;</sup> Office Word, Excel, PowerPoint, PDF, Immagini e vari altri formati utilizzando la libreria C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) risolve il problema della conversione dei documenti e gli sviluppatori possono automatizzare facilmente la soluzione di gestione e manipolazione dei documenti integrando l'API all'interno di nuove applicazioni sviluppate o in applicazioni esistenti. I programmatori C++ possono aggiungere funzionalità come creare, modificare o convertire documenti di vari formati all'interno della loro soluzione senza fare affidamento su alcun software. Pochi casi generici come txt in PDF, SVG in PNG, XLSX in CSV, JSON in CSV, Word in PDF, HTML in PDF, si possono facilmente convertire. Inoltre, alcuni casi trattati dall'API sono elencati di seguito e pochi collegamenti forniti per i casi di conversione pertinenti. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Converti Microsoft Word in Excel" %}}
Total C++ API supporta la conversione da Microsoft Word DOC/DOCX a Excel.  Il processo consiste nel caricare il file Word DOC / DOCX utilizzando il riferimento alla classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) e invocare [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) da convertire in HTML in primo luogo. Quindi caricare il documento HTML utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e invocare [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) per salvare il documento in formato Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Conversione da Word a Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversione da PDF a Word" %}}
La libreria di conversione C++ supporta anche la conversione da PDF a Word DOC, DOCX e altri formati. Considerando il caso del rendering di PDF in RTF, è un processo in due fasi, prima convertire PDF in formato Word DOC/DOCX e quindi renderli in formato RTF. Passaggi inclusi per questo, caricamento del file PDF utilizzando [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) riferimento alla classe e invocando [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) funzione membro per convertire PDF in Word. Ora carica di nuovo il file Word DOC / DOCX utilizzando il riferimento alla classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) dell'API Aspose.Words e salvalo in formato RTF usando [Salva](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) funzione membro.

{{% blocks/products/pf/feature-page-code h3="C++ - Conversione da PDF a Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Converti JSON in Word" %}}
Per la conversione JSON, l'API C++ supporta varie combinazioni come JSON in Word, Json in PowerPoint, Word in JSON ecc. Considerando il caso della conversione di Word, Process legge i dati JSON validi dal file utilizzando un nuovo oggetto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e quindi invoca [Salva](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) per salvare JSON come file PDF. Quindi ora carica il file salvato usando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) e salvalo nel formato del documento Word usando [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Conversione da JSON a Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}