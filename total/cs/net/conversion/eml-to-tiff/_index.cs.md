---
title: C# API pro export EML do TIFF
description: Převeďte EML na TIFF bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/eml-to-tiff/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: TIFF
otherformats: TIFF GIF XPS DOTX SVG ODT PCL DOCM PDF DOC PS RTF MD EPUB PNG FLATOPC DOTM DOCX EMF WORDML JPEG OTT DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EML do TIFF přes .NET" h2=".NET API pro vykreslení EML do TIFF na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EML do funkcí převodu TIFF ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EML do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do TIFF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EML na TIFF" %}}
1. Otevřete soubor EML pomocí třídy [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Převeďte EML na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu TIFF pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Tiff jako SaveFormat
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
Před převodem EML na TIFF, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EML, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů TIFF prostřednictvím .NET" %}}
Při ukládání dokumentu z EML do TIFF může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.tiff", SaveFormat.Tiff);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EML do TIFF: Případy použití" %}}
EML (Elektronický máilový soubor) jsou používány pro ukládání textových zpráv, což je ideální pro odesílání a přijímání e-melů. Nicméně, když se jedná o práci s obrážky, stávajíся formáty jako TIFF (Tagged Image File Format) nezbytnými pro uchování a manipulaci s vysokokvalitními obrázky.

Výkonvence EML souborů do TIFF formatu je nezbytná pro využívání plných možností vašeho schopností práce s obrážky. Tato konverze vám umožňuje:

**Užití:**

*   **Analyza lékařských obrázků**: Převést EML soubory pro analýzu lékařských obrázků, sledování postupu pacientů a identifikaci模式在数据中。
*   **Archivace a uchování**: Použít TIFF pro archivaci vysokokvalitních obrázků na účel archivace, zajistit, aby digitální artefakty zůstávaly stabilní po čase.
*   **Úprava a vylepšení obrázků**: Převést EML soubory pro tvorbu a úpravu obrázků, aplikování filtrů, úpravení a efektů pro dosažení požadovaného výsledku.
*   **Výpočty na vědeckých obrázcích**: Použít TIFF pro zpracování vědeckých obrázků, provádění registrace obrázků a zvýšení kvality obrázků pro další analýzu。
*   **Vyšetřování digitálních forensik**: Převést EML soubory pro vyšetřování digitálních důkazů, sledování online aktivity a reconstrukci digitálních událostí。
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}