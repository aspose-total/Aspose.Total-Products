---
title: PCL exportálása ODP-be C# API-n keresztül
description: .NET API a PCL konvertálásához ODP-vé Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/pcl-to-odp/
family: total
platformtag: net
feature: conversion
informat: PCL
outformat: ODP
otherformats: PPS SWF PPSM PPTM POT PPSX POTM XAML PPT POTX POWERPOINT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PCL megjelenítése ODP-nek .NET-en keresztül" h2=".NET API a PCL exportálásához ODP-be Windows, macOS és Linux rendszeren a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Hatékony fájlformátum-automatizálási API-k csomagja [Aspose.Total for .NET](https://products.aspose.com/total/net/) segítségével két egyszerű lépésben egyszerűen renderelheti le a PCL-et ODP-ben. A PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a PCL-fájlformátumot PPTX-re alakíthatja át. Ezt követően a Presentation Processing API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) használatával a PPTX-t ODP-vé alakíthatja.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a PCL ODP-vé konvertálásához" %}}
1. Nyissa meg a PCL-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a PCL-et PPTX-vé a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a PPTX fájlt a [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot ODP-formátumba a [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) metódussal, és állítsa be az `Odp-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.pcl");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.odp", SaveFormat.Odp);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XMP-metaadatok beszerzése a PCL-fájlból .NET-en keresztül" %}}
A PCL ODP-re konvertálása közben előfordulhat, hogy további XMP-metaadat-információkra lesz szüksége a kötegelt átalakítási folyamat prioritásainak meghatározásához. Például beszerezheti és rendezheti a konverziós dokumentumokat a létrehozás dátuma alapján, és ennek megfelelően dolgozhatja fel a dokumentumokat. Az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) lehetővé teszi a PCL-fájlok XMP-metaadatainak elérését. A PCL-fájl metaadatainak lekéréséhez létrehozhat egy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és megnyithatja a bemeneti PCL-fájlt. Ezt követően a [Metadata](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) tulajdonság segítségével szerezheti be a fájl metaadatait.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.pcl");

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

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-pot/" name="PCL Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-ppsx/" name="PCL Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-swf/" name="PCL Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-powerpoint/" name="PCL Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-otp/" name="PCL Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-potm/" name="PCL Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-ppt/" name="PCL Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-pps/" name="PCL Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-potx/" name="PCL Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-xaml/" name="PCL Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-ppsm/" name="PCL Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pcl-to-pptm/" name="PCL Nak nek PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}