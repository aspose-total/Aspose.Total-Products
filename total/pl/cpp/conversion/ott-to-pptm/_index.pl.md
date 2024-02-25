---
title: Konwertuj OTT na PPTM za pomocą C++ lub za pomocą bezpłatnego konwertera online
description: Eksportuj OTT do PPTM w aplikacjach C++ bez użycia Microsoft Word lub PowerPoint lub online. Szybko przetestuj darmowy konwerter online OTT na PPTM przed integracją kodu.

family: total
platformtag: cpp
feature: conversion
informat: OTT
outformat: PPTM
otherformats: PPSM PPTX POTX PPS PPT PPSX POWERPOINT POTM ODP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API do konwersji OTT na PPTM lub Aplikacja internetowa" h2="Eksportuj OTT do PPTM w swoich aplikacjach C++ bez użycia Microsoft Word&reg; lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) składa się z potężnych API do automatyzacji plików, które pozwalają zautomatyzować konwersję OTT do PPTM przy użyciu dwóch jego API. Załaduj dokument OTT za pomocą [Aspose.Words for C++](https://products.aspose.com/words/cpp/) i przekonwertuj go na HTML, a następnie załaduj HTML za pomocą interfejsu API C++ do manipulacji w programie PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby utworzyć nową prezentację i zapisać ją jako PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwersja OTT do PPTM w C++" %}}
1. Otwórz plik OTT, korzystając z odwołania do klasy [Ottument](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
2. Konwertuj OTT na HTML za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_stdbasicostream_saveoptions)
3. Zainicjuj nowy obiekt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Dodaj Autokształt do slajdu i dodaj do niego AddTextFrame
5. Załaduj zawartość HTML i zapisz ją w pliku prezentacji
6. Zapisz dokument w formacie PPTM za pomocą metody [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw Pptm jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load OTT file with an instance of Ottument
Ottument ottument = new Ottument("template.ott");
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"sourceFile.ott");
// save the ottument in HTML file format
ott->Save(u"HtmlOutput.HTML");
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

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Darmowy konwerter online dla OTT na PPTM</h3>

<iframe title="Narzędzie online do konwersji pptm na ott" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptm&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Załaduj dokument OTT chroniony hasłem za pomocą C++" %}}
Oprócz konwersji dokumentów, API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) umożliwia programistom C++ mnóstwo funkcji manipulacji dokumentami. Jeśli format pliku Microsoft Word OTT jest chroniony hasłem, nadal możesz go otworzyć za pomocą interfejsu API. Aby załadować zaszyfrowany dokument, możesz użyć specjalnego przeciążenia konstruktora, który akceptuje obiekt [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Ten obiekt zawiera właściwość Password, która określa ciąg hasła.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected ottument, the password is passed to the ottument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"ottPassword");
// load the ottument from the local file system by filename:
SharedPtr<Ottument> ott = MakeObject<Ottument>(u"Encrypted.ott", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Dodaj komentarze w dokumencie PPTM za pomocą C++" %}}
Zapisując OTT jako PPTM, możesz również użyć [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), aby dodać kolejne funkcje do swojego dokumentu PPTM. Na przykład możesz dodać komentarze do swojej prezentacji. Komentarz do slajdu prezentacji jest powiązany z konkretnym autorem. Klasa Presentation zawiera kolekcję autorów w ICommentAuthorCollection, którzy są pptmowiedzialni za dodawanie komentarzy do slajdów. Dla każdego autora istnieje zbiór komentarzy w ICommentCollection.
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
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Często Zadawane Pytania</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jak mogę przekonwertować OTT na PPTM Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Możesz znaleźć aplikację online do konwersji OTT powyżej. Aby rozpocząć proces konwersji, możesz dodać plik OTT, przeciągając go i upuszczając lub klikając wewnątrz białego obszaru, aby zaimportować dokument. Po dodaniu pliku wystarczy kliknąć przycisk „Konwertuj”. Po zakończeniu konwersji OTT do PPTM możesz pobrać przekonwertowany plik jednym kliknięciem.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ile czasu zajmuje konwersja OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Szybkość tego konwertera online zależy w dużej mierze od rozmiaru konwertowanego pliku OTT. Małe pliki OTT można przekonwertować na format PPTM w ciągu zaledwie kilku sekund. Jeśli używasz kodu konwersji w aplikacji C++, szybkość konwersji będzie zależeć od tego, jak dobrze zoptymalizowałeś swoją aplikację.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Czy konwersja OTT na PPTM za pomocą darmowego konwertera Aspose.Total jest bezpieczna?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Oczywiście! Po przekonwertowaniu pliku OTT do formatu PPTM za pomocą naszego konwertera online link do pobrania pliku PPTM będzie natychmiast dostępny. Poważnie traktujemy bezpieczeństwo i prywatność przesłanych przez Ciebie plików i usuwamy je 24 godziny po zakończeniu procesu konwersji. Możesz mieć pewność, że nikt nie będzie miał dostępu do Twoich plików. Nasz proces konwersji, w tym konwersja OTT, jest całkowicie bezpieczny. Udostępniamy bezpłatną aplikację do celów testowych, dzięki czemu możesz zweryfikować wyniki przed integracją kodu.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Jakiej przeglądarki powinienem użyć do konwersji OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Do konwersji OTT online możesz użyć dowolnej nowoczesnej przeglądarki, takiej jak Google Chrome, Firefox, Opera lub Safari. Jeśli jednak tworzysz aplikację komputerową, zalecany jest Aspose.Total OTT Conversion API w celu zapewnienia płynnej wydajności.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}