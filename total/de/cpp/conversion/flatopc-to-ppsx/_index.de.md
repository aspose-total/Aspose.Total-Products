---
title: Konvertieren Sie FLATOPC über C++ in PPSX oder mit dem kostenlosen Online Converter
description: Exportieren Sie FLATOPC in PPSX in Ihren C++-Anwendungen, ohne Microsoft Word oder PowerPoint zu verwenden oder online. Testen Sie schnell den kostenlosen POT-zu-CSV-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: cpp
feature: conversion
informat: FLATOPC
outformat: PPSX
otherformats: POWERPOINT PPSM PPS PPTM POTX POTM PPTX ODP PPT POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Konvertieren von FLATOPC in PPSX oder Online-App" h2="Exportieren Sie FLATOPC in PPSX innerhalb Ihrer C++-Anwendungen, ohne Microsoft Word&reg; oder PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) besteht aus leistungsstarken Dateiautomatisierungs-APIs, die es ermöglichen, die FLATOPC-zu-PPSX-Konvertierung zu automatisieren, während zwei seiner APIs verwendet werden. Laden Sie Ihr FLATOPC mit [Aspose.Words for C++](https://products.aspose.com/words/cpp/) und konvertieren Sie es in HTML, laden Sie dann das HTML über die PowerPoint-Manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), um eine neue Präsentation zu erstellen und als PPSX zu speichern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="FLATOPC-zu-PPSX-Konvertierung auf C++" %}}
1. Öffnen Sie die FLATOPC-Datei mit der Klassenreferenz [Flatopcument](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument).
2. Konvertieren Sie FLATOPC in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.flatopcument#save_stdbasicostream_saveoptions) verwenden
3. Initialisieren Sie ein neues [Präsentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)-Objekt
4. Fügen Sie Ihrer Folie eine AutoForm hinzu, und fügen Sie AddTextFrame darin hinzu
5. Laden Sie den HTML-Inhalt und schreiben Sie ihn in Ihre Präsentationsdatei
6. Speichern Sie das Dokument im PPSX-Format mit der Methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Ppsx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load FLATOPC file with an instance of Flatopcument
Flatopcument flatopcument = new Flatopcument("template.flatopc");
System::SharedPtr<Flatopcument> flatopc = System::MakeObject<Flatopcument>(u"sourceFile.flatopc");
// save the flatopcument in HTML file format
flatopc->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für FLATOPC zu PPSX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=ppsx&from=flatopc" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Laden Sie ein passwortgeschütztes FLATOPC-Dokument über C++" %}}
Abgesehen von der Dokumentenkonvertierung ermöglicht die [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API zahlreiche Funktionen zur Dokumentbearbeitung für C++-Entwickler. Falls Ihr Microsoft Word FLATOPC-Dateiformat passwortgeschützt ist, können Sie es trotzdem über die API öffnen. Um das verschlüsselte Dokument zu laden, können Sie eine spezielle Konstruktorüberladung verwenden, die ein [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)-Objekt akzeptiert. Dieses Objekt enthält die Eigenschaft Password, die die Kennwortzeichenfolge angibt.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected flatopcument, the password is passed to the flatopcument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"flatopcPassword");
// load the flatopcument from the local file system by filename:
SharedPtr<Flatopcument> flatopc = MakeObject<Flatopcument>(u"Encrypted.flatopc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare im PPSX-Dokument über C++ hinzufügen" %}}
Während Sie FLATOPC als PPSX speichern, können Sie auch [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um Ihrem PPSX-Dokument weitere Funktionen hinzuzufügen. Beispielsweise können Sie Ihrer Präsentation Kommentare hinzufügen. Die Präsentationsfolienkommentare sind einem bestimmten Autor zugeordnet. Die Presentation-Klasse enthält die Sammlung von Autoren in ICommentAuthorCollection, die für das Hinzufügen von Folienkommentaren verantwortlich sind. Für jeden Autor gibt es eine Sammlung von Kommentaren in ICommentCollection.
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-powerpoint/" name="FLATOPC Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-ppsm/" name="FLATOPC Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-pps/" name="FLATOPC Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-pptm/" name="FLATOPC Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-potx/" name="FLATOPC Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-potm/" name="FLATOPC Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-pptx/" name="FLATOPC Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-ppsx/" name="FLATOPC Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-ppt/" name="FLATOPC Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/flatopc-to-pot/" name="FLATOPC Zu POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}