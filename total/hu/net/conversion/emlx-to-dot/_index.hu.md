---
title: C# API az EMLX DOT-be való exportálásához
description: Konvertálja az EMLX-t DOT-vé Microsoft Word vagy Outlook használata nélkül a .NET-en
url_ignore: /hu/net/conversion/emlx-to-dot/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOT
otherformats: GIF RTF DOTX MD PCL SVG EMF DOTM PNG ODT FLATOPC TEXT PDF DOCX TIFF WORDML PS OTT DOC XPS EPUB DOT DOCM JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportálja az EMLX-t DOT-be .NET-en keresztül" h2=".NET API az EMLX DOT formátumban való megjelenítéséhez Windows, macOS és Linux rendszeren Word vagy Outlook használata nélkül" >}}

{{% blocks/products/pf/feature-page-summary %}}
Ha Ön .NET-fejlesztő, szeretné hozzáadni az EMLX-t az alkalmazásokon belüli DOT-konverziós funkciókhoz, az [Aspose.Total for .NET](https://products.aspose.com/total/net/) fájlformátum-manipulációs API-k jelentik az utat. előre. Az [Aspose.Email for .NET](https://products.aspose.com/email/net/) használatával konvertálhatja az EMLX fájlformátumot HTML-re. Ezt követően az [Aspose.Words for .NET](https://products.aspose.com/words/net/) használatával a HTML-t DOT-be renderelheti.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API az EMLX DOT-vé konvertálásához" %}}
1. Nyissa meg az EMLX fájlt a [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage) osztály használatával
2. Alakítsa át az EMLX-címet HTML-vé a [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3) módszerrel
3. Töltse be a HTML-t a [Document](https://reference.aspose.com/words/net/aspose.words/document) osztály használatával
4. Mentse a dokumentumot DOT formátumba a [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) módszerrel, és állítsa be a Dot-t SaveFormat-ként.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverziós követelmények" %}}
Telepítés parancssorból ```nuget install Aspose.Total``` néven, vagy a Visual Studio Package Manager konzolján keresztül az ```Install-Package Aspose.Total``` paranccsal.

Alternatív megoldásként letöltheti az offline MSI telepítőt vagy a DLL-eket ZIP-fájlban a [downloads](https://releases.aspose.com/total/net) webhelyről.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.dot", SaveFormat.Dot); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Az EMLX fájl elemzése .NET-en keresztül" %}}
Az EMLX DOT-vé konvertálása előtt, ha meg szeretne győződni arról, hogy a megfelelő e-mailt konvertálja, töltse be az EMLX dokumentumot, elemezze, és tekintse meg a kívánt tulajdonságot. A [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, a küldő és a címzett információkat kaphat. Például a [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername) tulajdonság használatával ellenőrizheti a konverzióhoz tartozó feladó e-mail-címét.  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="A DOT-dokumentumszerkesztés korlátozása .NET-en keresztül" %}}
Amikor a dokumentumot EMLX-ből DOT-be menti, előfordulhat, hogy meg kell védenie a kimeneti dokumentumot. Előfordulhat, hogy korlátoznia kell egy dokumentum szerkesztésének lehetőségét, és csak bizonyos műveleteket kell engedélyeznie vele. Ez hasznos lehet annak megakadályozására, hogy mások szerkeszthessék a dokumentumban található érzékeny és bizalmas információkat. Az [Aspose.Words for .NET](https://products.aspose.com/words/net/) API lehetővé teszi a tartalom korlátozásának módját a [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) felsorolási paraméter. A következő kódsorok használatával beállíthatja dokumentumát írásvédettre. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Egyéb konverziós lehetőségek" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-pcl/" name="MSG TO PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-pdf/" name="MSG A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-dot/" name="MSG TO DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-flatopc/" name="MSG A FLATOPC-NEK" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-jpeg/" name="MSG - JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-png/" name="MSG - PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-rtf/" name="MSG TO RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-tiff/" name="MSG A TIFF-hez" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-docm/" name="MSG DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-ps/" name="MSG PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-gif/" name="MSG A GIF-re" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-xps/" name="MSG TO XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-odt/" name="MSG TO ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-docx/" name="MSG TO DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-doc/" name="MSG DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-wordml/" name="MSG A WORDML-hez" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-svg/" name="MSG – SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-epub/" name="MSG TO EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-md/" name="MSG MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-emf/" name="MSG TO EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-dotm/" name="MSG TO DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-ott/" name="MSG OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-dotx/" name="MSG DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/hu/net/conversion/msg-to-text/" name="ÜZENET SZÖVEGBE" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}