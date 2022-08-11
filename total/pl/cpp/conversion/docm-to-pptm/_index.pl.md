---
title: Konwertuj DOCM na PPTM za pomocą C++
description: Eksportuj DOCM do PPTM w aplikacjach C++ bez użycia Microsoft Word lub PowerPoint
url: /pl/cpp/conversion/docm-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: PPTM
otherformats: PPT POTM PPSM ODP PPSX PPS POT POWERPOINT POTX PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji DOCM na PPTM" h2="Eksportuj DOCM do PPTM w swoich aplikacjach C++ bez użycia Microsoft Word&reg; lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) składa się z potężnych API do automatyzacji plików, które pozwalają zautomatyzować konwersję DOCM do PPTM przy użyciu dwóch jego API. Załaduj dokument DOCM za pomocą [Aspose.Words for C++](https://products.aspose.com/words/cpp/) i przekonwertuj go na HTML, a następnie załaduj HTML za pomocą interfejsu API C++ do manipulacji w programie PowerPoint [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/), aby utworzyć nową prezentację i zapisać ją jako PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja DOCM do PPTM w C++" %}}
1. Otwórz plik DOCM, korzystając z odwołania do klasy [Docmument](https://reference.aspose.com/words/cpp/class/aspose.words.docmument)
2. Konwertuj DOCM na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions)
3. Zainicjuj nowy obiekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Dodaj Autokształt do slajdu i dodaj do niego AddTextFrame
5. Załaduj zawartość HTML i zapisz ją w pliku prezentacji
6. Zapisz dokument w formacie PPTM za pomocą metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Pptm jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCM file with an instance of Docmument
Docmument docmument = new Docmument("template.docm");
System::SharedPtr<Docmument> docm = System::MakeObject<Docmument>(u"sourceFile.docm");
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument DOCM chroniony hasłem za pomocą C++" %}}
Oprócz konwersji dokumentów, API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia programistom C++ mnóstwo funkcji manipulacji dokumentami. Jeśli format pliku Microsoft Word DOCM jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API. Aby załadować zaszyfrowany dokument, możesz użyć specjalnego przeciążenia konstruktora, który akceptuje obiekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Ten obiekt zawiera właściwość Password, która określa ciąg hasła.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Docmument> docm = MakeObject<Docmument>(u"Encrypted.docm", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Dodaj komentarze w dokumencie PPTM za pomocą C++" %}}
Zapisując DOCM jako PPTM, możesz również użyć [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby dodać kolejne funkcje do swojego dokumentu PPTM. Na przykład możesz dodać komentarze do swojej prezentacji. Komentarz do slajdu prezentacji jest powiązany z konkretnym autorem. Klasa Presentation zawiera kolekcję autorów w ICommentAuthorCollection, którzy są pptmowiedzialni za dodawanie komentarzy do slajdów. Dla każdego autora istnieje zbiór komentarzy w ICommentCollection.
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
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-ppt/" name="DOCM Do PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-potm/" name="DOCM Do POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-ppsm/" name="DOCM Do PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-pptm/" name="DOCM Do PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-ppsx/" name="DOCM Do PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-pps/" name="DOCM Do PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-pot/" name="DOCM Do POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-powerpoint/" name="DOCM Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-potx/" name="DOCM Do POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/docm-to-pptx/" name="DOCM Do PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}