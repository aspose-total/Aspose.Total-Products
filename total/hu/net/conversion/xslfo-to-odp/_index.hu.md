---
title: XSLFO exportálása ODP-be C# API-n keresztül
description: .NET API a XSLFO konvertálásához ODP-vé Microsoft Word használata nélkül
url: /hu/net/conversion/xslfo-to-odp/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: ODP
otherformats: PPSM PPT PPSX POTX SWF PPTM POWERPOINT OTP POTM XAML PPS POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XSLFO megjelenítése ODP-nek .NET-en keresztül" h2=".NET API a XSLFO exportálásához ODP-be Windows, macOS és Linux rendszeren a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Hatékony fájlformátum-automatizálási API-k csomagja [Aspose.Total for .NET](https://products.aspose.com/total/net/) segítségével két egyszerű lépésben egyszerűen renderelheti le a XSLFO-et ODP-ben. A PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a XSLFO-fájlformátumot PPTX-re alakíthatja át. Ezt követően a Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával a PPTX-t ODP-vé alakíthatja.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a XSLFO ODP-vé konvertálásához" %}}
1. Nyissa meg a XSLFO-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a XSLFO-et PPTX-vé a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a PPTX fájlt a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot ODP-formátumba a [Mentés](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) metódussal, és állítsa be az `Odp-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xslfo");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XMP-metaadatok beszerzése a XSLFO-fájlból .NET-en keresztül" %}}
A XSLFO ODP-re konvertálása közben előfordulhat, hogy további XMP-metaadat-információkra lesz szüksége a kötegelt átalakítási folyamat prioritásainak meghatározásához. Például beszerezheti és rendezheti a konverziós dokumentumokat a létrehozás dátuma alapján, és ennek megfelelően dolgozhatja fel a dokumentumokat. Az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) lehetővé teszi a XSLFO-fájlok XMP-metaadatainak elérését. A XSLFO-fájl metaadatainak lekéréséhez létrehozhat egy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és megnyithatja a bemeneti XSLFO-fájlt. Ezt követően a [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) tulajdonság segítségével szerezheti be a fájl metaadatait.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xslfo");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható ODP-fájl létrehozása .NET-en keresztül" %}}
Az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API használatával tovább javíthatja konverziós alkalmazása funkcióit. Az egyik funkció lehet a kimeneti fájl létrehozása csak olvasható a biztonság növelése érdekében. Az API lehetővé teszi az ODP-fájl írásvédettre állítását, ami azt jelenti, hogy a felhasználók (a prezentáció megnyitása után) a csak olvasható ajánlást látják. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-pot/" name="XSLFO Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-ppsx/" name="XSLFO Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-swf/" name="XSLFO Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-powerpoint/" name="XSLFO Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-otp/" name="XSLFO Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-potm/" name="XSLFO Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-ppt/" name="XSLFO Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-pps/" name="XSLFO Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-potx/" name="XSLFO Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-xaml/" name="XSLFO Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-ppsm/" name="XSLFO Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xslfo-to-pptm/" name="XSLFO Nak nek PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}