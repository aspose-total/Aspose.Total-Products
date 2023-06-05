---
title: Converti pagine Web HTML in immagini utilizzando C#
description: Raschiare le pagine Web del sito Web ed esportare HTML in immagini. Sviluppa applicazioni .NET per raschiare i dati del sito Web in JPEG, PNG, GIF, BMP ecc. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti pagine Web in immagini tramite C#" h2="Estrai i dati del sito Web dalle pagine Web HTML. Converti HTML in immagini JPG, GIF, PNG, BMP all'interno di applicazioni .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Perché convertire le pagine Web in immagini?</h2>
<p>La conversione di pagine Web in immagini può essere utile in una varietà di situazioni. È un requisito comune per molte applicazioni. In alcuni scenari, è necessario acquisire l'intera pagina Web come immagine, comprese le parti non visibili sullo schermo. Ciò può essere utile per generare anteprime di siti Web, acquisire ricevute e fatture o archiviare pagine Web per scopi legali. Può essere utilizzato per creare schermate di pagine Web a scopo di documentazione o test. Può anche essere utilizzato per creare miniature o anteprime di pagine Web da utilizzare nei risultati di ricerca o nelle gallerie di immagini. Che tu stia creando un'applicazione desktop o un'applicazione Web, sono disponibili molte opzioni per convertire le pagine Web in immagini utilizzando C#.</p><br />

<p>La conversione di pagine Web in immagini tramite C# può offrire diversi vantaggi, tra cui:</p><br />
<ul>
<li>Accessibilità migliorata: Le immagini possono essere più facili da leggere e comprendere per le persone con disabilità visive o altre disabilità.</li>
<li>Maggiore portabilità: Le immagini possono essere facilmente condivise o incorporate in altri documenti o applicazioni.</li>
</ul>
<p>Anche la conversione di pagine Web in immagini utilizzando C# può presentare alcune sfide, tra cui:</p><br />
<ul>
<li>Supporto formato limitato: Alcune API o strumenti potrebbero non supportare tutti i formati di immagine o potrebbero avere limitazioni sulla dimensione o sulla risoluzione delle immagini di output.</li>
<li>Problemi di compatibilità: Alcune pagine Web potrebbero non essere visualizzate correttamente in tutti i browser o potrebbero richiedere impostazioni o plug-in specifici per essere visualizzate correttamente.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire pagine Web in immagini utilizzando C#?" %}}
Per convertire le pagine Web in immagini utilizzando C#, puoi utilizzare un'API Aspose.HTML per .NET che fornisce questa funzionalità per convertire le pagine HTML in formati immagine, inclusi JPEG, PNG e TIFF.</p>

1. Carica un documento HTML utilizzando uno dei costruttori disponibili in [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Puoi caricare HTML da un file, codice HTML, uno stream o un URL.
2. Crea una nuova istanza di [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) e impostare la proprietà ImageFormat su JPEG. Per impostazione predefinita, la proprietà Format è impostata su PNG.
3. Utilizza il [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metodo dalla classe Converter per salvare il documento HTML come file JPEG. Dovrai fornire HTMLDocument, ImageSaveOptions e il percorso del file di output come parametri per il metodo ConvertHTML().
4. Il file JPEG risultante verrà salvato nel percorso file specificato.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti per lo scrapping Web e la conversione delle immagini" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o installa direttamente dalla console di Package Manager di Visual Studio.

Due [Aspose.Total for .NET](https://products.aspose.com/total/net/) API figlio, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) sarà integrato.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}