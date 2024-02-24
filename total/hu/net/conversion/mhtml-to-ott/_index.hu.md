---
title: C# API a MHTML exportálásához OTT-be
description: A MHTML konvertálása OTT-re Microsoft Word használata nélkül
url_ignore: /hu/net/conversion/mhtml-to-ott/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: OTT
otherformats: PS MARKDOWN OTT DOTX DOTM FLATOPC DOT WORDML RTF ODT PCL XAMLFLOW
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MHTML megjelenítése OTT-ben .NET-en keresztül" h2=".NET API a MHTML exportálásához OTT-be Windows, macOS és Linux rendszeren Microsoft Word használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Az [Aspose.Total for .NET](https://products.aspose.com/total/net/) egy hatékony API dokumentumkezelési és -konverziós szolgáltatások hozzáadásához a .NET-alkalmazásokon belül. A fejlett PDF-feldolgozási API [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) használatával a MHTML-fájlformátumot DOC-formátumba konvertálhatja. Ezt követően a hatékony dokumentumfeldolgozási API [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a DOC-t OTT-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API a MHTML OTT-má konvertálásához" %}}
1. Nyissa meg a MHTML-fájlt a [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) osztály használatával
2. Konvertálja a MHTML-et dokumentummá a [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) módszerrel
3. Töltse be a Doc fájlt az Aspose.Words [Document](https://reference.aspose.com/words/net/aspose.words/document) osztályával
4. Mentse a dokumentumot OTT-formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) metódussal, és állítsa be a Ott-et SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.mhtml");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ott", SaveFormat.Ott);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="A MHTML-fájl visszafejtése tulajdonosi jelszó használatával .NET-en keresztül" %}}
A MHTML OTT-re konvertálása előtt, ha vissza szeretné fejteni a dokumentumot, megteheti az API használatával. A PDF-fájl visszafejtéséhez először létre kell hoznia egy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) objektumot, és meg kell nyitnia a MHTML-et a tulajdonos jelszavával. Ezt követően meg kell hívnia a Dokumentum objektum [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) metódust. Végül mentse a frissített fájlt a Dokumentum objektum Mentés metódusával.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.mhtml", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Csak olvasható OTT-fájl létrehozása .NET-en keresztül" %}}
Annak érdekében, hogy megvédje a OTT-et a szerkesztéstől, és megakadályozza, hogy mások szerkesztsék a dokumentumban lévő érzékeny és bizalmas információkat, beállíthatja a dokumentum védelmét az API segítségével is. Korlátozhatja a dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket engedélyezhet vele. Ezt az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API használatával teheti meg. Lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter segítségével. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}