---
title: Převod HTML webových stránek na obrázky pomocí C#
description: Seškrábejte webové stránky a exportujte HTML do obrázků. Vyvíjejte aplikace .NET pro seškrabování dat webových stránek do JPEG, PNG, GIF, BMP atd. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést webové stránky na obrázky pomocí C#" h2="Extrahujte data webových stránek z webových stránek HTML. Převeďte HTML do obrázků JPG, GIF, PNG, BMP v rámci aplikací .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Proč převádět webové stránky na obrázky?</h2>
<p>Převod webových stránek na obrázky může být užitečný v různých situacích. Je to běžný požadavek pro mnoho aplikací. V některých scénářích je nutné zachytit celou webovou stránku jako obrázek, včetně částí, které nejsou vidět na obrazovce. To může být užitečné pro generování náhledů webových stránek, zachycování účtenek a faktur nebo archivaci webových stránek pro právní účely. Lze jej použít k vytvoření screenshotů webových stránek pro účely dokumentace nebo testování. Lze jej také použít k vytváření miniatur nebo náhledů webových stránek pro použití ve výsledcích vyhledávání nebo v galeriích obrázků. Ať už vytváříte desktopovou aplikaci nebo webovou aplikaci, existuje mnoho možností pro převod webových stránek na obrázky pomocí C#.</p><br />

<p>Převod webových stránek na obrázky pomocí C# může poskytnout několik výhod, včetně:</p><br />
<ul>
<li>Vylepšená dostupnost: Obrázky mohou být snadněji čitelné a pochopitelné pro lidi se zrakovým postižením nebo jiným postižením.</li>
<li>Zvýšená přenosnost: Obrázky lze snadno sdílet nebo vkládat do jiných dokumentů nebo aplikací.</li>
</ul>
<p>Převod webových stránek na obrázky pomocí C# může také představovat určité problémy, včetně:</p><br />
<ul>
<li>Omezená podpora formátu: Některá rozhraní API nebo nástroje nemusí podporovat všechny formáty obrázků nebo mohou mít omezení velikosti nebo rozlišení výstupních obrázků.</li>
<li>Problémy s kompatibilitou: Některé webové stránky se nemusí správně vykreslit ve všech prohlížečích nebo mohou ke správnému zobrazení vyžadovat specifická nastavení nebo pluginy.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Jak převést webové stránky na obrázky pomocí C#?" %}}
Chcete-li převést webové stránky na obrázky pomocí C#, můžete použít Aspose.HTML for .NET API, které poskytuje tuto funkci pro převod HTML stránek do obrazových formátů, včetně JPEG, PNG a TIFF.</p>

1. Načtěte dokument HTML pomocí jednoho z konstruktorů dostupných v [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). HTML můžete načíst ze souboru, kódu HTML, streamu nebo adresy URL.
2. Vytvořte novou instanci [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) a nastavte vlastnost ImageFormat na JPEG. Ve výchozím nastavení je vlastnost Formát nastavena na PNG.
3. Využijte [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) metoda ze třídy Converter k uložení dokumentu HTML jako souboru JPEG. Budete muset zadat HTMLDocument, ImageSaveOptions a cestu k výstupnímu souboru jako parametry metody ConvertHTML().
4. Výsledný soubor JPEG bude uložen do zadané cesty k souboru.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na odstranění webu a konverzi obrázků" %}}
Nainstalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo nainstalujte přímo z konzole Správce balíčků sady Visual Studio.

Dva [Aspose.Total for .NET](https://products.aspose.com/total/net/) podřízené API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) bude integrován.

Případně získejte offline instalační program MSI nebo knihovny DLL v souboru ZIP [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}