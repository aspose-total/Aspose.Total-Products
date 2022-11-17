---
title: Converti TXT in POT tramite C++
description: Esporta TXT in POT nelle tue applicazioni C++ senza utilizzare Microsoft Word di PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: POT
otherformats: POTM PPSM PPSX PPT PPS PPTX POTX POWERPOINT PPTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire TXT in POT" h2="Esporta TXT in POT all'interno delle tue applicazioni C++ senza utilizzare Microsoft Word&reg; o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) è costituito da potenti API di automazione dei file che consentono di automatizzare la conversione da TXT a POT utilizzando due delle sue API. Carica il tuo TXT utilizzando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e convertilo in HTML, quindi carica l'HTML tramite la manipolazione di PowerPoint API C++ [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per creare una nuova presentazione e salvarla come POT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversione da TXT a POT su C++" %}}
1. Aprire il file TXT utilizzando [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument) riferimento alla classe
2. Converti TXT in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions)
3. Inizializzare un nuovo oggetto [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Aggiungi una forma nella diapositiva e aggiungi AddTextFrame in essa
5. Carica il contenuto HTML e scrivilo nel tuo file di presentazione
6. Salva il txtumento in formato POT utilizzando il metodo [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e imposta Pot come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TXT file with an instance of Txtument
Txtument txtument = new Txtument("template.txt");
System::SharedPtr<Txtument> txt = System::MakeObject<Txtument>(u"sourceFile.txt");
// save the txtument in HTML file format
txt->Save(u"HtmlOutput.HTML");
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

{{% blocks/products/pf/feature-page-section  h2="Carica txtumento TXT protetto da password tramite C++" %}}
Oltre alla conversione dei txtumenti, l'API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente tantissime funzionalità di manipolazione dei txtumenti per gli sviluppatori C++. Nel caso in cui il tuo formato di file Microsoft Word TXT sia protetto da password, puoi comunque aprirlo utilizzando l'API. Per caricare il txtumento crittografato, è possibile utilizzare un sovraccarico del costruttore speciale, che accetta un oggetto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Questo oggetto contiene la proprietà Password, che specifica la stringa della password.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Aggiungi commenti nel txtumento POT tramite C++" %}}
Durante il salvataggio di TXT come POT, puoi anche utilizzare [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) per aggiungere ulteriori funzionalità al txtumento POT. Ad esempio, puoi aggiungere commenti nella tua presentazione. I commenti alla diapositiva della presentazione sono associati a un determinato autore. La classe Presentation contiene la raccolta di autori in ICommentAuthorCollection responsabili dell'aggiunta di commenti alle diapositive. Per ogni autore, c'è una raccolta di commenti in ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-potm/" name="TXT Per POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-ppsm/" name="TXT Per PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-ppsx/" name="TXT Per PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-ppt/" name="TXT Per PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-pps/" name="TXT Per PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-pptx/" name="TXT Per PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-potx/" name="TXT Per POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-powerpoint/" name="TXT Per POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-pptm/" name="TXT Per PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/txt-to-pot/" name="TXT Per POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}