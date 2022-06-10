---
title: XPS exportálása PPSX-be C# API-n keresztül
description: .NET API a XPS konvertálásához PPSX-vé Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/xps-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: XPS
outformat: PPSX
otherformats: PPT SWF OTP POWERPOINT POTM PPS PPTM PPSX POTX XAML PPSM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XPS megjelenítése PPSX-nek .NET-en keresztül" h2=".NET API a XPS exportálásához PPSX-be Windows, macOS és Linux rendszeren a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Hatékony fájlformátum-automatizálási API-k csomagja [Aspose.Total for .NET](https://products.aspose.com/total/net/) segítségével két egyszerű lépésben egyszerűen renderelheti le a XPS-et PPSX-ben. A PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a XPS-fájlformátumot PPTX-re alakíthatja át. Ezt követően a Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával a PPTX-t PPSX-vé alakíthatja.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a XPS PPSX-vé konvertálásához" %}}
1. Nyissa meg a XPS-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a XPS-et PPTX-vé a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a PPTX fájlt a [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot PPSX-formátumba a [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) metódussal, és állítsa be az `Ppsx-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xps");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XMP-metaadatok beszerzése a XPS-fájlból .NET-en keresztül" %}}
A XPS PPSX-re konvertálása közben előfordulhat, hogy további XMP-metaadat-információkra lesz szüksége a kötegelt átalakítási folyamat prioritásainak meghatározásához. Például beszerezheti és rendezheti a konverziós dokumentumokat a létrehozás dátuma alapján, és ennek megfelelően dolgozhatja fel a dokumentumokat. Az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) lehetővé teszi a XPS-fájlok XMP-metaadatainak elérését. A XPS-fájl metaadatainak lekéréséhez létrehozhat egy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és megnyithatja a bemeneti XPS-fájlt. Ezt követően a [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) tulajdonság segítségével szerezheti be a fájl metaadatait.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xps");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható PPSX-fájl létrehozása .NET-en keresztül" %}}
Az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API használatával tovább javíthatja konverziós alkalmazása funkcióit. Az egyik funkció lehet a kimeneti fájl létrehozása csak olvasható a biztonság növelése érdekében. Az API lehetővé teszi az PPSX-fájl írásvédettre állítását, ami azt jelenti, hogy a felhasználók (a prezentáció megnyitása után) a csak olvasható ajánlást látják. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-pot/" name="XPS Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-ppsx/" name="XPS Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-swf/" name="XPS Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-powerpoint/" name="XPS Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-otp/" name="XPS Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-potm/" name="XPS Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-ppt/" name="XPS Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-pps/" name="XPS Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-potx/" name="XPS Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-xaml/" name="XPS Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-ppsm/" name="XPS Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xps-to-pptm/" name="XPS Nak nek PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}