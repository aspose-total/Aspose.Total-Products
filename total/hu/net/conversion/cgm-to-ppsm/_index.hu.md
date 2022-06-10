---
title: CGM exportálása PPSM-be C# API-n keresztül
description: .NET API a CGM konvertálásához PPSM-vé Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/cgm-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSM
otherformats: POWERPOINT PPSM SWF PPT XAML PPSX PPTM PPS OTP POT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="CGM megjelenítése PPSM-nek .NET-en keresztül" h2=".NET API a CGM exportálásához PPSM-be Windows, macOS és Linux rendszeren a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Hatékony fájlformátum-automatizálási API-k csomagja [Aspose.Total for .NET](https://products.aspose.com/total/net/) segítségével két egyszerű lépésben egyszerűen renderelheti le a CGM-et PPSM-ben. A PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a CGM-fájlformátumot PPTX-re alakíthatja át. Ezt követően a Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával a PPTX-t PPSM-vé alakíthatja.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a CGM PPSM-vé konvertálásához" %}}
1. Nyissa meg a CGM-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a CGM-et PPTX-vé a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a PPTX fájlt a [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot PPSM-formátumba a [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) metódussal, és állítsa be az `Ppsm-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.cgm");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XMP-metaadatok beszerzése a CGM-fájlból .NET-en keresztül" %}}
A CGM PPSM-re konvertálása közben előfordulhat, hogy további XMP-metaadat-információkra lesz szüksége a kötegelt átalakítási folyamat prioritásainak meghatározásához. Például beszerezheti és rendezheti a konverziós dokumentumokat a létrehozás dátuma alapján, és ennek megfelelően dolgozhatja fel a dokumentumokat. Az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) lehetővé teszi a CGM-fájlok XMP-metaadatainak elérését. A CGM-fájl metaadatainak lekéréséhez létrehozhat egy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és megnyithatja a bemeneti CGM-fájlt. Ezt követően a [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) tulajdonság segítségével szerezheti be a fájl metaadatait.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.cgm");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható PPSM-fájl létrehozása .NET-en keresztül" %}}
Az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API használatával tovább javíthatja konverziós alkalmazása funkcióit. Az egyik funkció lehet a kimeneti fájl létrehozása csak olvasható a biztonság növelése érdekében. Az API lehetővé teszi az PPSM-fájl írásvédettre állítását, ami azt jelenti, hogy a felhasználók (a prezentáció megnyitása után) a csak olvasható ajánlást látják. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-pot/" name="CGM Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-ppsx/" name="CGM Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-swf/" name="CGM Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-powerpoint/" name="CGM Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-otp/" name="CGM Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-potm/" name="CGM Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-ppt/" name="CGM Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-pps/" name="CGM Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-potx/" name="CGM Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-xaml/" name="CGM Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-ppsm/" name="CGM Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/cgm-to-pptm/" name="CGM Nak nek PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}