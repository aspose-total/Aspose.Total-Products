---
title: Konvertera DOCX till POTX via C++ eller med gratis Online Converter
description: Exportera DOCX till POTX i dina C++-applikationer utan att använda Microsoft Word eller PowerPoint eller online. Testa gratis DOCX till POTX online-omvandlare snabbt innan du integrerar koden.

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: POTX
otherformats: PPTX PPSX POTM ODP PPS PPSM PPT POT POWERPOINT PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API för att konvertera DOCX till POTX eller onlineapp" h2="Exportera DOCX till POTX i dina C++-program utan att använda Microsoft Word&reg; eller PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) består av kraftfulla filautomatiserings-API:er som gör det möjligt att automatisera DOCX till POTX-konvertering samtidigt som två av dess API:er används. Ladda ditt dokument med [Aspose.Words for C++](https://products.aspose.com/words/cpp/) och konvertera det till HTML, ladda sedan HTML-koden via PowerPoint-manipulation C++ API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) för att skapa en ny presentation och spara den som POTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCX till POTX-konvertering på C++" %}}
1. Öppna DOCX-filen med [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klassreferens
2. Konvertera DOCX till HTML genom att använda medlemsfunktionen [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Initiera ett nytt [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objekt
4. Lägg till en AutoShape i din bild och lägg till AddTextFrame i den
5. Ladda HTML-innehållet och skriv det i din presentationsfil
6. Spara dokumentet i POTX-format med metoden [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) och ställ in Potx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total.Cpp``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total.Cpp```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCX file with an instance of Document
Document document = new Document("template.docx");
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"sourceFile.docx");
// save the document in HTML file format
docx->Save(u"HtmlOutput.HTML");
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

<h3>Gratis onlinekonverterare för DOCX till POTX</h3>

<iframe title="docx till potx Conversion Online Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potx&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Ladda lösenordsskyddat DOCX-dokument via C++" %}}
Förutom dokumentkonvertering tillåter [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API massor av dokumentmanipuleringsfunktioner för C++-utvecklare. Om ditt Microsoft Word DOCX-filformat är lösenordsskyddat kan du fortfarande öppna det med API:et. För att ladda det krypterade dokumentet kan du använda en speciell konstruktoröverbelastning, som accepterar ett [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objekt. Detta objekt innehåller egenskapen Password, som anger lösenordssträngen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docxPassword");
// load thDocumentnt from the local fiDocument by filename:
SharedPtr<Docxument> docx = MakeObject<Docxument>(u"Encrypted.docx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Lägg till kommentarer i POTX-dokument via C++" %}}
Medan du sparar DOCX som POTX kan du också använda [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) för att lägga till ytterligare funktioner i ditt POTX-dokument. Du kan till exempel lägga till kommentarer i din presentation. Presentationsbildkommentaren är kopplad till en viss författare. Klassen Presentation innehåller samlingen av författare i ICommentAuthorCollection som är ansvariga för att lägga till bildkommentarer. För varje författare finns det en samling kommentarer i ICommentCollection.
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
              <h2>Vanliga frågor</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur kan jag konvertera DOCX till POTX Online?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Du hittar onlineappen för DOCX-konvertering ovan. För att starta konverteringsprocessen kan du lägga till DOCX-filen antingen genom att dra och släppa den eller genom att klicka i det vita området för att importera dokumentet. När du har lagt till filen kan du helt enkelt klicka på knappen "Konvertera". När DOCX till POTX-konverteringen är klar kan du ladda ner din konverterade fil med bara ett klick.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hur lång tid tar det att konvertera DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Hastigheten på denna onlinekonverterare beror till stor del på storleken på DOCX-filen som konverteras. Små DOCX-filer kan konverteras till POTX på bara några sekunder. Om du använder konverteringskoden i en C++-applikation kommer konverteringshastigheten att bero på hur väl du har optimerat din applikation.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Är det säkert att konvertera DOCX till POTX med gratis Aspose.Total-omvandlare?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Självklart! Efter att din DOCX-fil har konverterats till POTX med vår onlinekonverterare, kommer nedladdningslänken för POTX-filen att vara tillgänglig omedelbart. Vi tar säkerheten och integriteten för dina uppladdade filer på allvar och raderar dem 24 timmar efter att konverteringsprocessen är klar. Var säker, ingen kommer att ha tillgång till dina filer. Vår konverteringsprocess, inklusive DOCX-konvertering, är helt säker. Vi tillhandahåller en gratis app för teständamål så att du kan verifiera resultaten innan du integrerar koden.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Vilken webbläsare ska jag använda för att konvertera DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">För online DOCX-konvertering kan du använda vilken modern webbläsare som helst, som Google Chrome, Firefox, Opera eller Safari. Men om du utvecklar ett skrivbordsprogram rekommenderas Aspose.Total DOCX Conversion API för smidig prestanda.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}