---
title: C# API pro export EMAIL do WORDML
description: Převeďte EMAIL na WORDML bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/email-to-wordml/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: WORDML
otherformats: MD TIFF OTT DOCM EMF DOTM PNG SVG DOT TEXT DOTX DOCX PDF DOC WORDML GIF FLATOPC EPUB ODT JPEG XPS RTF PS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMAIL do WORDML přes .NET" h2=".NET API pro vykreslení EMAIL do WORDML na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMAIL do funkcí převodu WORDML ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMAIL do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do WORDML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMAIL na WORDML" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu WORDML pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Wordml jako SaveFormat
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
Před převodem EMAIL na WORDML, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMAIL, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů WORDML prostřednictvím .NET" %}}
Při ukládání dokumentu z EMAIL do WORDML může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.WordML
document.Save("output.wordml", SaveFormat.WordML);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMAIL do WORDML: Případy použití" %}}
Emailové soubory jsou používány pro ukládání textových informací na základě komunikace, což je ideální pro odesílání zpráv příjemcům. Nicméně při práci s daty prezentací se stává WordML (anglicky) nezbytným formátem pro vytvoření profesionálních dokumentů a prezentací.

Konverze emailových souborů na formáty WordML je nezbytná, aby jste mohli rozvířit plný potenciál své schopnosti tvorby dokumentů a designu prezentací. Tato konverze vám umožňuje:

**Použití:**

*   **Business Correspondence**: Konvertování emailových souborů na vytvoření formálních obchodních zpráv, návrhů a protokollů zasedání.
*   **Presentation Design**: Použití WordML pro návrh engaging prezentací, přidávání multimediálních prvků a integraci interaktivity.
*   **Document Templates**: Konvertování emailových souborů na vytvoření použitelných šablon pro často používané dokumenty, jako jsou smlouvy a politiky.
*   **Research Collaboration**: Použití WordML pro sdílení výsledků výzkumu, spolupráci se kolegy a sledování pokroku.
*   **Marketing Content Creation**: Konvertování emailových souborů na vytvoření propagandistického materiálu, příspěvků pro sociální média a článků.

Konvertováním vašich emailových souborů na formát WordML můžete rozvířit nové možnosti tvorby dokumentů, designu prezentací a spolupráce.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}