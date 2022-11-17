---
title: Konvertieren Sie RTF über C++ in PPTX
description: Exportieren Sie RTF in PPTX in Ihren C++-Anwendungen, ohne Microsoft Word oder PowerPoint zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: PPTX
otherformats: ODP POT POTX POTM PPS PPT POWERPOINT PPSM PPSX PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Konvertieren von RTF in PPTX" h2="Exportieren Sie RTF in PPTX innerhalb Ihrer C++-Anwendungen, ohne Microsoft Word&reg; oder PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) besteht aus leistungsstarken Dateiautomatisierungs-APIs, die es ermöglichen, die RTF-zu-PPTX-Konvertierung zu automatisieren, während zwei seiner APIs verwendet werden. Laden Sie Ihr RTF mit [Aspose.Words for C++](https://products.aspose.com/words/cpp/) und konvertieren Sie es in HTML, laden Sie dann das HTML über die PowerPoint-Manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), um eine neue Präsentation zu erstellen und als PPTX zu speichern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="RTF-zu-PPTX-Konvertierung auf C++" %}}
1. Öffnen Sie die RTF-Datei mit der Klassenreferenz [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument).
2. Konvertieren Sie RTF in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_stdbasicostream_saveoptions) verwenden
3. Initialisieren Sie ein neues [Präsentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)-Objekt
4. Fügen Sie Ihrer Folie eine AutoForm hinzu, und fügen Sie AddTextFrame darin hinzu
5. Laden Sie den HTML-Inhalt und schreiben Sie ihn in Ihre Präsentationsdatei
6. Speichern Sie das Dokument im PPTX-Format mit der Methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Pptx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load RTF file with an instance of Rtfument
Rtfument rtfument = new Rtfument("template.rtf");
System::SharedPtr<Rtfument> rtf = System::MakeObject<Rtfument>(u"sourceFile.rtf");
// save the rtfument in HTML file format
rtf->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Laden Sie ein passwortgeschütztes RTF-Dokument über C++" %}}
Abgesehen von der Dokumentenkonvertierung ermöglicht die [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API zahlreiche Funktionen zur Dokumentbearbeitung für C++-Entwickler. Falls Ihr Microsoft Word RTF-Dateiformat passwortgeschützt ist, können Sie es trotzdem über die API öffnen. Um das verschlüsselte Dokument zu laden, können Sie eine spezielle Konstruktorüberladung verwenden, die ein [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)-Objekt akzeptiert. Dieses Objekt enthält die Eigenschaft Password, die die Kennwortzeichenfolge angibt.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected rtfument, the password is passed to the rtfument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"rtfPassword");
// load the rtfument from the local file system by filename:
SharedPtr<Rtfument> rtf = MakeObject<Rtfument>(u"Encrypted.rtf", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare im PPTX-Dokument über C++ hinzufügen" %}}
Während Sie RTF als PPTX speichern, können Sie auch [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um Ihrem PPTX-Dokument weitere Funktionen hinzuzufügen. Beispielsweise können Sie Ihrer Präsentation Kommentare hinzufügen. Die Präsentationsfolienkommentare sind einem bestimmten Autor zugeordnet. Die Presentation-Klasse enthält die Sammlung von Autoren in ICommentAuthorCollection, die für das Hinzufügen von Folienkommentaren verantwortlich sind. Für jeden Autor gibt es eine Sammlung von Kommentaren in ICommentCollection.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-pptx/" name="RTF Zu PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-pot/" name="RTF Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-potx/" name="RTF Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-potm/" name="RTF Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-pps/" name="RTF Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-ppt/" name="RTF Zu PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-powerpoint/" name="RTF Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-ppsm/" name="RTF Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-ppsx/" name="RTF Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/rtf-to-pptm/" name="RTF Zu PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}