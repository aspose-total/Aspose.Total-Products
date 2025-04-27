---
title: C# API pro export EML do EMF
description: Převeďte EML na EMF bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/eml-to-emf/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EMF
otherformats: DOC PS DOTX MD PNG XPS GIF DOTM DOT SVG JPEG EPUB OTT TIFF WORDML FLATOPC DOCM PDF EMF TEXT RTF PCL ODT DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EML do EMF přes .NET" h2=".NET API pro vykreslení EML do EMF na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EML do funkcí převodu EMF ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do EMF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EML na EMF" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu EMF pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Emf jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.emf", SaveFormat.Emf); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EML přes .NET" %}}
Před převodem EML na EMF, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EML, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů EMF prostřednictvím .NET" %}}
Při ukládání dokumentu z EML do EMF může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.emf", SaveFormat.Emf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EML do EMF: Případy použití" %}}
EML (Elektronická pošta) soubory jsou určeny pro ukládání zpráv pošty, čímž se stávají ideálem pro tvorbu statických dokumentů a záznamů o komunikacích. Nicméně při práci s dynamickými údajemi se stává formáty EMF nezbytnými pro uchování vizuální忠实ности a ostré podrobnosti.

Konverze EML souborů do formátu EMF je nezbytná, aby bylo možné uvolnit plnou potenciálku svého dokumentu a analýzy. Tato konverze umožňuje:

**Němoci:**

*   **Uchovávanie a soulize se zákonnými požadavky**: Konvertovat EML soubory do formátu EMF pro vytvoření vyhledatelných, editovatelných záznamů o komunikacích pošty, zajistit souliz se zákonními požadavky.
*   **Digitální forenzní výzkum a vyšetřování**: Použít EMF pro analýzu a uchování důkazů pošty, sledování digitálních stop a reconstrukci scénářů komunikací.
*   **Analyza marketingových kampaní**: Konvertovat EML soubory do formátu EMF pro měření účinnosti kampaní pošty, optimalizaci seznamu odesílajících a zvýšení čtenářských率.
*   **Vývoj platformy pro e-lerning**: Vytvořit interaktivní moduly e-lerningu konvertováním EML souborů do formátu EMF, čímž se zvyšují učeňová zkušenství.
*   **Uchování archivů historických záznamů**: Použít EMF pro digitální uchování starých záznamů pošty, zajistit jejich uchování pro budoucí generace a poskytnout cenné informace o minulém vzájemném kontaktu.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}