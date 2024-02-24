---
title: C# API az MSG WORD-be való exportálásához
description: Konvertálja az MSG-t WORD-vé Microsoft Word vagy Outlook használata nélkül a .NET-en
url_ignore: /hu/net/conversion/msg-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORD
otherformats: EMF TEXT SVG XPS PS FLATOPC ODT WORD OTT GIF PCL MD TIFF DOT DOC JPEG PNG WORDML DOTM DOCX PDF DOCM DOTX EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportálja az MSG-t WORD-be .NET-en keresztül" h2=".NET API az MSG WORD formátumban való megjelenítéséhez Windows, macOS és Linux rendszeren Word vagy Outlook használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ha Ön .NET-fejlesztő, szeretné hozzáadni az MSG-t az alkalmazásokon belüli WORD-konverziós funkciókhoz, az [Aspose.Total for .NET](https://products.aspose.com/total/net/) fájlformátum-manipulációs API-k jelentik az utat. előre. Az [Aspose.Email for .NET](https://products.aspose.com/email/net/) használatával konvertálhatja az MSG fájlformátumot HTML-re. Ezt követően az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a HTML-t WORD-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API az MSG WORD-vé konvertálásához" %}}
1. Nyissa meg az MSG fájlt a [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage) osztály használatával
2. Alakítsa át az MSG-címet HTML-vé a [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3) módszerrel
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
4. Mentse a dokumentumot WORD formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel, és állítsa be a Word-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Az MSG fájl elemzése .NET-en keresztül" %}}
Az MSG WORD-vé konvertálása előtt, ha meg szeretne győződni arról, hogy a megfelelő e-mailt konvertálja, töltse be az MSG dokumentumot, elemezze, és tekintse meg a kívánt tulajdonságot. A [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, a küldő és a címzett információkat kaphat. Például a [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername) tulajdonság használatával ellenőrizheti a konverzióhoz tartozó feladó e-mail-címét.  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A WORD-dokumentumszerkesztés korlátozása .NET-en keresztül" %}}
Amikor a dokumentumot MSG-ből WORD-be menti, előfordulhat, hogy meg kell védenie a kimeneti dokumentumot. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Ez hasznos lehet annak megakadályozására, hogy mások szerkeszthessék a dokumentumban található érzékeny és bizalmas információkat. Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}