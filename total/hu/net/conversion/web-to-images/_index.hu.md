---
title: Weboldalak HTML-jének konvertálása képekké a C# használatával
description: Kaparja ki a webhely weboldalait, és exportálja a HTML-t Képekbe. NET-alkalmazások fejlesztése a webhelyadatok JPEG, PNG, GIF, BMP stb. formátumba kaparásához. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Weboldalak konvertálása képekké C# segítségével" h2="Webhelyadatok kinyerése HTML weboldalakból. A HTML konvertálása JPG, GIF, PNG, BMP képekké a .NET alkalmazásokon belül." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Miért kell a weboldalakat képekké konvertálni?</h2>
<p>A weboldalak képekké konvertálása számos helyzetben hasznos lehet. Sok alkalmazásnál általános követelmény. Egyes esetekben a teljes weboldalt képként kell rögzíteni, beleértve a képernyőn nem látható részeket is. Ez hasznos lehet webhely-előnézetek generálásához, nyugták és számlák rögzítéséhez, vagy weboldalak jogi célú archiválásához. Használható képernyőképek készítésére weboldalakról dokumentációs vagy tesztelési célokra. Használható weboldalak bélyegképeinek vagy előnézeteinek létrehozására is a keresési eredményekben vagy képgalériákban való használatra. Függetlenül attól, hogy asztali alkalmazást vagy webalkalmazást készít, számos lehetőség áll rendelkezésre a weboldalak C# használatával képekké konvertálására.</p><br />

<p>A weboldalak C# használatával képekké konvertálása számos előnnyel jár, többek között:</p><br />
<ul>
<li>Továbbfejlesztett hozzáférhetőség: A képek könnyebben olvashatók és érthetőbbek a látássérült vagy más fogyatékkal élők számára.</li>
<li>Fokozott hordozhatóság: A képek könnyen megoszthatók vagy beágyazhatók más dokumentumokba vagy alkalmazásokba.</li>
</ul>
<p>A weboldalak C# használatával képekké konvertálása bizonyos kihívásokat is jelenthet, többek között:</p><br />
<ul>
<li>Korlátozott formátumtámogatás: Előfordulhat, hogy egyes API-k vagy eszközök nem támogatják az összes képformátumot, vagy korlátozhatják a kimeneti képek méretét vagy felbontását.</li>
<li>Kompatibilitási problémák: Előfordulhat, hogy egyes weboldalak nem jelennek meg megfelelően minden böngészőben, vagy bizonyos beállításokra vagy beépülő modulokra van szükség a megfelelő megjelenítéshez.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hogyan lehet weblapokat képekké konvertálni C# használatával?" %}}
Weboldalak C# használatával képekké alakításához használhat egy Aspose.HTML for .NET API-t, amely ezt a funkciót biztosítja a HTML-oldalak képformátumokká konvertálásához, beleértve a JPEG, PNG és TIFF formátumokat.</p>

1. Töltsön be egy HTML-dokumentumot a rendelkezésre álló konstruktorok egyikével [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). HTML-t betölthet fájlból, HTML-kódból, adatfolyamból vagy URL-ből.
2. Hozzon létre egy új példányt a [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) és állítsa az ImageFormat tulajdonságot JPEG-re. Alapértelmezés szerint a Formátum tulajdonság PNG-re van állítva.
3. Használja ki a [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metódussal a Converter osztályból, hogy a HTML-dokumentumot JPEG-fájlként mentse. A ConvertHTML() metódus paramétereiként meg kell adnia a HTMLDocument, ImageSaveOptions és a kimeneti fájl elérési útját.
4. Az eredményül kapott JPEG fájl a megadott fájlútvonalra kerül mentésre.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Internetes selejtezési és képátalakítási követelmények" %}}
Telepítse parancssorból ```nuget install Aspose.Total``` néven, vagy telepítse közvetlenül a Visual Studio Package Manager konzoljából.

Kettő [Aspose.Total for .NET](https://products.aspose.com/total/net/) gyermek API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) integrálni fogják.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban innen [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}