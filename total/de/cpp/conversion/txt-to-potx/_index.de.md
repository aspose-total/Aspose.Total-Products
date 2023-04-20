---
title: Konvertieren Sie TXT über C++ in POTX oder mit dem kostenlosen Online Converter
description: Exportieren Sie TXT in POTX in Ihren C++-Anwendungen, ohne Microsoft Word oder PowerPoint zu verwenden oder online. Testen Sie schnell den kostenlosen TXT-zu-POTX-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: POTX
otherformats: PPTM ODP POWERPOINT PPTX PPS PPSM PPT PPSX POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Konvertieren von TXT in POTX oder Online-App" h2="Exportieren Sie TXT in POTX innerhalb Ihrer C++-Anwendungen, ohne Microsoft Word&reg; oder PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) besteht aus leistungsstarken Dateiautomatisierungs-APIs, die es ermöglichen, die TXT-zu-POTX-Konvertierung zu automatisieren, während zwei seiner APIs verwendet werden. Laden Sie Ihr TXT mit [Aspose.Words for C++](https://products.aspose.com/words/cpp/) und konvertieren Sie es in HTML, laden Sie dann das HTML über die PowerPoint-Manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), um eine neue Präsentation zu erstellen und als POTX zu speichern. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TXT-zu-POTX-Konvertierung auf C++" %}}
1. Öffnen Sie die TXT-Datei mit der Klassenreferenz [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument).
2. Konvertieren Sie TXT in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions) verwenden
3. Initialisieren Sie ein neues [Präsentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)-Objekt
4. Fügen Sie Ihrer Folie eine AutoForm hinzu, und fügen Sie AddTextFrame darin hinzu
5. Laden Sie den HTML-Inhalt und schreiben Sie ihn in Ihre Präsentationsdatei
6. Speichern Sie das Dokument im POTX-Format mit der Methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie Potx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Kostenloser Online-Konverter für TXT zu POTX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=txt" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Laden Sie ein passwortgeschütztes TXT-Dokument über C++" %}}
Abgesehen von der Dokumentenkonvertierung ermöglicht die [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API zahlreiche Funktionen zur Dokumentbearbeitung für C++-Entwickler. Falls Ihr Microsoft Word TXT-Dateiformat passwortgeschützt ist, können Sie es trotzdem über die API öffnen. Um das verschlüsselte Dokument zu laden, können Sie eine spezielle Konstruktorüberladung verwenden, die ein [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options)-Objekt akzeptiert. Dieses Objekt enthält die Eigenschaft Password, die die Kennwortzeichenfolge angibt.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Kommentare im POTX-Dokument über C++ hinzufügen" %}}
Während Sie TXT als POTX speichern, können Sie auch [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) verwenden, um Ihrem POTX-Dokument weitere Funktionen hinzuzufügen. Beispielsweise können Sie Ihrer Präsentation Kommentare hinzufügen. Die Präsentationsfolienkommentare sind einem bestimmten Autor zugeordnet. Die Presentation-Klasse enthält die Sammlung von Autoren in ICommentAuthorCollection, die für das Hinzufügen von Folienkommentaren verantwortlich sind. Für jeden Autor gibt es eine Sammlung von Kommentaren in ICommentCollection.
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
// save presentation as Potx
pres->Save(output.potx, Aspose::Slides::Export::SaveFormat::Potx);  
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
              <h2>Häufig gestellte Fragen</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie kann ich TXT in POTX Online konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Online-App für die TXT-Konvertierung finden Sie oben. Um den Konvertierungsprozess zu starten, können Sie die TXT-Datei entweder per Drag & Drop hinzufügen oder in den weißen Bereich klicken, um das Dokument zu importieren. Nachdem Sie die Datei hinzugefügt haben, können Sie einfach auf die Schaltfläche „Konvertieren“ klicken. Nachdem die TXT-zu-POTX-Konvertierung abgeschlossen ist, können Sie Ihre konvertierte Datei mit nur einem Klick herunterladen.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie lange dauert die Konvertierung von TXT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Geschwindigkeit dieses Online-Konverters hängt weitgehend von der Größe der zu konvertierenden TXT-Datei ab. Kleine TXT-Dateien können in wenigen Sekunden in POTX konvertiert werden. Wenn Sie den Konvertierungscode innerhalb einer C++-Anwendung verwenden, hängt die Konvertierungsgeschwindigkeit davon ab, wie gut Sie Ihre Anwendung optimiert haben.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ist es sicher, TXT mit dem kostenlosen Aspose.Total-Konverter in POTX umzuwandeln?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Natürlich! Nachdem Ihre TXT-Datei mit unserem Online-Konverter in POTX konvertiert wurde, ist der Download-Link für die POTX-Datei sofort verfügbar. Wir nehmen die Sicherheit und den Datenschutz Ihrer hochgeladenen Dateien ernst und löschen sie 24 Stunden nach Abschluss des Konvertierungsprozesses. Seien Sie versichert, dass niemand Zugriff auf Ihre Dateien hat. Unser Konvertierungsprozess, einschließlich der TXT-Konvertierung, ist absolut sicher. Wir stellen zu Testzwecken eine kostenlose App zur Verfügung, damit Sie die Ergebnisse überprüfen können, bevor Sie den Code integrieren.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Welchen Browser sollte ich verwenden, um TXT zu konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Für die Online-TXT-Konvertierung können Sie jeden modernen Browser wie Google Chrome, Firefox, Opera oder Safari verwenden. Wenn Sie jedoch eine Desktop-Anwendung entwickeln, wird Aspose.Total TXT Conversion API für eine reibungslose Leistung empfohlen.</span>
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