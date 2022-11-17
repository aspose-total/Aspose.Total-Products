---
title: Konwertuj TXT na PPT za pomocą C++
description: Eksportuj TXT do PPT w aplikacjach C++ bez użycia Microsoft Word lub PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: PPT
otherformats: POT PPTX POTM ODP POTX PPSM POWERPOINT PPSX PPS PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji TXT na PPT" h2="Eksportuj TXT do PPT w swoich aplikacjach C++ bez użycia Microsoft Word&reg; lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) składa się z potężnych API do automatyzacji plików, które pozwalają zautomatyzować konwersję TXT do PPT przy użyciu dwóch jego API. Załaduj dokument TXT za pomocą [Aspose.Words for C++](https://products.aspose.com/words/cpp/) i przekonwertuj go na HTML, a następnie załaduj HTML za pomocą interfejsu API C++ do manipulacji w programie PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby utworzyć nową prezentację i zapisać ją jako PPT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja TXT do PPT w C++" %}}
1. Otwórz plik TXT, korzystając z odwołania do klasy [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument)
2. Konwertuj TXT na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions)
3. Zainicjuj nowy obiekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Dodaj Autokształt do slajdu i dodaj do niego AddTextFrame
5. Załaduj zawartość HTML i zapisz ją w pliku prezentacji
6. Zapisz dokument w formacie PPT za pomocą metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Ppt jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument TXT chroniony hasłem za pomocą C++" %}}
Oprócz konwersji dokumentów, API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia programistom C++ mnóstwo funkcji manipulacji dokumentami. Jeśli format pliku Microsoft Word TXT jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API. Aby załadować zaszyfrowany dokument, możesz użyć specjalnego przeciążenia konstruktora, który akceptuje obiekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Ten obiekt zawiera właściwość Password, która określa ciąg hasła.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Dodaj komentarze w dokumencie PPT za pomocą C++" %}}
Zapisując TXT jako PPT, możesz również użyć [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby dodać kolejne funkcje do swojego dokumentu PPT. Na przykład możesz dodać komentarze do swojej prezentacji. Komentarz do slajdu prezentacji jest powiązany z konkretnym autorem. Klasa Presentation zawiera kolekcję autorów w ICommentAuthorCollection, którzy są pptowiedzialni za dodawanie komentarzy do slajdów. Dla każdego autora istnieje zbiór komentarzy w ICommentCollection.
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
// save presentation as Ppt
pres->Save(output.ppt, Aspose::Slides::Export::SaveFormat::Ppt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-pot/" name="TXT Do POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-pptx/" name="TXT Do PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-potm/" name="TXT Do POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-ppt/" name="TXT Do PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-potx/" name="TXT Do POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-ppsm/" name="TXT Do PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-powerpoint/" name="TXT Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-ppsx/" name="TXT Do PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-pps/" name="TXT Do PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/txt-to-pptm/" name="TXT Do PPTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}