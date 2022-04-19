---
title: XML exportálása PPTM-be C# API-n keresztül
description: .NET API a XML konvertálásához PPTM-vé Microsoft Word használata nélkül
url: /hu/net/conversion/xml-to-pptm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: PPTM
otherformats: POWERPOINT POTM PPT POT POTX SWF PPSM PPSX XAML PPS OTP PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="XML megjelenítése PPTM-nek .NET-en keresztül" h2=".NET API a XML exportálásához PPTM-be Windows, macOS és Linux rendszeren a Microsoft<sup>&reg;</sup> PowerPoint használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Hatékony fájlformátum-automatizálási API-k csomagja [Aspose.Total for .NET] (https://products.aspose.com/total/net/) segítségével két egyszerű lépésben egyszerűen renderelheti le a XML-et PPTM-ben. A PDF-feldolgozási API [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) használatával a XML-fájlformátumot PPTX-re alakíthatja át. Ezt követően a Presentation Processing API [Aspose.Slides for .NET] (https://products.aspose.com/slides/net/) használatával a PPTX-t PPTM-vé alakíthatja.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API a XML PPTM-vé konvertálásához" %}}
1. Nyissa meg a XML-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a XML-et PPTX-vé a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a PPTX fájlt a [Presentation](https://apireference.aspose.com/slides/net/aspose.slides/presentation) osztály használatával
4. Mentse a dokumentumot PPTM-formátumba a [Mentés](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) metódussal, és állítsa be az `Pptm-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.xml");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="XMP-metaadatok beszerzése a XML-fájlból .NET-en keresztül" %}}
A XML PPTM-re konvertálása közben előfordulhat, hogy további XMP-metaadat-információkra lesz szüksége a kötegelt átalakítási folyamat prioritásainak meghatározásához. Például beszerezheti és rendezheti a konverziós dokumentumokat a létrehozás dátuma alapján, és ennek megfelelően dolgozhatja fel a dokumentumokat. Az [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) lehetővé teszi a XML-fájlok XMP-metaadatainak elérését. A XML-fájl metaadatainak lekéréséhez létrehozhat egy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és megnyithatja a bemeneti XML-fájlt. Ezt követően a [Metadata](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata) tulajdonság segítségével szerezheti be a fájl metaadatait.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document doc = new Document("input.xml");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható PPTM-fájl létrehozása .NET-en keresztül" %}}
Az [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) API használatával tovább javíthatja konverziós alkalmazása funkcióit. Az egyik funkció lehet a kimeneti fájl létrehozása csak olvasható a biztonság növelése érdekében. Az API lehetővé teszi az PPTM-fájl írásvédettre állítását, ami azt jelenti, hogy a felhasználók (a prezentáció megnyitása után) a csak olvasható ajánlást látják. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-pot/" name="XML Nak nek POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-ppsx/" name="XML Nak nek PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-swf/" name="XML Nak nek SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-powerpoint/" name="XML Nak nek POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-otp/" name="XML Nak nek OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-potm/" name="XML Nak nek POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-ppt/" name="XML Nak nek PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-pps/" name="XML Nak nek PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-potx/" name="XML Nak nek POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-xaml/" name="XML Nak nek XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-ppsm/" name="XML Nak nek PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/xml-to-pptm/" name="XML Nak nek PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}