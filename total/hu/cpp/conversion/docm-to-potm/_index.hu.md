---
title: A DOCM konvertálása POTM-re C++ segítségével vagy ingyenes online konverterrel
description: Exportáljon DOCM-t POTM-be C++-alkalmazásaiban Microsoft Word of PowerPoint használata nélkül vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes DOCM-POTM online konvertert.

family: total
platformtag: cpp
feature: conversion
informat: DOCM
outformat: POTM
otherformats: ODP PPS POT PPT PPSX PPTM PPTX POWERPOINT POTX PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API a DOCM konvertálásához POTM-vé vagy Online App" h2="DOCM exportálása POTM-be a C++-alkalmazásokon belül a Microsoft Word&reg; vagy PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for C++](https://products.aspose.com/total/cpp/) olyan hatékony fájlautomatizálási API-kból áll, amelyek lehetővé teszik a DOCM- POTM-konverzió automatizálását, miközben két API-t használ. Töltse be a DOCM-t az [Aspose.Words for C++] segítségével (https://products.aspose.com/words/cpp/), konvertálja HTML-vé, majd töltse be a HTML-t a PowerPoint manipulációs C++ API-n keresztül [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) új prezentáció létrehozásához és POTM-ként mentéséhez. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="DOCM konvertálás POTM-be C++-on" %}}
1. Nyissa meg a DOCM-fájlt a [Document](https://reference.aspose.com/words/cpp/class/aspose.words.docmument) osztályhivatkozás használatával
2. Alakítsa át a DOCM-t HTML-vé a [Mentés](https://reference.aspose.com/words/cpp/class/aspose.words.docmument#save_stdbasicostream_saveoptions) tagfüggvény használatával
3. Inicializáljon egy új [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) objektumot
4. Adjon hozzá egy AutoShape-ot a diához, és adja hozzá az AddTextFrame-et
5. Töltse be a HTML tartalmat, és írja be a bemutató fájlba
6. Mentse a dokumentumot POTM formátumba a [Mentés](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) módszerrel, és állítsa be az Potm-t SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total.Cpp```ként, vagy a Visual Studio csomagkezelő konzolján keresztül az ```Install-Package Aspose.Total.Cpp``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/cpp) webhelyről.
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Ingyenes online konverter DOCM-hez POTM-be</h3>

<iframe title="docm-ból potm-be konvertáló online eszköz" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=potm&from=docm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Töltsön be jelszóval védett DOCM-dokumentumot C++-on keresztül" %}}
A dokumentumok konvertálásán kívül az [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API rengeteg dokumentumkezelési funkciót tesz lehetővé a C++ fejlesztői számára. Ha a Microsoft Word DOCM fájlformátuma jelszóval védett, akkor is megnyithatja az API használatával. A titkosított dokumentum betöltéséhez használhat egy speciális konstruktor túlterhelést, amely elfogad egy [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options) objektumot. Ez az objektum tartalmazza a Jelszó tulajdonságot, amely a jelszó karakterláncot adja meg.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected docmument, the password is passed to the docmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docmPassword");
// load the docmument from the local file system by filename:
SharedPtr<Document> docm = MakeObject<Document>(u"Encrypted.docm", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Megjegyzések hozzáadása az POTM-dokumentumhoz C++-on keresztül" %}}
Miközben a DOCM-t POTM-ként menti, az [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) segítségével további funkciókat is hozzáadhat POTM-dokumentumához. Például megjegyzéseket fűzhet a prezentációjához. A bemutató dia megjegyzései egy adott szerzőhöz vannak társítva. A Prezentáció osztály az ICommentAuthorCollection gyűjteményét tartalmazza azon szerzők gyűjteményében, amelyek a diák megjegyzéseinek hozzáadásáért felelősek. Minden szerzőhöz van egy megjegyzésgyűjtemény az ICommentCollectionben.
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
// save presentation as Potm
pres->Save(output.potm, Aspose::Slides::Export::SaveFormat::Potm);  
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
              <h2>Gyakran Ismételt Kérdések</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Hogyan konvertálhatom a DOCM-t POTM Online formátumba?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">A DOCM konverziós online alkalmazást fent találja. Az átalakítási folyamat elindításához hozzáadhatja a DOCM-fájlt húzással vagy a fehér területre kattintva a dokumentum importálásához. Miután hozzáadta a fájlt, egyszerűen kattintson a "Konvertálás" gombra. A DOCM-POTM átalakítás befejezése után egyetlen kattintással letöltheti az átalakított fájlt.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mennyi ideig tart a DOCM konvertálása?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ennek az online konverternek a sebessége nagyban függ a konvertálandó DOCM fájl méretétől. A kisméretű DOCM fájlok néhány másodperc alatt POTM formátumba konvertálhatók. Ha a konverziós kódot egy C++-alkalmazáson belül használja, a konverziós sebesség attól függ, hogy mennyire optimalizálta az alkalmazást.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Biztonságos a DOCM konvertálása POTM formátumba az ingyenes Aspose.Total konverter segítségével?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Természetesen! Miután a DOCM fájlt POTM formátumba konvertálta online konverterünk segítségével, a POTM fájl letöltési linkje azonnal elérhető lesz. Komolyan vesszük feltöltött fájljai biztonságát és adatvédelmét, és a konvertálási folyamat befejezése után 24 órával töröljük őket. Biztos lehet benne, hogy senki sem fog hozzáférni a fájljaihoz. Konverziós folyamatunk, beleértve a DOCM átalakítást is, teljesen biztonságos. Ingyenes alkalmazást biztosítunk tesztelési célokra, így ellenőrizheti az eredményeket a kód integrálása előtt.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Milyen böngészőt használjak a DOCM konvertálásához?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Az online DOCM konverzióhoz bármilyen modern böngészőt használhat, például Google Chrome, Firefox, Opera vagy Safari. Ha azonban asztali alkalmazást fejleszt, az Aspose.Total DOCM Conversion API ajánlott a zökkenőmentes teljesítmény érdekében.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}