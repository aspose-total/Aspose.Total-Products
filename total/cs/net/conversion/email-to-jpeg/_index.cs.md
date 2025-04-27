---
title: C# API pro export EMAIL do JPEG
description: Převeďte EMAIL na JPEG bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/email-to-jpeg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PNG DOC DOT EMF FLATOPC ODT MD TIFF XPS DOCM EPUB TEXT WORDML JPEG DOTM OTT PDF SVG DOCX GIF RTF PCL PS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMAIL do JPEG přes .NET" h2=".NET API pro vykreslení EMAIL do JPEG na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMAIL do funkcí převodu JPEG ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMAIL do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do JPEG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMAIL na JPEG" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu JPEG pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Jpeg jako SaveFormat
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
Před převodem EMAIL na JPEG, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMAIL, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů JPEG prostřednictvím .NET" %}}
Při ukládání dokumentu z EMAIL do JPEG může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.jpeg", SaveFormat.Jpeg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMAIL do JPEG: Případy použití" %}}
Konvertování emailových souborů na JPEG obrázky je nezbytností pro osvobození potenciálu vizuální内容。

Emailové soubory, obsahující klíčový datní materiál komunikace, lze účinně konvertovat na JPEG obrázky, které jsou ideální pro statickou vizuální reprezentaci a sdílení. Nicméně, když pracujeme s dynamickým obsahem, sociální média jako Instagram stávají nezbytnými pro vizuální storytelling a angažování.

Konvertování emailových souborů na formáty JPEG je nezbytné pro osvobození plného potenciálu vaší vizuální内容 a schopnosti sdílení. Toto konvertování vám umožňuje:

**Některá použití:**

*   **Sociální média a sdílení**: Konvertujte emailové soubory na JPEG obríky, které lze sdílet přes různé sociální média, čímž se zvyšuje dosah vaší аудиторie.
*   **E-commerce produktové vizualizace**: Používáte JPEG obríky k ukázání detailů produktu, specifikací a vlastností, což zkraseňuje online nákupní zkušenost.
*   **Promoce udělostních akcí a reklamy**: Konvertujte emailové soubory na JPEG obríky pro propagaci akcí, produktů nebo služeb, čímž vyhlídnete pozornost a naluzujete zájem.
*   **Infografiky a datační vizualizace**: Používáte JPEG obríky k vizualizaci dat, statistik a informací, vytvářející informativní a angažující obsah pro různé skupiny lidí.
*   **Digitální marketingové kampaně**: Konvertujte emailové soubory na JPEG obríky pro vytvoření očišťujících vizuálních materiálů pro kampaň, reklamu a propagandistické materiály.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}