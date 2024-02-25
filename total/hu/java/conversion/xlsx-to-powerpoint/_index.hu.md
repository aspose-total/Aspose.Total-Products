---
title: A XLSX konvertálása POWERPOINT formátumba Java segítségével vagy ingyenes online konverterrel
description: Java API a XLSX exportálásához POWERPOINT-ba vagy online Excel vagy Word használatával vagy online. A kód integrálása előtt gyorsan tesztelje az ingyenes CSV-DOC online konvertert.
url_ignore: /hu/java/conversion/xlsx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLSX
outformat: POWERPOINT
otherformats: POWERPOINTX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API a XLSX exportálásához POWERPOINT-ba vagy online" h2="On Premise Java API a XLSX exportálásához POWERPOINT-ba vagy online anélkül, hogy a Microsoft Excel<sup>&reg;</sup>" >}}
{{% blocks/products/pf/feature-page-summary %}}
A XLSX megjelenítése POWERPOINT-ba kétlépéses folyamat. Először az [Aspose.Cells for Java](https://products.aspose.com/cells/java) API segítségével konvertálja az adott XLSX-dokumentumot PDF-be, majd az [Aspose.PDF for Java](https://products.aspose.com/pdf/java) API segítségével könnyedén konvertálhatja PDF dokumentumát POWERPOINT formátumba. Mindkét API az [Aspose.Total for Java](https://products.aspose.com/total/java/) fájlformátumú automatizálási könyvtárak gyűjteményébe tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet XLSX-t POWERPOINT-ba konvertálni Java API-n keresztül" %}}
1. Nyissa meg a XLSX-fájlt a [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) osztály használatával
2. Alakítsa át a XLSX-t PDF-be, és állítsa a SaveFormat beállítást AUTO-ra
3. Töltse be a konvertált PDF-fájlt a [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) osztály használatával
4. Mentse a dokumentumot POWERPOINT formátumba a [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions) segítségével-) metódust, és állítsa be a Powerpoint-ot SaveFormat-ként
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Az Aspose.Total for Java programot közvetlenül egy [Maven](https://releases.aspose.com/total/java/) alapú projektből kell használnia és vegyen fel könyvtárakat a pom.xml fájlba.

Alternatív megoldásként beszerezhet egy ZIP-fájlt a [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Workbook class
Workbook book = new Workbook("input.xlsx");
// save XLSX as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online konverter XLSX-hez POWERPOINT-be</h3>

<iframe title="xlsx-ból pptx-be konvertáló online eszköz" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">Próbálja ki ingyenes alkalmazásunkat a XLSX-ből POWERPOINT-be konvertálásához</a></p>
</div></div>
</div></div>
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
                          <span itemprop="name"><b>Hogyan konvertálhatom a XLSX-t POWERPOINT Online formátumba?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">A fentiekben integrált online alkalmazás a XLSX konverzióhoz. Az átalakítási folyamat magában foglalja a XLSX-fájl hozzáadását a fehér területre való húzással vagy a terület belsejébe való kattintással a fájl importálásához. A fájl hozzáadása után egyszerűen kattintson a Konvertálás gombra a konvertálási folyamat elindításához. Ha elkészült, egyetlen kattintással letöltheti az újonnan konvertált POWERPOINT-fájlt.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Mennyi ideig tart a XLSX konvertálása?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Ennek az online konverternek a sebességét nagyrészt a konvertálandó XLSX fájl mérete határozza meg. A kisebb XLSX fájlok néhány másodpercen belül POWERPOINT formátumba konvertálhatók. Ezenkívül, ha beépítette a konverziós kódot egy Java-alkalmazásba, az alkalmazás hatékonysága is befolyásolja a konverziós folyamatot.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Biztonságos a XLSX konvertálása POWERPOINT formátumba az ingyenes Aspose.Total konverter segítségével?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Természetesen! Az átalakítási folyamat befejezése után a POWERPOINT-fájl letöltési hivatkozása azonnal elérhető lesz. A feltöltött fájlok 24 óra elteltével automatikusan törlődnek, és a letöltési hivatkozások ezen időn túl nem lesznek aktívak. Biztos lehet benne, hogy fájljai biztonságban vannak, és a fájlkonverzió, beleértve a XLSX-t is, teljesen biztonságos. Az ingyenes alkalmazást elsősorban tesztelési célokra integrálták, lehetővé téve az eredmények ellenőrzését, mielőtt a kódot integrálná a projektbe.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Milyen böngészőt használjak a XLSX konvertálásához?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Az online konverzióhoz bármilyen modern webböngészőt használhat, például Google Chrome, Firefox, Opera vagy Safari. Ha azonban asztali alkalmazást fejleszt, az Aspose.Total XLSX Conversion API kiváló választás, mivel úgy tervezték, hogy zökkenőmentesen működjön ilyen környezetben.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}