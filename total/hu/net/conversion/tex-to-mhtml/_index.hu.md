---
title: C# API a TEX exportálásához MHTML-be
description: A TEX konvertálása MHTML-re Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/tex-to-mhtml/
family: total
platformtag: net
feature: conversion
informat: TEX
outformat: MHTML
otherformats: OTT PCL ODT MARKDOWN FLATOPC MHTML WORDML DOTM DOT PS XAMLFLOW RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="TEX megjelenítése MHTML-ben .NET-en keresztül" h2=".NET API a TEX exportálásához MHTML-be Windows, macOS és Linux rendszeren Microsoft Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) egy hatékony API dokumentumkezelési és -konverziós szolgáltatások hozzáadásához a .NET-alkalmazásokon belül. A fejlett PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a TEX-fájlformátumot DOC-formátumba konvertálhatja. Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a DOC-t MHTML-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API a TEX MHTML-má konvertálásához" %}}
1. Nyissa meg a TEX-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a TEX-et dokumentummá a [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a Doc fájlt az Aspose.Words [Document](https://apireference.aspose.com/words/net/aspose.words/document) osztályával
4. Mentse a dokumentumot MHTML-formátumba a [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) metódussal, és állítsa be a Mhtml-et SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://downloads.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.tex");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.mhtml", SaveFormat.Mhtml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A TEX-fájl visszafejtése tulajdonosi jelszó használatával .NET-en keresztül" %}}
A TEX MHTML-re konvertálása előtt, ha vissza szeretné fejteni a dokumentumot, megteheti az API használatával. A PDF-fájl visszafejtéséhez először létre kell hoznia egy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és meg kell nyitnia a TEX-et a tulajdonos jelszavával. Ezt követően meg kell hívnia a Dokumentum objektum [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) metódust. Végül mentse a frissített fájlt a Dokumentum objektum Mentés metódusával.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.tex", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható MHTML-fájl létrehozása .NET-en keresztül" %}}
Annak érdekében, hogy megvédje a MHTML-et a szerkesztéstől, és megakadályozza, hogy mások szerkesztsék a dokumentumban lévő érzékeny és bizalmas információkat, beállíthatja a dokumentum védelmét az API segítségével is. Korlátozhatja a dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket engedélyezhet vele. Ezt az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API használatával teheti meg. Lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter segítségével. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.mhtml", SaveFormat.Mhtml);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-ott/" name="TEX Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-mhtml/" name="TEX Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-wordml/" name="TEX Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-dot/" name="TEX Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-odt/" name="TEX Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-rtf/" name="TEX Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-ps/" name="TEX Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-flatopc/" name="TEX Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-pcl/" name="TEX Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-markdown/" name="TEX Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-xamlflow/" name="TEX Nak nek XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/tex-to-dotx/" name="TEX Nak nek DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}