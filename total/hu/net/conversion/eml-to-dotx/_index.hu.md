---
title: C# API az EML DOTX-be való exportálásához
description: Konvertálja az EML-t DOTX-vé Microsoft Word vagy Outlook használata nélkül a .NET-en
url_ignore: /hu/net/conversion/eml-to-dotx/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOTX
otherformats: EPUB DOCM TEXT MD DOC GIF DOTX DOTM JPEG ODT PDF XPS PCL DOCX PNG FLATOPC PS SVG OTT DOT TIFF EMF RTF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportálja az EML-t DOTX-be .NET-en keresztül" h2=".NET API az EML DOTX formátumban való megjelenítéséhez Windows, macOS és Linux rendszeren Word vagy Outlook használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ha Ön .NET-fejlesztő, szeretné hozzáadni az EML-t az alkalmazásokon belüli DOTX-konverziós funkciókhoz, az [Aspose.Total for .NET](https://products.aspose.com/total/net/) fájlformátum-manipulációs API-k jelentik az utat. előre. Az [Aspose.Email for .NET](https://products.aspose.com/email/net/) használatával konvertálhatja az EML fájlformátumot HTML-re. Ezt követően az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a HTML-t DOTX-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API az EML DOTX-vé konvertálásához" %}}
1. Nyissa meg az EML fájlt a [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage) osztály használatával
2. Alakítsa át az EML-címet HTML-vé a [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) módszerrel
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
4. Mentse a dokumentumot DOTX formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel, és állítsa be a Dotx-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Az EML fájl elemzése .NET-en keresztül" %}}
Az EML DOTX-vé konvertálása előtt, ha meg szeretne győződni arról, hogy a megfelelő e-mailt konvertálja, töltse be az EML dokumentumot, elemezze, és tekintse meg a kívánt tulajdonságot. A [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, a küldő és a címzett információkat kaphat. Például a [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) tulajdonság használatával ellenőrizheti a konverzióhoz tartozó feladó e-mail-címét.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A DOTX-dokumentumszerkesztés korlátozása .NET-en keresztül" %}}
Amikor a dokumentumot EML-ből DOTX-be menti, előfordulhat, hogy meg kell védenie a kimeneti dokumentumot. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Ez hasznos lehet annak megakadályozására, hogy mások szerkeszthessék a dokumentumban található érzékeny és bizalmas információkat. Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dotx", SaveFormat.Dotx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}