---
title: Rimuovi l'annotazione PDF online o gestisci le annotazioni utilizzando le app mobili Android
description: elimina gratuitamente i commenti dal file PDF tramite l'app online.Codice API Android per gestire i commenti dei file PDF.

family: total
platformtag: Android
feature: Annotate
informat: PDF
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF ODT TXT Word PDF Excel XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS Powerpoint PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Cancella commenti dal documento PDF online o gestisci tramite app Android" h2="Sviluppa una potente applicazione di utilità per l'annotazione di documenti PDF basata su Android.Codice elencato per la gestione dei commenti del file PDF." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovi le annotazioni PDF online" %}}

1. Importa il file PDF per eliminare i commenti caricandolo
1. Fallo facendo clic all'interno dell'area di rilascio tramite trascinamento dell'app di annotazione
1. A seconda della dimensione del file PDF e della velocità di Internet, attendere alcuni secondi
1. Fare clic sul pulsante "Rimuovi" per cancellare i commenti
1. Scarica il file immediatamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rimuovi i commenti del documento PDF tramite l'API dell'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Carica il documento tramite l'oggetto classe Document
1. Selezionare la pagina specifica tramite getPages().get_Item(Index)
1. Utilizza AnnotationSelector e ottieni tutte le annotazioni di testo tramite annotationSelector.getSelected()
1. Scorrere ogni annotazione e chiamare il metodo delete per rimuoverla.
1. Chiama il metodo di salvataggio per salvare il file.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: elimina commenti dal file PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "delete-all-pdf-page-annotation.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Aggiungi annotazione tramite API dell'app Android" %}}

1. Aggiungi riferimento alla libreria al progetto Android
1. Crea un oggetto di classe Documento
1. Aggiungi la nuova pagina e il contenuto utilizzando getPages().add()
1. Utilizza getPages().get_Item(Index) della classe TextAnnotation
1. Imposta le annotazioni pertinenti come titolo, oggetto, contenuto, ecc
1. Utilizza getAnnotations().add per aggiungere le annotazioni
1. Chiama il metodo di salvataggio per salvare il file con i commenti aggiunti
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice: aggiungi annotazione PDF" offSpacer="" %}}

{{< gist "aspose-com-gists" "b571b78d9a9a1b41d5ece691af6102d2" "add-annotations-to-pdf-document.java" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Sviluppa l'app Android per l'annotazione dei documenti PDF</h2>

Hai bisogno di sviluppare un'app o un'utilità mobile per annotazioni PDF per fornire feedback, dare suggerimenti o collaborare con altri sul documento?Con [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/it/android-java/), un'API figlia di [Aspose.Total for Android via Java](https://products.aspose.com/total/it/android-java/), qualsiasi sviluppatore Android può integrare il codice API di cui sopra all'interno della propria applicazione di annotazione dei documenti.La potente libreria Android consente di programmare qualsiasi soluzione di annotazione di documenti.Inoltre può supportare molti formati popolari incluso il formato PDF.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Libreria Android per annotare file PDF" %}}

- Ospitiamo i nostri pacchetti Java in [Repository Maven](https://releases.aspose.com/java/repo/com/aspose/aspose-pdf/). 
- Aspose.PDF for Java è un file JAR comune contenente codice byte.
- Segui [istruzioni passo passo](https://docs.aspose.com/pdf/java/installation/#install-aspose-pdf-for-java-from-maven-repository) su come installare Aspose.PDF for Android via Java.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

- API Android 31 e 32
- Android 4.0 e versioni successive
- Strumenti Android Studio e SDK

<br />
Per maggiori dettagli sulle dipendenze dei pacchetti opzionali, come JogAmp JOGL, motore dei caratteri Harfbuzz, Java Advanced Imaging JAI, fare riferimento a [Documentazione del prodotto](https://docs.aspose.com/pdf/java/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}