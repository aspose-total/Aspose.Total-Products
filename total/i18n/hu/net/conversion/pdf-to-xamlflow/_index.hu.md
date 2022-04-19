---
title: C# API a PDF exportálásához XAMLFLOW-be
description: A PDF konvertálása XAMLFLOW-re Microsoft Word használata nélkül
url: /hu/net/conversion/pdf-to-xamlflow/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: XAMLFLOW
otherformats: DOTX XAMLFLOW DOT ODT PCL OTT PS DOTM FLATOPC MARKDOWN RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PDF megjelenítése XAMLFLOW-ben .NET-en keresztül" h2=".NET API a PDF exportálásához XAMLFLOW-be Windows, macOS és Linux rendszeren Microsoft Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) egy hatékony API dokumentumkezelési és -konverziós szolgáltatások hozzáadásához a .NET-alkalmazásokon belül. A fejlett PDF-feldolgozási API [Aspose.PDF for .NET] (https://products.aspose.com/pdf/net/) használatával a PDF-fájlformátumot DOC-formátumba konvertálhatja. Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for .NET] (https://products.aspose.com/words/net/) használatával a DOC-t XAMLFLOW-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API a PDF XAMLFLOW-má konvertálásához" %}}
1. Nyissa meg a PDF-fájlt a [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a PDF-et dokumentummá a [Mentés](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a Doc fájlt az Aspose.Words [Document](https://apireference.aspose.com/words/net/aspose.words/document) osztályával
4. Mentse a dokumentumot XAMLFLOW-formátumba a [Mentés](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) metódussal, és állítsa be a Xamlflow-et SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads] webhelyről (https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.pdf");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.xamlflow", SaveFormat.Xamlflow);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A PDF-fájl visszafejtése tulajdonosi jelszó használatával .NET-en keresztül" %}}
A PDF XAMLFLOW-re konvertálása előtt, ha vissza szeretné fejteni a dokumentumot, megteheti az API használatával. A PDF-fájl visszafejtéséhez először létre kell hoznia egy [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és meg kell nyitnia a PDF-et a tulajdonos jelszavával. Ezt követően meg kell hívnia a Dokumentum objektum [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) metódust. Végül mentse a frissített fájlt a Dokumentum objektum Mentés metódusával.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.pdf", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható XAMLFLOW-fájl létrehozása .NET-en keresztül" %}}
Annak érdekében, hogy megvédje a XAMLFLOW-et a szerkesztéstől, és megakadályozza, hogy mások szerkesztsék a dokumentumban lévő érzékeny és bizalmas információkat, beállíthatja a dokumentum védelmét az API segítségével is. Korlátozhatja a dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket engedélyezhet vele. Ezt az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API használatával teheti meg. Lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter segítségével. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xamlflow", SaveFormat.Xamlflow);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ott/" name="PDF Nak nek OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-mhtml/" name="PDF Nak nek MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-wordml/" name="PDF Nak nek WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dot/" name="PDF Nak nek DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-odt/" name="PDF Nak nek ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-rtf/" name="PDF Nak nek RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-ps/" name="PDF Nak nek PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-flatopc/" name="PDF Nak nek FLANak nekPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-pcl/" name="PDF Nak nek PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-markdown/" name="PDF Nak nek MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-xamlflow/" name="PDF Nak nek XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/pdf-to-dotx/" name="PDF Nak nek DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}