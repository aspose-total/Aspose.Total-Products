---
title: Converti ODT in PPTM tramite C# .NET o con il convertitore online gratuito
description: Converti documenti Word in file pptm PowerPoint con C#. Converti più file all'interno di ASP.NET o altre applicazioni .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Converti ODT in PPTM usando C# o in linea" h2="Crea app di conversione da Microsoft Word ODT a PowerPoint PPTM su piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Come convertire ODT in PPTM usando C#" %}}

Al fine di automatizzare il processo per qualsiasi file di Word odt nella conversione batch di presentazioni PowerPoint pptm, utilizzeremo [Aspose.Words for .NET](https://products.aspose.com/words/net) e [Aspose.Slides per .NET](https://products.aspose.com/slides/net) API. La prima è un'API di elaborazione testi per l'elaborazione o la manipolazione di documenti Microsoft Word. Considerando che quest'ultima è un'API di manipolazione della presentazione che ti consente di creare o modificare diapositive di Microsoft PowerPoint. Entrambe le API fanno parte del pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net). Puoi [scaricare](https://releases.aspose.com/) direttamente da Nuget o utilizzare i seguenti comandi dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando della console di gestione dei pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passaggi per convertire ODT in PPTM tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Aggiungere il riferimento di Aspose.Total per .NET
1. Caricare il file ODT utilizzando la classe [Aspose.Words.Document](https://apiference.aspose.com/words/net/aspose.words/document)
1. Salva il documento ODT in HTML
1. Crea un oggetto [Aspose.Slides.Presentation](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
1. Importa contenuto HTML nella cornice di testo di qualsiasi forma di diapositiva all'interno della presentazione
1. Salvare il documento utilizzando [Aspose.Slides.Presentation.Save("output.pptm", SaveFormat.Pptm)](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con piattaforme .NET Framework, .NET Core, Windows Azure, Mono o Xamarin.
- Ambiente di sviluppo come Microsoft Visual Studio.
- Aspose.Words per .NET &amp; Aspose.Slides per DLL .NET o Aspose.Total per DLL .NET a cui si fa riferimento nel progetto.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo esempio di codice mostra come convertire un ODT in PPTM usando C#" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word ODT file
Aspose.Words.Document odt = new Aspose.Words.Document("sourceWordFile.odt");

// Save ODT file to HTML 
odt.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages ODT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to PPTM.

using (Presentation pptm = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the PPTM Presentation
	pptm.Save("filepath\\pres.pptm", Aspose.Slides.Export.SaveFormat.Pptm);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Convertitore online da ODT a PPTM</h3>

<iframe title="Strumento di conversione gratuito da odt a pptm" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptm&from=odt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita per convertire ODT in PPTM" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant PPTM file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos ODT a PPTM mediante programación: casos de uso" %}}
Utilizzo dei file di testo aperti (OpenDocument Text) per archiviare documenti di testo, rendendoli ideali per la creazione di documenti statici e relazioni. Tuttavia, quando si lavora con presentazioni come PPTM (Template Macro-enabled di Microsoft PowerPoint), i file ODT diventano essenziali per la creazione e l'edizione delle presentazioni.

La conversione dei file ODT in formati PPTM è necessaria per rivelare al meglio le capacità della tua capacità di presentazione. Questa conversione consente a te:

**Casi d'uso:**

*   **Presentazioni aziendali**: Converti i file ODT per creare presentazioni professionali, modificare gli schemi esistenti e aggiungere contenuti multimediali.
*   **Presentazioni accademiche**: Usa PPTM per presentare scoperte di ricerca, collaborare con membri del team e visualizzare dati complessi in modo engaging.
*   **Presentazioni commerciali**: Converti i file ODT per creare proposte di marketing persuasivi, seguire lo stato delle vendite e analizzare la retroazione dei clienti.
*   **Sessioni di formazione**: Usa PPTM per creare materiali di formazione interattivi, incassare video lezioni e condividere conoscenze con gli stakeholder.
*   **Presentazioni di conferenza**: Converti i file ODT per presentare scoperte di ricerca, mostrare prodotti e coinvolgere gli spettatori attraverso contenuti multimediali."
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Domande frequenti</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Come posso convertire ODT in PPTM online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">L'app online per la conversione ODT è integrata sopra. Per utilizzare questa app, puoi aggiungere il tuo file ODT trascinandolo nell'area bianca designata o facendo clic all'interno dell'area per importare il documento. Successivamente, premi il pulsante Converti per avviare il processo di conversione. Al termine della conversione da ODT a PPTM, puoi scaricare il file appena convertito con un solo clic e sarà disponibile sotto forma di file PPTM.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo ci vuole per convertire ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Questo convertitore online funziona rapidamente ma dipende principalmente dalle dimensioni del file ODT convertito. Per i piccoli file ODT, la conversione in PPTM può essere completata in pochi secondi. Tuttavia, se hai integrato il codice di conversione all'interno di un'applicazione .NET, la velocità di conversione dipenderà dall'ottimizzazione dell'applicazione per il processo di conversione.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro convertire ODT in PPTM utilizzando il convertitore Aspose.Total gratuito?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! Una volta completata la conversione da ODT a PPTM, il collegamento per il download del file PPTM appena convertito sarà immediatamente disponibile. Garantisce inoltre la sicurezza del processo di conversione, poiché tutti i file caricati, inclusi i file ODT, sono completamente sicuri e verranno eliminati dal sistema dopo 24 ore. Inoltre, i link per il download smetteranno di funzionare dopo questo periodo, garantendo la privacy e la protezione dei tuoi file. L'app integrata è gratuita e progettata per scopi di test in modo che gli utenti possano valutare i risultati prima di integrare il codice nei loro progetti.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser devo usare per convertire ODT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi utilizzare qualsiasi browser Web moderno, come Google Chrome, Firefox, Opera o Safari, per la conversione online da ODT a PPTM. Tuttavia, se stai sviluppando un'applicazione desktop, l'API Aspose.Total ODT Conversion è consigliata per un'elaborazione fluida ed efficiente.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}