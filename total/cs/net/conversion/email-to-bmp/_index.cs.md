---
title: C# API pro export EMAIL do BMP
description: Převeďte EMAIL na BMP bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/email-to-bmp/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: BMP
otherformats: PCL PDF DOT FLATOPC JPEG PNG RTF TIFF DOCM PS GIF XPS ODT DOCX DOC WORDML SVG EPUB MD EMF DOTM OTT DOTX TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMAIL do BMP přes .NET" h2=".NET API pro vykreslení EMAIL do BMP na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMAIL do funkcí převodu BMP ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMAIL do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do BMP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMAIL na BMP" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu BMP pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Bmp jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EMAIL přes .NET" %}}
Před převodem EMAIL na BMP, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMAIL, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů BMP prostřednictvím .NET" %}}
Při ukládání dokumentu z EMAIL do BMP může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.bmp", SaveFormat.Bmp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMAIL do BMP: Případy použití" %}}
Emailové soubory jsou používány pro ukládání textu, což je ideální pro tvorbu profesionálních komunikat a dopisů. Nicméně, když pracujeme se vizuálními údajmi, jako jsou obrázky ve formátu BMP, stávají se nezbytnými pro přidání multimédia.

Výkon převodu Emailových souborů do formátu BMP je nezbytný pro rozvíjení plného potenciálu vašich multimédia. Tento převod umožňuje:

**Užití:**

*   **Zvukání událostí**: Převést emailové soubory na vidětky s krásnými grafikami a obrázky pro zvukání událostí.
*   **Výstava produktů e-commerce**: Použít BMP pro přidání vysokokvalitních obrázků produktů do emailových obchodních stránek, čímž se zvyšuje užívání zákazníků a prodej.
*   **Kampány marketingu**: Převést emailové soubory na vidětky s očarovými banery a obrázky pro marketingové kampaně, čímž se zvýší angažmáni a konverzní časy.
*   **Osobní sdělení**: Použít BMP pro přidání osobních obrázků a grafik ke emailovým zprávám, čímž se vytvoří více osobního a pamětihodného zážitku pro příjemce.
*   **Design newsletter**: Převést emailové soubory na vidětky s obrázky a multimédia pro tvorbu krásných newsletterů, čímž se zvyšuje angažmáni a informovanost odběračů.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}