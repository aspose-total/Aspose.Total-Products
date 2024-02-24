---
title: Távolítsa el a Word Annotation Online-t vagy kezelje a megjegyzéseket .NET-en keresztül
description: ingyenesen törölje a megjegyzéseket a Word fájlból az online alkalmazáson keresztül..NET API kód a Word fájlok megjegyzéseinek kezeléséhez.

family: total
platformtag: net
feature: Annotate
informat: Word
otherformats: DOC DOT DOCX DOCM DOTX DOTM RTF WORD PDF XLS XLSX XLSB XLSM XLT XLTX XLTM CSV TSV ODS EXCEL PPT PPS PPTX POTX PPSX PPTM PPSM POTM ODP POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header-widget h1="Törölje a megjegyzéseket a Word Document Online szolgáltatásból, vagy kezelje a .NET-en keresztül" h2="Hatékony .NET alapú Word dokumentum annotációs segédprogram fejlesztése.A Word fájl megjegyzéseinek .NET-en keresztüli kezeléséhez felsorolt kód." >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Távolítsa el a Word megjegyzéseket online" %}}

1. Importáljon Word fájlt a megjegyzések feltöltésével való törléséhez
1. Ehhez kattintson a ledobási területen belülre a megjegyzés alkalmazás húzásával
1. A Word fájl méretétől és az internet sebességétől függően várjon néhány másodpercet
1. Kattintson az "Eltávolítás" gombra a megjegyzések törléséhez
1. Azonnal töltse le a fájlt

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Adott szerző Word dokumentum megjegyzéseinek törlése .NET-en keresztül" %}}

1. Adjon hozzá könyvtári hivatkozást a .NET projekthez
1. Dokumentum betöltése a Dokumentum osztály objektumon keresztül
1. Az összes csomópont megjegyzését a GetChildNodes NodeType.Comment funkcióval kapja meg
1. Ismételje meg az összes megjegyzést, és egyeztesse a szerző nevével
1. Hívja az Eltávolítás metódust az adott szerző megjegyzésének törléséhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title="C# kód: Adott szerzői megjegyzések törlése a Word fájlból" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "remove-comments-of-a-specific-author-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Megjegyzések hozzáadása a .NET-en keresztül" %}}

1. Dokumentum osztály objektum létrehozása
1. Használja a Megjegyzés osztályt
1. Adja hozzá az új bekezdést a Bekezdések.Hozzáadás segítségével
1. Használja a FirstParagraph.Runs.Add parancsot, és adja hozzá a megjegyzést
1. Vagy a másik módszer a CommentRangeStart és CommentRangeEnd osztályok használata
1. Hívja a mentési módot a megjegyzésekkel ellátott fájl mentéséhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kivonat az összes megjegyzésből" %}}

1. Dokumentum betöltése a Dokumentum osztály objektumon keresztül
1. Hozzon létre egy ArrayList objektumot
1. Szerezze be az összes GetChildNode-ot a NodeCollection-ben
1. Ismételje meg az egyes gyűjteményeket, és adjon hozzá megjegyzéseket az ArrayListhez

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/code-block title=".NET kód: Megjegyzés hozzáadása a Word fájlból" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "add-comments-in-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="C# Code: Kivonat az összes megjegyzésből" offSpacer="" %}}

{{< gist "aspose-com-gists" "8705a5d67f7352e82188cb2dbe511bc6" "extract-all-comments-from-word-documents.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{% blocks/products/pf/feature-page-summary %}}


<h2>Word dokumentum-annotációs alkalmazás fejlesztése .NET-en keresztül</h2>

Word annotációs alkalmazást vagy segédprogramot kell fejlesztenie, hogy visszajelzést adjon, javaslatokat tegyen, vagy együttműködjön másokkal a dokumentumon?A [Aspose.Words for .NET](https://products.aspose.com/words/net/)-tal a [Aspose.Total for .NET](https://products.aspose.com/total/net/) gyermek API-jával bármely .NET-fejlesztő integrálhatja a fenti API-kódot dokumentumannotációs alkalmazásába.A hatékony .NET-könyvtár lehetővé teszi bármilyen dokumentum-annotációs megoldás programozását.Ezenkívül számos népszerű formátumot támogat, beleértve a Word formátumot.<br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET-könyvtár a Word-fájlok megjegyzéseivel" %}}

Három alternatív lehetőség van a "Aspose.Words for .NET" vagy "Aspose.Total for .NET" telepítésére a rendszerre.Kérjük, válasszon egyet, amely megfelel az Ön igényeinek, és kövesse a lépésről lépésre található utasításokat:<br /><br />

- Telepítsen egy [NuGet Package](https://www.nuget.org/packages/Aspose.Words/)-at. Lásd [Documentation](https://docs.aspose.com/words/net/installation/#install-or-update-aspose-words-for-net-using-nuget)
- Telepítse a könyvtárat a [Package Manager Console](https://docs.aspose.com/words/net/installation/#install-or-update-asposewords-using-package-manager-console) használatával a Visual Studio IDE-n belül
- Telepítse a könyvtárat kézzel a [Windows Installer](https://docs.aspose.com/words/net/installation/#install-asposewords-for-net-using-installer) használatával

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="rendszerkövetelmények" %}}

Termékünk teljes mértékben platformfüggetlen, és támogatja az összes főbb .NET implementációt a „.NET Standard 2.0” specifikációt követve:<br /><br />

- Microsoft .NET-keretrendszer, a legkorábbi 2.0-s verziótól kezdve a legújabb „.NET-keretrendszer 4.8”-ig
- .NET Core, a legkorábbi 2.0-tól kezdve és a legújabb „.NET 6”-ig
- Mono >= 2.6.7
<br /><br />
Mivel a .NET kód nem a mögöttes hardverre vagy operációs rendszerre támaszkodik, hanem csak egy virtuális gépre, így szabadon fejleszthet bármilyen szoftvert Windowsra, macOS-re, Androidra, iOS-re és Linuxra.Csak győződjön meg arról, hogy a .NET-keretrendszer, a .NET Core, a Windows Azure, a Mono vagy a Xamarin megfelelő verzióját telepítette.<br /><br />
C#, F#, VB.NET alkalmazások létrehozásához javasoljuk a Microsoft Visual Studio, Xamarin és MonoDevelop IDE használatát.
<br /><br />
További részletekért lásd a [Product Documentation](https://docs.aspose.com/words/net/system-requirements/)-at.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="GYIK" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>GYIK</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Használhatom a fenti .NET kódot az alkalmazásomban?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Igen, nyugodtan töltheti le ezt a kódot, és használhatja fel .NET-alapú dokumentum-annotációs alkalmazás fejlesztésére.Ez a kód értékes erőforrásként szolgálhat projektjei funkcionalitásának és képességeinek fejlesztéséhez a háttérdokumentum-feldolgozás és -manipuláció területén.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ez az online dokumentumjegyzet-alkalmazás csak Windows rendszeren működik?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bármilyen eszközön rugalmasan kezdeményezheti a megjegyzések eltávolításához szükséges dokumentum megjegyzéseket, függetlenül attól, hogy melyik operációs rendszeren fut, legyen az Windows, Linux, Mac OS vagy Android.Csak egy modern webböngészőre és egy aktív internetkapcsolatra van szükség.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Biztonságos-e az online alkalmazás használata a Word-dokumentum megjegyzéseinek rögzítésére?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Természetesen! A szolgáltatásunkon keresztül generált kimeneti fájlokat 24 órás időkereten belül biztonságosan és automatikusan eltávolítjuk szervereinkről.Ennek eredményeként az ezekhez a fájlokhoz társított megjelenítési hivatkozások ezen időszak után megszűnnek.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Milyen böngészőt kell használni az alkalmazáshoz?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Bármilyen modern webböngészőt használhat, például a Google Chrome-ot, a Firefoxot, az Opera-t vagy a Safarit az online Word-dokumentum annotációjához.Ha azonban asztali alkalmazást fejleszt, javasoljuk az Aspose.Total dokumentumfeldolgozási API használatát a hatékony kezelés érdekében.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}