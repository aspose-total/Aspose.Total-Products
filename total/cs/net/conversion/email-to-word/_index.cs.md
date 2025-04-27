---
title: C# API pro export EMAIL do WORD
description: Převeďte EMAIL na WORD bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/email-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: DOCM ODT TEXT PCL OTT DOCX PS FLATOPC EPUB XPS GIF WORD DOTX DOC DOTM MD WORDML PDF DOT JPEG PNG RTF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMAIL do WORD přes .NET" h2=".NET API pro vykreslení EMAIL do WORD na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMAIL do funkcí převodu WORD ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMAIL do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMAIL na WORD" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu WORD pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EMAIL přes .NET" %}}
Před převodem EMAIL na WORD, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMAIL, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů WORD prostřednictvím .NET" %}}
Při ukládání dokumentu z EMAIL do WORD může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMAIL do WORD: Případy použití" %}}
Převezení emailů do složeků: Křtiny plná komunikace

Emaily jsou ideální pro ukládání krátkých zpráv, takže jsou vhodné pro každodenní písmo a neformální komunikaci. Nicméně, když jde o vytváření profesionálních dokumentů a jejich prezentaci, stává se Wordem nezbytným pro sdělení složitějších informací a představ.

Převezení obsahu emailů do formátu Word je nezbytné, aby se mohlo plně využít schopnosti vaší komunikace. Toto převézání vám umožňuje:

**Užití:**

*   **Business Reports**: Převezení emailů pro vytvoření profesionálních business reportů, které zobrazují informace o společnosti, finanční data a trendy na trhu.
*   **Policy Briefs and Proposals**: Využití Wordu pro vytváření formálních policy briefů, návrhů a prezentací pro rozhodující osobnosti, zúčastněné strany a klienty.
*   **Academic Papers and Research Reports**: Převezení emailů pro vytvoření vysokokvalitních akademických článků, výzkumných zpráv a přehledů literatury s přesným citováním a odkazováním.
*   **Meeting Minutes and Agendas**: Využití Wordu pro vytváření formálních protokolů zasedání, agend a sumarií, které usnadňují efektivní komunikaci a archivování informací.
*   **Personal Essays and Blog Posts**: Převezení emailů pro vytvoření osobních esejů, blogových příspěvků a článků, které zobrazují uměleckou schopnost a kreativitu.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}