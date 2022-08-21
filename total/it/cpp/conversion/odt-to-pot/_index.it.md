---
title: Converti ODT in POT tramite C++
description: Esporta ODT in POT nelle tue applicazioni C++ senza utilizzare Microsoft Word di PowerPoint
url: /it/cpp/conversion/odt-to-pot/
family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: POT
otherformats: PPTM POTM POTX PPSM ODP PPTX PPSX POWERPOINT PPT PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire ODT in POT" h2="Esporta ODT in POT all'interno delle tue applicazioni C++ senza utilizzare Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è costituito da potenti API di automazione dei file che consentono di automatizzare la conversione da ODT a POT utilizzando due delle sue API. Carica il tuo ODT utilizzando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e convertilo in HTML, quindi carica l'HTML tramite la manipolazione di PowerPoint API C++ [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) per creare una nuova presentazione e salvarla come POT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da ODT a POT su C++" %}}
1. Aprire il file ODT utilizzando [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) riferimento alla classe
2. Converti ODT in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_stdbasicostream_saveoptions)
3. Inizializzare un nuovo oggetto [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Aggiungi una forma nella diapositiva e aggiungi AddTextFrame in essa
5. Carica il contenuto HTML e scrivilo nel tuo file di presentazione
6. Salva il odtumento in formato POT utilizzando il metodo [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e imposta Pot come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load ODT file with an instance of Odtument
Odtument odtument = new Odtument("template.odt");
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"sourceFile.odt");
// save the odtument in HTML file format
odt->Save(u"HtmlOutput.HTML");
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Carica odtumento ODT protetto da password tramite C++" %}}
Oltre alla conversione dei odtumenti, l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente tantissime funzionalità di manipolazione dei odtumenti per gli sviluppatori C++. Nel caso in cui il tuo formato di file Microsoft Word ODT sia protetto da password, puoi comunque aprirlo utilizzando l'API. Per caricare il odtumento crittografato, è possibile utilizzare un sovraccarico del costruttore speciale, che accetta un oggetto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Questo oggetto contiene la proprietà Password, che specifica la stringa della password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected odtument, the password is passed to the odtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"odtPassword");
// load the odtument from the local file system by filename:
SharedPtr<Odtument> odt = MakeObject<Odtument>(u"Encrypted.odt", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi commenti nel odtumento POT tramite C++" %}}
Durante il salvataggio di ODT come POT, puoi anche utilizzare [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per aggiungere ulteriori funzionalità al odtumento POT. Ad esempio, puoi aggiungere commenti nella tua presentazione. I commenti alla diapositiva della presentazione sono associati a un determinato autore. La classe Presentation contiene la raccolta di autori in ICommentAuthorCollection responsabili dell'aggiunta di commenti alle diapositive. Per ogni autore, c'è una raccolta di commenti in ICommentCollection.
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
// save presentation as Pot
pres->Save(output.pot, Aspose::Slides::Export::SaveFormat::Pot);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-pptm/" name="ODT Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-potm/" name="ODT Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-potx/" name="ODT Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-ppsm/" name="ODT Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-pot/" name="ODT Per POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-pptx/" name="ODT Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-ppsx/" name="ODT Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-powerpoint/" name="ODT Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-ppt/" name="ODT Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-pps/" name="ODT Per PPS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}