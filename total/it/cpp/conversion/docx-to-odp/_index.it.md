---
title: Converti DOCX in ODP tramite C++ o con il convertitore online gratuito
description: Esporta DOCX in ODP nelle tue applicazioni C++ senza utilizzare Microsoft Word di PowerPoint o in linea. Prova rapidamente il convertitore online gratuito da DOCX a ODP prima di integrare il codice.

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: ODP
otherformats: POTX PPSM POTM POT PPTX PPS PPSX POWERPOINT PPT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire DOCX in ODP o App online" h2="Esporta DOCX in ODP all'interno delle tue applicazioni C++ senza utilizzare Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è costituito da potenti API di automazione dei file che consentono di automatizzare la conversione da DOCX a ODP utilizzando due delle sue API. Carica il tuo DOCX utilizzando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e convertilo in HTML, quindi carica l'HTML tramite la manipolazione di PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per creare una nuova presentazione e salvarla come ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da DOCX a ODP su C++" %}}
1. Aprire il file DOCX utilizzando [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) riferimento alla classe
2. Converti DOCX in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Inizializzare un nuovo oggetto [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Aggiungi una forma nella diapositiva e aggiungi AddTextFrame in essa
5. Carica il contenuto HTML e scrivilo nel tuo file di presentazione
6. Salva il documento in formato ODP utilizzando il metodo [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e imposta Odp come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCX file with an instance of Document
Document document = new Document("template.docx");
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"sourceFile.docx");
// save the document in HTML file format
docx->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertitore online gratuito da DOCX a ODP</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odp&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Carica documento DOCX protetto da password tramite C++" %}}
Oltre alla conversione dei documenti, l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente tantissime funzionalità di manipolazione dei documenti per gli sviluppatori C++. Nel caso in cui il tuo formato di file Microsoft Word DOCX sia protetto da password, puoi comunque aprirlo utilizzando l'API. Per caricare il documento crittografato, è possibile utilizzare un sovraccarico del costruttore speciale, che accetta un oggetto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Questo oggetto contiene la proprietà Password, che specifica la stringa della password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docxPassword");
// load thDocumentnt from the local fiDocument by filename:
SharedPtr<Docxument> docx = MakeObject<Docxument>(u"Encrypted.docx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi commenti nel documento ODP tramite C++" %}}
Durante il salvataggio di DOCX come ODP, puoi anche utilizzare [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per aggiungere ulteriori funzionalità al documento ODP. Ad esempio, puoi aggiungere commenti nella tua presentazione. I commenti alla diapositiva della presentazione sono associati a un determinato autore. La classe Presentation contiene la raccolta di autori in ICommentAuthorCollection responsabili dell'aggiunta di commenti alle diapositive. Per ogni autore, c'è una raccolta di commenti in ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Odp
pres->Save(output.odp, Aspose::Slides::Export::SaveFormat::Odp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
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
                          <span itemprop="name"><b>Come posso convertire DOCX in ODP online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Puoi trovare l'app online per la conversione DOCX sopra. Per avviare il processo di conversione, puoi aggiungere il file DOCX trascinandolo e rilasciandolo o facendo clic all'interno dell'area bianca per importare il documento. Dopo aver aggiunto il file, puoi semplicemente fare clic sul pulsante "Converti". Al termine della conversione da DOCX a ODP, puoi scaricare il file convertito con un solo clic.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quanto tempo ci vuole per convertire DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">La velocità di questo convertitore online dipende in gran parte dalla dimensione del file DOCX da convertire. Piccoli file DOCX possono essere convertiti in ODP in pochi secondi. Se si utilizza il codice di conversione all'interno di un'applicazione C++, la velocità di conversione dipenderà dall'ottimizzazione dell'applicazione.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>È sicuro convertire DOCX in ODP utilizzando il convertitore Aspose.Total gratuito?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ovviamente! Dopo che il tuo file DOCX è stato convertito in ODP utilizzando il nostro convertitore online, il link per il download del file ODP sarà immediatamente disponibile. Prendiamo sul serio la sicurezza e la privacy dei tuoi file caricati e li cancelliamo 24 ore dopo il completamento del processo di conversione. Stai tranquillo, nessuno avrà accesso ai tuoi file. Il nostro processo di conversione, inclusa la conversione DOCX, è completamente sicuro. Forniamo un'app gratuita a scopo di test in modo che tu possa verificare i risultati prima di integrare il codice.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Quale browser devo usare per convertire DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Per la conversione DOCX online, puoi utilizzare qualsiasi browser moderno, come Google Chrome, Firefox, Opera o Safari. Tuttavia, se stai sviluppando un'applicazione desktop, l'API Aspose.Total DOCX Conversion è consigliata per prestazioni fluide.</span>
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