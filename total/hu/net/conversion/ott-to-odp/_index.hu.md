---
title: A OTT konvertálása ODP-re C# .NET-en keresztül vagy ingyenes online konverterrel
description: Konvertálja a Word ott dokumentumokat PowerPoint odp fájlokká C# segítségével. Több fájl konvertálása az ASP.NET-en vagy más .NET-alkalmazásokon belül.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="A OTT konvertálása ODP-vé a C# használatával vagy online" h2="A Microsoft Word OTT-ból PowerPoint ODP-konverziós alkalmazásokat készíthet .NET-keretrendszer, .NET Core, Windows Azure, Mono vagy Xamarin platformokon." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODP" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DOCM" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="OTT konvertálása ODP-vé C# használatával" %}}

A Word-dokumentumfájlok PowerPoint odp prezentáció kötegelt konvertálásának folyamatának automatizálása érdekében az [Aspose.Words for .NET](https://products.aspose.com/words/net) és az [Aspose.Slides .NET](https://products.aspose.com/slides/net) API-khoz. Az előbbi egy szövegszerkesztő API a Microsoft Word dokumentumok feldolgozására vagy manipulálására. Míg az utóbbi egy prezentáció-manipulációs API, amely lehetővé teszi a Microsoft PowerPoint diák létrehozását vagy módosítását. Mindkét API az [Aspose.Total for .NET](https://products.aspose.com/total/net) csomag része. Közvetlenül [letöltheti](https://releases.aspose.com/) a Nugetből, vagy használhatja a következő parancsokat a Package Manager konzolból.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzolparancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések a OTT konvertálásához ODP-vé C# segítségével" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

1. Adja hozzá az Aspose.Total hivatkozását a .NET-hez
1. Töltse be a OTT-fájlt az [Aspose.Words.Document](https://apireference.aspose.com/words/net/aspose.words/document) osztály használatával
1. Mentse el a OTT dokumentumot HTML formátumba
1. Hozzon létre [Aspose.Slides.Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) objektumot
1. Importáljon HTML-tartalmat bármilyen dia alakú szövegkeretbe a prezentáción belül
1. Mentse a dokumentumot az [Aspose.Slides.Presentation.Save("output.odp", SaveFormat.Odp)](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods) segítségével /5)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows vagy kompatibilis operációs rendszer .NET-keretrendszerrel, .NET Core-val, Windows Azure-val, Mono- vagy Xamarin-platformokkal.
- Fejlesztői környezet, mint a Microsoft Visual Studio.
- Aspose.Words for .NET &amp; Aspose.Slides .NET DLL-ekhez vagy Aspose.Total .NET DLL-hez, amelyre a projektben hivatkozik.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a kódminta bemutatja, hogyan lehet OTT-t ODP-vé konvertálni C# használatával" offSpacer="" %}}

```cs
// Load the Single Page Microsoft Word OTT file
Aspose.Words.Document ott = new Aspose.Words.Document("sourceWordFile.ott");

// Save OTT file to HTML 
ott.Save("filepath\\test.html", SaveFormat.Html);

// To convert multi pages OTT documents, export each page to HTML separately using Aspose.Words and then use the below code to convert to ODP.

using (Presentation odp = new Presentation()){

	// Access the default first slide of presentation
	ISlide slide = pres.Slides[0];

	// Adding the AutoShape to accomodate the HTML content 
	// Adjust it as of your need
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Adding text frame to the shape
	ashape.AddTextFrame("");

	// Clearing all paragraphs in added text frame
	ashape.TextFrame.Paragraphs.Clear();

	// Loading the HTML file using stream reader
	TextReader tr = new StreamReader("filepath\\test.html");

	// Adding text from HTML stream reader in text frame
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Save the ODP Presentation
	odp.Save("filepath\\pres.odp", Aspose.Slides.Export.SaveFormat.Odp);

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online konverter OTT-hez ODP-be</h3>

<iframe title="ott-ból odp-be konvertáló online eszköz" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odp&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ingyenes alkalmazás a OTT konvertálásához ODP-vé" sectionDescription="" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your DOCM file and hit the \"Convert\" button." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will instantly get the download link for resultant ODP file." >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->
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
                          <span itemprop="name"><b>Hogyan konvertálhatom a OTT-t ODP Online formátumba?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">A OTT konverziós online alkalmazás a fentiekben be van építve. Az alkalmazás használatához hozzáadhatja OTT-fájlját úgy, hogy húzza a kijelölt fehér területre, vagy kattintson a területen belülre a dokumentum importálásához. Ezután nyomja meg a Konvertálás gombot az átalakítási folyamat elindításához. Miután a OTT-ből ODP-be konvertálás befejeződött, egyetlen kattintással letöltheti az újonnan konvertált fájlt, és ODP-fájl formájában elérhető lesz az Ön számára.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mennyi ideig tart a OTT konvertálása?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ez az online konverter gyorsan működik, de elsősorban a konvertálandó OTT fájl méretétől függ. Kisebb OTT fájlok esetén a ODP formátumba konvertálás pillanatok alatt elvégezhető. Ha azonban a konverziós kódot egy .NET-alkalmazásba integrálta, a konverziós sebesség attól függ, hogy az alkalmazás mennyire van optimalizálva a konverziós folyamathoz.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Biztonságos a OTT konvertálása ODP formátumba az ingyenes Aspose.Total konverter segítségével?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Természetesen! Amint a OTT-ből ODP-be konvertálás befejeződött, az újonnan konvertált ODP-fájl letöltési linkje azonnal elérhető lesz. Az átalakítási folyamat biztonságát is biztosítja, mivel minden feltöltött fájl, beleértve a OTT fájlokat is, teljesen biztonságos, és 24 óra elteltével törlődik a rendszerből. Ezen túlmenően a letöltési hivatkozások ezen időszak letelte után leállnak, így biztosítva a fájlok adatvédelmét és védelmét. Az integrált alkalmazás ingyenesen használható, és tesztelési célokra készült, így a felhasználók értékelhetik az eredményeket, mielőtt a kódot integrálnák projektjeikbe.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Milyen böngészőt használjak a OTT konvertálásához?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bármilyen modern webböngészőt használhat, például a Google Chrome-ot, a Firefoxot, az Opera-t vagy a Safarit az online OTT-ből ODP-be konvertálásához. Ha azonban asztali alkalmazást fejleszt, az Aspose.Total OTT Conversion API ajánlott a zökkenőmentes és hatékony feldolgozás érdekében.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}