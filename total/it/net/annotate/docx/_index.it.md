---
title: Rimuovi l'annotazione DOCX online o gestisci le annotazioni tramite .NET
description: elimina gratuitamente i commenti dal file DOCX tramite l'app online.Codice API .NET per gestire i commenti dei file DOCX.

family: total
platformtag: net
feature: Annotate
informat: DOCX
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Cancella commenti dal documento DOCX online o gestisci tramite .NET" h2="Sviluppa una potente applicazione di utilità per l'annotazione di documenti DOCX basata su .NET.Codice elencato per la gestione dei commenti del file DOCX tramite .NET." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Rimuovi le annotazioni DOCX online" %}}

1. Importa il file DOCX per eliminare i commenti caricandolo
1. Fallo facendo clic all'interno dell'area di rilascio tramite trascinamento dell'app di annotazione
1. A seconda della dimensione del file DOCX e della velocità di Internet, attendere alcuni secondi
1. Fare clic sul pulsante "Rimuovi" per cancellare i commenti
1. Scarica il file immediatamente

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Elimina commenti specifici sul documento DOCX dell'autore tramite .NET" %}}

1. Aggiungi riferimento alla libreria al progetto .NET
1. Carica il documento tramite l'oggetto classe Document
1. Ottieni tutti i commenti dei nodi utilizzando GetChildNodes con NodeType.Comment
1. Scorrere tutti i commenti e abbinare il nome dell'autore
1. Chiama il metodo Remove per eliminare il commento specifico dell'autore

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice C#: elimina i commenti specifici dell'autore dal file DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Aggiungi commenti tramite .NET" %}}

1. Crea un oggetto di classe Documento
1. Utilizzare la classe Comment
1. Aggiungi il nuovo paragrafo utilizzando Paragraphs.Add
1. Utilizza FirstParagraph.Runs.Add per aggiungere il commento
1. Oppure l'altro modo è utilizzare le classi CommentRangeStart e CommentRangeEnd
1. Chiama il metodo di salvataggio per salvare il file con i commenti aggiunti

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Estrai tutti i commenti" %}}

1. Carica il documento tramite l'oggetto classe Document
1. Crea un oggetto ArrayList
1. Ottieni tutti i GetChildNodes in NodeCollection
1. Scorri ogni raccolta e aggiungi commenti in ArrayList

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="Codice .NET: aggiungi commento dal file DOCX" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Estrai tutti i commenti" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Sviluppare un'applicazione di annotazione di documenti DOCX tramite .NET</h2>

Hai bisogno di sviluppare un'app o un'utilità di annotazione DOCX per fornire feedback, dare suggerimenti o collaborare con altri sul documento?Con [Aspose.Words for .NET](https://products.aspose.com/words/net/), un'API figlio di [Aspose.Total for .NET](https://products.aspose.com/total/net/), qualsiasi sviluppatore .NET può integrare il codice API riportato sopra all'interno della propria applicazione di annotazione dei documenti.La potente libreria .NET consente di programmare qualsiasi soluzione di annotazione di documenti.Inoltre può supportare molti formati popolari incluso il formato DOCX.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Libreria .NET per annotare file DOCX" %}}

Esistono tre opzioni alternative per installare "Aspose.Words for .NET" o "Aspose.Total for .NET" sul tuo sistema.Scegline uno che soddisfi le tue esigenze e segui le istruzioni passo passo:<br /><br />

- Installa una [NuGet Package](https://www.nuget.org/packages/Aspose.Words/). Vedi [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Installa la libreria utilizzando [Package Manager Console](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) all'interno dell'IDE di Visual Studio
- Installa la libreria manualmente utilizzando [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

Il nostro prodotto è completamente multipiattaforma e supporta tutte le principali implementazioni .NET seguendo la specifica ".NET Standard 2.0":<br /><br />

- Microsoft .NET Framework, a partire dalla prima versione 2.0 e termina con l'ultima ".NET Framework 4.8"
- .NET Core, a partire dalla prima versione 2.0 e terminando con l'ultima ".NET 6"
- Mono >= 2.6.7
<br /><br />
Poiché il codice .NET non si basa sull'hardware o sul sistema operativo sottostante, ma solo su una macchina virtuale, sei libero di sviluppare qualsiasi tipo di software per Windows, macOS, Android, iOS e Linux.Assicurati solo di aver installato la versione corrispondente di .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.<br /><br />
È consigliabile usare Microsoft Visual Studio, Xamarin e MonoDevelop IDE per creare applicazioni C#, F# e VB.NET.
<br /><br />
Per maggiori dettagli fare riferimento a [Product Documentation](https://docs.aspose.com/words/net/system-requirements/).

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="Domande frequenti" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Domande frequenti</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Posso utilizzare il codice .NET precedente nella mia applicazione?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sì, puoi scaricare questo codice e utilizzarlo allo scopo di sviluppare un'applicazione di annotazione di documenti basata su .NET.Questo codice può rappresentare una risorsa preziosa per migliorare la funzionalità e le capacità dei tuoi progetti nel campo dell'elaborazione e della manipolazione dei documenti backend.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Questa app per l'annotazione di documenti online funziona solo su Windows?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Hai la flessibilità di avviare l'annotazione del documento per la rimozione dei commenti su qualsiasi dispositivo, indipendentemente dal sistema operativo su cui viene eseguito, sia esso Windows, Linux, Mac OS o Android.Tutto ciò che serve è un browser web moderno e una connessione Internet attiva.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro utilizzare l'app online per annotare il documento DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! I file di output generati tramite il nostro servizio verranno rimossi in modo sicuro e automatico dai nostri server entro un periodo di 24 ore.Di conseguenza, i collegamenti di visualizzazione associati a questi file cesseranno di essere funzionali dopo tale periodo.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser dovrebbe utilizzare l'app?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web moderno come Google Chrome, Firefox, Opera o Safari per l'annotazione di documenti DOCX online.Tuttavia, se stai sviluppando un'applicazione desktop, ti consigliamo di utilizzare l'API di elaborazione dei documenti Aspose.Total per una gestione efficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}