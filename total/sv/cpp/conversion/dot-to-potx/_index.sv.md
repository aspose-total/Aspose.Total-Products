---
title: Konvertera DOT till POTX via C++
description: Exportera DOT till POTX i dina C++-applikationer utan att använda Microsoft Word eller PowerPoint
url: /sv/cpp/conversion/dot-to-potx/
family: total
platformtag: cpp
feature: conversion
informat: DOT
outformat: POTX
otherformats: POT PPSX PPTX PPSM PPTM PPT PPS POWERPOINT ODP POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att konvertera DOT till POTX" h2="Exportera DOT till POTX i dina C++-program utan att använda Microsoft Word&reg; eller PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) består av kraftfulla filautomatiserings-API:er som gör det möjligt att automatisera DOT till POTX-konvertering samtidigt som två av dess API:er används. Ladda ditt dokument med [Aspose.Words for C++](https://products.aspose.com/words/cpp/) och konvertera det till HTML, ladda sedan HTML-koden via PowerPoint-manipulation C++ API [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) för att skapa en ny presentation och spara den som POTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOT till POTX-konvertering på C++" %}}
1. Öppna DOT-filen med [Dotument](https://reference.aspose.com/words/cpp/class/aspose.words.dotument) klassreferens
2. Konvertera DOT till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_stdbasicostream_saveoptions)
3. Initiera ett nytt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objekt
4. Lägg till en AutoShape i din bild och lägg till AddTextFrame i den
5. Ladda HTML-innehållet och skriv det i din presentationsfil
6. Spara dokumentet i POTX-format med metoden [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) och ställ in Potx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOT file with an instance of Dotument
Dotument dotument = new Dotument("template.dot");
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"sourceFile.dot");
// save the dotument in HTML file format
dot->Save(u"HtmlOutput.HTML");
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

{{% blocks/products/pf/feature-page-section  h2="Ladda lösenordsskyddat DOT-dokument via C++" %}}
Förutom dokumentkonvertering tillåter [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API massor av dokumentmanipuleringsfunktioner för C++-utvecklare. Om ditt Microsoft Word DOT-filformat är lösenordsskyddat kan du fortfarande öppna det med API:et. För att ladda det krypterade dokumentet kan du använda en speciell konstruktoröverbelastning, som accepterar ett [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objekt. Detta objekt innehåller egenskapen Password, som anger lösenordssträngen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotument, the password is passed to the dotument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotPassword");
// load the dotument from the local file system by filename:
SharedPtr<Dotument> dot = MakeObject<Dotument>(u"Encrypted.dot", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till kommentarer i POTX-dokument via C++" %}}
Medan du sparar DOT som POTX kan du också använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) för att lägga till ytterligare funktioner i ditt POTX-dokument. Du kan till exempel lägga till kommentarer i din presentation. Presentationsbildkommentaren är kopplad till en viss författare. Klassen Presentation innehåller samlingen av författare i ICommentAuthorCollection som är ansvariga för att lägga till bildkommentarer. För varje författare finns det en samling kommentarer i ICommentCollection.
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
{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-pot/" name="DOT Till POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-ppsx/" name="DOT Till PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-pptx/" name="DOT Till PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-ppsm/" name="DOT Till PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-pptm/" name="DOT Till PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-ppt/" name="DOT Till PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-pps/" name="DOT Till PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-powerpoint/" name="DOT Till POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-potx/" name="DOT Till POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/conversion/dot-to-potm/" name="DOT Till POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}