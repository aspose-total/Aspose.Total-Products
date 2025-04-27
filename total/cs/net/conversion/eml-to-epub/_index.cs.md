---
title: C# API pro export EML do EPUB
description: Převeďte EML na EPUB bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/eml-to-epub/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: EPUB
otherformats: DOCM PCL PNG JPEG TIFF FLATOPC MD DOTM PS DOT DOCX EMF DOC WORDML ODT TEXT EPUB SVG OTT DOTX GIF RTF PDF XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EML do EPUB přes .NET" h2=".NET API pro vykreslení EML do EPUB na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EML do funkcí převodu EPUB ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EML na EPUB" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu EPUB pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Epub jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.eml");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EML přes .NET" %}}
Před převodem EML na EPUB, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EML, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EML file from disk
var outlookMessageFile = MapiMessage.FromFile("message.eml");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů EPUB prostřednictvím .NET" %}}
Při ukládání dokumentu z EML do EPUB může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EML do EPUB: Případy použití" %}}
EML (Electronic Mail) soubory jsou určeny pro ukládání textových informací, což je ideální pro osobní dopisování a spolupráci. Nicméně při práci s strukturovanou datem a multimediálními obsahy se stává EPUB (Electronic Publication) formáty nezbytnými pro digitální publikování a distribuci.

Konverze EML souborů na EPUB formáty je nezbytná, aby jste mohli využít plnou kapacitu své digitální obsaži a schopnosti v oblasti publikování. Tato konverze vám umožňuje:

**Užití:**

* **Digitální publikování:** Konverze EML souborů na EPUB formáty umožňuje vytvoření interaktivních digitálních publikací, časopisů a newsletterů, které jsou přístupné na různých zařízeních.

* **Vytváření elektronických knih (e-booků):** Použití EPUB formátů pro konverzi EML souborů na e-books umožňuje vytvoření čitelných textů pro čtení na e-časy, tabletech a smartphoních.

* **Publikování blogových článků:** Konverze EML souborů na EPUB formáty umožňuje publikování blogových článků v strukturovaném formátu, který zvyšuje jejich objevnost a přístupnost.

* **Vytvoření vědeckých článků:** Konverza EML souborů na EPUB formáty umožňuje vytvoření vědeckých článků, které jsou snadno sdíleny a citovány.

* **Společné práce na dokumentech:** Konverze EML souborů na EPUB formáty umožňuje vytvoření editelných dokumentů, které lze sdílet s ostatními, a tím usnadňuje spolupráci a zpětnou vazbu.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}