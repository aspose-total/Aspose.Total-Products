---
title: C# API pro export EML do DOC
description: Převeďte EML na DOC bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/eml-to-doc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOC
otherformats: EPUB PCL PDF JPEG DOCM DOC TEXT DOT MD RTF EMF DOTM SVG WORDML PS GIF TIFF XPS OTT ODT DOTX FLATOPC DOCX PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EML do DOC přes .NET" h2=".NET API pro vykreslení EML do DOC na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EML do funkcí převodu DOC ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EML na DOC" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu DOC pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Doc jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EML přes .NET" %}}
Před převodem EML na DOC, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EML, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů DOC prostřednictvím .NET" %}}
Při ukládání dokumentu z EML do DOC může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EML do DOC: Případy použití" %}}
Souborový soubor emailu je určen pro ukládání textových informací, což činí z něho ideální nástroj pro tvorbu čitelných dokumentů. Nicméně, když se jedná o práci s daty prezentace, stává se nezbytnými soubory Microsoft Office, jako jsou například Word, pro úpravu formátu a layoutsu dokumentů.

Konverze souborů emailu na formáty Word je nezbytná, aby bylo možné uvolnit plnou potenciálku tvorbě formátů a layoutů vašeho dokumentu. Tato konverze vám umožňuje:

**Užití:**

*   **Obchodní komunikace**: Konvertování souborů emailu na čitelné obchodní dokumenty, zprávy a návrhy.
*   **Zápisky z jednání a poznámky**: Využívání Wordu pro formátování zápisků z jednání, poznámek a akčních bodů, aby bylo možné zajistit jasnoúcházní porozumění mezi členy týmu.
*   **Osobní dopisování**: Konvertování souborů emailu na osobní dokumenty, jako jsou dopisy, certifikáty a pozvánky.
*   **Marketingový materiál**: Využívání Wordu pro tvorbu přitažlivého marketingového materiálu, jako jsou letáky, plakáty a tiskové releases.
*   **Profesní psaní**: Konvertování souborů emailu na vysoce profesionální obsah, jako jsou články, blogovy příspěvky a případové studie.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}