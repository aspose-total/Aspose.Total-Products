---
title: C# API pro export CGM do ODT
description: Převeďte CGM na ODT bez použití aplikace Microsoft Word
url_ignore: /cs/net/conversion/cgm-to-odt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODT
otherformats: ODT MARKDOWN RTF PS XAMLFLOW DOTM PCL WORDML FLATOPC MHTML DOTX OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Vykreslete CGM na ODT přes .NET" h2=".NET API pro export CGM do ODT na Windows, macOS a Linux bez použití Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) je výkonné rozhraní API, které do vaší aplikace .NET přidává funkce pro manipulaci a převod dokumentů. Pomocí pokročilého rozhraní API pro zpracování PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) můžete převést formát souboru CGM na DOC. Poté můžete pomocí výkonného API pro zpracování dokumentů [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit DOC do ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod CGM na ODT" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Převeďte CGM na Doc pomocí metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Načtěte soubor Doc pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document) třídy Aspose.Words
4. Uložte dokument do formátu ODT pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Odt jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Dešifrovat soubor CGM pomocí hesla vlastníka přes .NET" %}}
Před převodem CGM na ODT, pokud chcete dešifrovat dokument, můžete to udělat pomocí API. Abyste mohli dešifrovat soubor PDF, musíte nejprve vytvořit objekt [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) a otevřít CGM pomocí hesla vlastníka. Poté musíte zavolat metodu [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) objektu Document. Nakonec uložte aktualizovaný soubor pomocí metody Save objektu Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Vytvořte soubor ODT pouze pro čtení přes .NET" %}}
Abyste ochránili svůj ODT před úpravami a zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu, můžete také nastavit ochranu dokumentu pomocí API. Můžete omezit možnost upravovat dokument a povolit s ním pouze určité akce. To lze provést pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Umožňuje vám ovládat způsob, jakým omezujete obsah, pomocí parametru výčtu [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru CGM do ODT: Případy použití" %}}
Konvertování souborů CGM na formáty ODT je nezbytné, aby se plně rozvířili možnosti vaší dokumentační vizualizace a analýzy. Toto konvertování vám umožňuje:

**Užití:**

*   **Dokumentní návrh a redigování**: Konvertovat soubory CGM na tvorbu interaktivních návrhů dokumentů, úpravu layoutu textu a validaci formátů textových částí.
*   **Business Reporting a vytváření dashboardů**: Použít ODT pro vizualizaci obchodních dat, jako jsou trendy ve prodeji, chování zákazníků a analýzy trhu.
*   **Technická písanost a dokumentace**: Konvertovat soubory CGM na tvorbu interaktivních dokumenčních materiálů, správu obsáhlých sbírek内容和追踪版本历史。
*   **Vývoj e-learningových materiálů**: Použít ODT pro vývoj interaktivních e-learningových materiálů, simulaci uživatelských zkušeností a validaci výstupních结果。
*   **Data Reporting a vizualizace**: Konvertovat soubory CGM na tvorbu datově řízených reportů, dashboardů a vizualizací pro zákazníky, čímž se zlepšuje rozhodování.

Konvertováním souborů CGM na formáty ODT můžete rozvířit plnou kapacitu vaší dokumentační vizualizace a analýzy.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}