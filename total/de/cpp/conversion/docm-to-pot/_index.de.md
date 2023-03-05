---
title: Konvertieren Sie DOCM über C++ in POT oder mit dem kostenlosen Online Converter
description: Exportieren Sie DOCM in POT in Ihren C++-Anwendungen, ohne Microsoft Word oder PowerPoint zu verwenden oder online. Testen Sie schnell den kostenlosen POT-zu-CSV-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: POT
otherformats: PPTX PPT PPS PPSX POWERPOINT POTX POTM ODP PPTM PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Konvertieren von DOCM in POT oder Online-App" h2="Exportieren Sie DOCM in POT innerhalb Ihrer C++-Anwendungen, ohne Microsoft Word&reg; oder PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) besteht aus leistungsstarken Dateiautomatisierungs-APIs, die es ermöglichen, die DOCM-zu-POT-Konvertierung zu automatisieren, während zwei seiner APIs verwendet werden. Laden Sie Ihr DOCM mit [Aspose.Words for C++](https://products.aspose.com/words/cpp/) und konvertieren Sie es in HTML, laden Sie dann das HTML über die PowerPoint-Manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), um eine neue Präsentation zu erstellen und als POT zu speichern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCM-zu-POT-Konvertierung auf C++" %}}
1. Öffnen Sie die DOCM-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument).
2. Konvertieren Sie DOCM in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions) verwenden
3. Initialisieren Sie ein neues [Präsentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)-Objekt
4. Fügen Sie Ihrer Folie eine AutoForm hinzu, und fügen Sie AddTextFrame darin hinzu
5. Laden Sie den HTML-Inhalt und schreiben Sie ihn in Ihre Präsentationsdatei
6. Speichern Sie das Dokument im POT-Format mit der Methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Pot als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCM file with an instance of Document
Document docmument = new Document("template.docm");
System::SharedPtr<Document> docm = System::MakeObject<Document>(u"sourceFile.docm");
// save the docmument in HTML file format
docm->Save(u"HtmlOutput.HTML");
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
<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für DOCM zu POT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pot&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Laden Sie ein passwortgeschütztes DOCM-Dokument über C++" %}}
Abgesehen von der Dokumentenkonvertierung ermöglicht die [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API zahlreiche Funktionen zur Dokumentbearbeitung für C++-Entwickler. Falls Ihr Microsoft Word DOCM-Dateiformat passwortgeschützt ist, können Sie es trotzdem über die API öffnen. Um das verschlüsselte Dokument zu laden, können Sie eine spezielle Konstruktorüberladung verwenden, die ein [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)-Objekt akzeptiert. Dieses Objekt enthält die Eigenschaft Password, die die Kennwortzeichenfolge angibt.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Document> docm = MakeObject<Document>(u"Encrypted.docm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare im POT-Dokument über C++ hinzufügen" %}}
Während Sie DOCM als POT speichern, können Sie auch [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um Ihrem POT-Dokument weitere Funktionen hinzuzufügen. Beispielsweise können Sie Ihrer Präsentation Kommentare hinzufügen. Die Präsentationsfolienkommentare sind einem bestimmten Autor zugeordnet. Die Presentation-Klasse enthält die Sammlung von Autoren in ICommentAuthorCollection, die für das Hinzufügen von Folienkommentaren verantwortlich sind. Für jeden Autor gibt es eine Sammlung von Kommentaren in ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-pptx/" name="DOCM Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-ppt/" name="DOCM Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-pps/" name="DOCM Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-ppsx/" name="DOCM Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-powerpoint/" name="DOCM Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-potx/" name="DOCM Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-potm/" name="DOCM Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-pot/" name="DOCM Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-pptm/" name="DOCM Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/docm-to-ppsm/" name="DOCM Zu PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}