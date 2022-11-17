---
title: Converti WORDML in ODP tramite C++
description: Esporta WORDML in ODP nelle tue applicazioni C++ senza utilizzare Microsoft Word di PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: WORDML
outformat: ODP
otherformats: PPT PPTX PPSM POT PPSX POTM POWERPOINT PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire WORDML in ODP" h2="Esporta WORDML in ODP all'interno delle tue applicazioni C++ senza utilizzare Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è costituito da potenti API di automazione dei file che consentono di automatizzare la conversione da WORDML a ODP utilizzando due delle sue API. Carica il tuo WORDML utilizzando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e convertilo in HTML, quindi carica l'HTML tramite la manipolazione di PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per creare una nuova presentazione e salvarla come ODP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da WORDML a ODP su C++" %}}
1. Aprire il file WORDML utilizzando [Wordmlument](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument) riferimento alla classe
2. Converti WORDML in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.wordmlument#save_stdbasicostream_saveoptions)
3. Inizializzare un nuovo oggetto [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Aggiungi una forma nella diapositiva e aggiungi AddTextFrame in essa
5. Carica il contenuto HTML e scrivilo nel tuo file di presentazione
6. Salva il wordmlumento in formato ODP utilizzando il metodo [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e imposta Odp come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load WORDML file with an instance of Wordmlument
Wordmlument wordmlument = new Wordmlument("template.wordml");
System::SharedPtr<Wordmlument> wordml = System::MakeObject<Wordmlument>(u"sourceFile.wordml");
// save the wordmlument in HTML file format
wordml->Save(u"HtmlOutput.HTML");
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

{{% blocks/products/pf/feature-page-section  h2="Carica wordmlumento WORDML protetto da password tramite C++" %}}
Oltre alla conversione dei wordmlumenti, l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente tantissime funzionalità di manipolazione dei wordmlumenti per gli sviluppatori C++. Nel caso in cui il tuo formato di file Microsoft Word WORDML sia protetto da password, puoi comunque aprirlo utilizzando l'API. Per caricare il wordmlumento crittografato, è possibile utilizzare un sovraccarico del costruttore speciale, che accetta un oggetto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Questo oggetto contiene la proprietà Password, che specifica la stringa della password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected wordmlument, the password is passed to the wordmlument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"wordmlPassword");
// load the wordmlument from the local file system by filename:
SharedPtr<Wordmlument> wordml = MakeObject<Wordmlument>(u"Encrypted.wordml", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi commenti nel wordmlumento ODP tramite C++" %}}
Durante il salvataggio di WORDML come ODP, puoi anche utilizzare [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per aggiungere ulteriori funzionalità al wordmlumento ODP. Ad esempio, puoi aggiungere commenti nella tua presentazione. I commenti alla diapositiva della presentazione sono associati a un determinato autore. La classe Presentation contiene la raccolta di autori in ICommentAuthorCollection responsabili dell'aggiunta di commenti alle diapositive. Per ogni autore, c'è una raccolta di commenti in ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-ppt/" name="WORDML Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-pptx/" name="WORDML Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-ppsm/" name="WORDML Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-pot/" name="WORDML Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-ppsx/" name="WORDML Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-potm/" name="WORDML Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-powerpoint/" name="WORDML Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-pptm/" name="WORDML Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-potx/" name="WORDML Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/wordml-to-pps/" name="WORDML Per PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}