---
title: C# API az OFT EPUB-be való exportálásához
description: Konvertálja az OFT-t EPUB-vé Microsoft Word vagy Outlook használata nélkül a .NET-en
url_ignore: /hu/net/conversion/oft-to-epub/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: EPUB
otherformats: FLATOPC RTF DOCX DOCM PCL SVG PNG ODT DOTM XPS JPEG OTT DOT TEXT MD DOC DOTX WORDML PS EMF EPUB TIFF GIF PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportálja az OFT-t EPUB-be .NET-en keresztül" h2=".NET API az OFT EPUB formátumban való megjelenítéséhez Windows, macOS és Linux rendszeren Word vagy Outlook használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ha Ön .NET-fejlesztő, szeretné hozzáadni az OFT-t az alkalmazásokon belüli EPUB-konverziós funkciókhoz, az [Aspose.Total for .NET](https://products.aspose.com/total/net/) fájlformátum-manipulációs API-k jelentik az utat. előre. Az [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) használatával konvertálhatja az OFT fájlformátumot HTML-re. Ezt követően az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a HTML-t EPUB-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API az OFT EPUB-vé konvertálásához" %}}
1. Nyissa meg az OFT fájlt a [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) osztály használatával
2. Alakítsa át az OFT-címet HTML-vé a [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) módszerrel
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
4. Mentse a dokumentumot EPUB formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel, és állítsa be a Epub-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.oft");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Az OFT fájl elemzése .NET-en keresztül" %}}
Az OFT EPUB-vé konvertálása előtt, ha meg szeretne győződni arról, hogy a megfelelő e-mailt konvertálja, töltse be az OFT dokumentumot, elemezze, és tekintse meg a kívánt tulajdonságot. A [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API, a küldő és a címzett információkat kaphat. Például a [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) tulajdonság használatával ellenőrizheti a konverzióhoz tartozó feladó e-mail-címét.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A EPUB-dokumentumszerkesztés korlátozása .NET-en keresztül" %}}
Amikor a dokumentumot OFT-ből EPUB-be menti, előfordulhat, hogy meg kell védenie a kimeneti dokumentumot. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Ez hasznos lehet annak megakadályozására, hogy mások szerkeszthessék a dokumentumban található érzékeny és bizalmas információkat. Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}