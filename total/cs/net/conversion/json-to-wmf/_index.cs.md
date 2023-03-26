---
title: Převeďte formát JSON na WMF přes .NET
description: Analyzujte JSON na WMF v C# bez použití závislostí třetích stran
url_ignore: /cs/net/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: DICOM WMF IMAGE WMZ DXF TGA PSD JPEG2000 SVGZ EMZ
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Převést formát JSON na WMF přes C#" h2="C# API pro analýzu JSON na WMF bez použití závislostí třetích stran" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for .NET](https://products.aspose.com/total/net/) můžete analyzovat JSON na WMF v jakékoli aplikaci .NET, C#, ASP.NET a VB.NET ve dvou jednoduchých kroky. Za prvé, pomocí [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) můžete exportovat JSON do JPEG. Poté můžete pomocí [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/) převést JPEG na WMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převést formát JSON na WMF přes C#" %}}
1. Vytvořte nový objekt [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) a načtěte data JSON ze souboru
2. Převeďte JSON na JPEG pomocí metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Načtěte dokument JPEG pomocí třídy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Uložte dokument do formátu WMF pomocí metody [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Nastavte rozvržení a převeďte formát JSON na WMF přes C#" %}}
Při analýze JSON na WMF můžete také nastavit možnosti rozvržení pro JSON pomocí [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umožňuje zpracovat pole jako tabulku, ignorovat hodnoty null, ignorovat název pole, ignorovat název objektu, převést řetězec na číslo nebo datum, nastavit formát data a čísla a nastavit styl nadpisu. Všechny tyto možnosti vám umožňují prezentovat data podle vašich potřeb. Následující fragment kódu ukazuje, jak nastavit možnosti rozvržení.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte formát JSON na WMF s vodoznakem" %}}
Pomocí API můžete také převést JSON na WMF s vodoznakem v dokumentu WMF. Chcete-li přidat vodoznak, můžete nejprve vykreslit svůj dokument JSON do formátu JPEG a přidat do něj vodoznak. Chcete-li předvést operaci, můžete načíst převedený obrázek JPEG, přidat transformace pomocí objektu třídy Matrix a nakreslit řetězec jako vodoznak na povrch obrázku pomocí [Graphics](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) třída' [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Po přidání vodoznaku do něj můžete uložit JPEG jako formát WMF. Níže je uveden příklad kódu, který ukazuje, jak do dokumentu přidat diagonální vodoznak. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}