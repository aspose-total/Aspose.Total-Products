---
title: C# API a MD exportálásához DOTM-be
description: A MD konvertálása DOTM-re Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/md-to-dotm/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOTM
otherformats: FLATOPC ODT WORDML OTT DOT RTF PS MHTML MARKDOWN DOTX DOTM XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MD megjelenítése DOTM-ben .NET-en keresztül" h2=".NET API a MD exportálásához DOTM-be Windows, macOS és Linux rendszeren Microsoft Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) egy hatékony API dokumentumkezelési és -konverziós szolgáltatások hozzáadásához a .NET-alkalmazásokon belül. A fejlett PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a MD-fájlformátumot DOC-formátumba konvertálhatja. Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a DOC-t DOTM-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API a MD DOTM-má konvertálásához" %}}
1. Nyissa meg a MD-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a MD-et dokumentummá a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a Doc fájlt az Aspose.Words [Document](https://reference.aspose.com/words/net/aspose.words/document) osztályával
4. Mentse a dokumentumot DOTM-formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) metódussal, és állítsa be a Dotm-et SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A MD-fájl visszafejtése tulajdonosi jelszó használatával .NET-en keresztül" %}}
A MD DOTM-re konvertálása előtt, ha vissza szeretné fejteni a dokumentumot, megteheti az API használatával. A PDF-fájl visszafejtéséhez először létre kell hoznia egy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és meg kell nyitnia a MD-et a tulajdonos jelszavával. Ezt követően meg kell hívnia a Dokumentum objektum [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) metódust. Végül mentse a frissített fájlt a Dokumentum objektum Mentés metódusával.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható DOTM-fájl létrehozása .NET-en keresztül" %}}
Annak érdekében, hogy megvédje a DOTM-et a szerkesztéstől, és megakadályozza, hogy mások szerkesztsék a dokumentumban lévő érzékeny és bizalmas információkat, beállíthatja a dokumentum védelmét az API segítségével is. Korlátozhatja a dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket engedélyezhet vele. Ezt az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API használatával teheti meg. Lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter segítségével. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotm", SaveFormat.Dotm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}