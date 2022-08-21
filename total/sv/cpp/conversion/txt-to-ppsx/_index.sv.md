---
title: Konvertera TXT till PPSX via C++
description: Exportera TXT till PPSX i dina C++-applikationer utan att använda Microsoft Word eller PowerPoint
url: /sv/cpp/conversion/txt-to-ppsx/
family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: PPSX
otherformats: PPTM ODP PPT POT POTX POWERPOINT PPTX PPS POTM PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att konvertera TXT till PPSX" h2="Exportera TXT till PPSX i dina C++-program utan att använda Microsoft Word&reg; eller PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) består av kraftfulla filautomatiserings-API:er som gör det möjligt att automatisera TXT till PPSX-konvertering samtidigt som två av dess API:er används. Ladda ditt dokument med [Aspose.Words for C++](https://products.aspose.com/words/cpp/) och konvertera det till HTML, ladda sedan HTML-koden via PowerPoint-manipulation C++ API [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) för att skapa en ny presentation och spara den som PPSX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="TXT till PPSX-konvertering på C++" %}}
1. Öppna TXT-filen med [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument) klassreferens
2. Konvertera TXT till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions)
3. Initiera ett nytt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objekt
4. Lägg till en AutoShape i din bild och lägg till AddTextFrame i den
5. Ladda HTML-innehållet och skriv det i din presentationsfil
6. Spara dokumentet i PPSX-format med metoden [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) och ställ in Ppsx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
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
// save presentation as Ppsx
pres->Save(output.ppsx, Aspose::Slides::Export::SaveFormat::Ppsx);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ladda lösenordsskyddat TXT-dokument via C++" %}}
Förutom dokumentkonvertering tillåter [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API massor av dokumentmanipuleringsfunktioner för C++-utvecklare. Om ditt Microsoft Word TXT-filformat är lösenordsskyddat kan du fortfarande öppna det med API:et. För att ladda det krypterade dokumentet kan du använda en speciell konstruktoröverbelastning, som accepterar ett [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objekt. Detta objekt innehåller egenskapen Password, som anger lösenordssträngen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till kommentarer i PPSX-dokument via C++" %}}
Medan du sparar TXT som PPSX kan du också använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) för att lägga till ytterligare funktioner i ditt PPSX-dokument. Du kan till exempel lägga till kommentarer i din presentation. Presentationsbildkommentaren är kopplad till en viss författare. Klassen Presentation innehåller samlingen av författare i ICommentAuthorCollection som är ansvariga för att lägga till bildkommentarer. För varje författare finns det en samling kommentarer i ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-pptm/" name="TXT Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-ppsx/" name="TXT Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-ppt/" name="TXT Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-pot/" name="TXT Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-potx/" name="TXT Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-powerpoint/" name="TXT Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-pptx/" name="TXT Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-pps/" name="TXT Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-potm/" name="TXT Till POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/txt-to-ppsm/" name="TXT Till PPSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}