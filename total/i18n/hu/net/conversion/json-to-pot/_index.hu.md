---
title: Konvertálja a JSON-formátumot POT-vé .NET-en keresztül
description: Elemezze a JSON-t POT-re C#-ban Microsoft PowerPoint használata nélkül
url: /hu/net/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POTM PPT PPTM PPSM POT PPSX POWERPOINT OTP PPS POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konvertálja a JSON formátumot POT-vé a C# segítségével" h2="C# API a JSON elemzéséhez POT-be a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Két egyszerű lépésben konvertálhatja a JSON-t POT-vé bármely .NET, C#, ASP.NET és VB.NET alkalmazáson belül. Először is, az [Aspose.Cells for .NET] (https://products.aspose.com/cells/net/) használatával elemezheti a JSON-t PPTX-re. Ezt követően az [Aspose.Slides for .NET] (https://products.aspose.com/slides/net/) használatával konvertálhatja a PPTX-t POT-vé. Mindkét API az [Aspose.Total for .NET](https://products.aspose.com/total/net/) csomagba tartozik.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertálja a JSON formátumot POT-vé a C# segítségével" %}}
1. Hozzon létre egy új [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) objektumot, és olvassa be az érvényes JSON-adatokat a fájlból
2. Importálja a JSON-fájlt a munkalapra a [JsonUtility](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonutility) osztály és a [Mentés](https://apireference.aspose.com/) használatával. cell/net/aspose.cells.workbook/save/methods/4) PPTX-ként
3. Töltse be a PPTX dokumentumot a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot POT formátumba a [Mentés](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) módszerrel
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Állítsa be az elrendezést, és konvertálja a JSON-formátumot POT-re C#-on keresztül" %}}
A JSON POT-re történő elemzése közben a JSON-formátum elrendezési beállításait is megadhatja a [JsonLayoutOptions](https://apireference.aspose.com/cells/net/aspose.cells.utility/jsonlayotoptions) segítségével. Lehetővé teszi a tömb táblázatként történő feldolgozását, a nullák figyelmen kívül hagyását, a tömb címének figyelmen kívül hagyását, az objektum címének figyelmen kívül hagyását, a karakterlánc számmá vagy dátummá alakítását, a dátum és számformátum beállítását, valamint a címstílus beállítását. Mindezek a lehetőségek lehetővé teszik, hogy adatait az igényeinek megfelelően mutassa be. A következő kódrészlet bemutatja, hogyan állíthatja be az elrendezési beállításokat.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konvertálja a JSON formátumot POT-re vízjellel" %}}
Az API használatával a JSON-t vízjellel POT-vé is konvertálhatja. Ha vízjelet szeretne hozzáadni az POT-dokumentumhoz, először elemezze a JSON-t PPTX-be, és adjon hozzá egy vízjelet. Vízjel hozzáadásához töltse be az újonnan létrehozott PPTX fájlt a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály segítségével, válassza ki a főprezentációt, és adja meg az alakzat típusát a segítségével AddAutoShape, és adjon hozzá vízjelszöveget az AddTextFrame segítségével. A vízjel hozzáadása után elmentheti a dokumentumot az POT-be. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppt/" name="JSON Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-otp/" name="JSON Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppsx/" name="JSON Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-powerpoint/" name="JSON Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-potm/" name="JSON Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pot/" name="JSON Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-ppsm/" name="JSON Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-potx/" name="JSON Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pptm/" name="JSON Nak nek PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/json-to-pps/" name="JSON Nak nek PPS" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}