---
title: C# API pro export EML do IMAGE
description: Převeďte EML na IMAGE bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/eml-to-image/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EMF WORDML PDF ODT MD TEXT DOTM DOC DOCX DOT DOCM IMAGE SVG EPUB JPEG RTF PNG XPS GIF PCL PS TIFF DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EML do IMAGE přes .NET" h2=".NET API pro vykreslení EML do IMAGE na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EML do funkcí převodu IMAGE ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EML na IMAGE" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu IMAGE pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Image jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EML přes .NET" %}}
Před převodem EML na IMAGE, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EML, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů IMAGE prostřednictvím .NET" %}}
Při ukládání dokumentu z EML do IMAGE může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EML do IMAGE: Případy použití" %}}
EML (Elektronické Maill) soubory jsou určeny pro ukládání textových emailů a používáné k vytvoření statické obsahové emailové zprávy. Nicméně, když se jedná o dynamické obrázky a grafiky, formáty jako JPEG nebo PNG jsou klíčoví pro vizuální komunikaci.

Konverze EML souborů do obrázkových formátů je nezbytná, aby bylo možné uvolnit plnou potenciál vizuální komunikace. Tato konverze umožňuje:

**Užití:**

*   **Vytvoření obsahu pro sociální média**: Konvertování EML souborů na engaging sociální media posts, obrázky a grafiky, které uchovají pozornost uživatele.
*   **Výstupy e-commerce**: Používání obrázkových formátů k zobrazování informací o produktech, jejich vlastností a výhodách v nápadné podobě.
*   **Kampaň digitálního marketingu**: Konvertování EML souborů na očarovující emailové kampaně, propagandistické materiály a prodejní stránky.
*   **Ilustrace blogů a článků**: Používání obrázkových formátů k ilustrování složitých blogových článků, článků a bílých knih.
*   **Technická dokumentace**: Konvertování EML souborů na vizálně přívodní technickou dokumentaci, uživatelské manuály a průvodce.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}