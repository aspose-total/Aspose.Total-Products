---
title: C# API pro export EMAIL do IMAGE
description: Převeďte EMAIL na IMAGE bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/email-to-image/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: WORDML FLATOPC DOCM DOTX TIFF SVG TEXT PS DOT GIF EPUB RTF DOTM JPEG DOCX ODT PDF IMAGE XPS PNG EMF PCL DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMAIL do IMAGE přes .NET" h2=".NET API pro vykreslení EMAIL do IMAGE na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMAIL do funkcí převodu IMAGE ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMAIL do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMAIL na IMAGE" %}}
1. Otevřete soubor EMAIL pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMAIL na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EMAIL přes .NET" %}}
Před převodem EMAIL na IMAGE, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMAIL, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů IMAGE prostřednictvím .NET" %}}
Při ukládání dokumentu z EMAIL do IMAGE může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMAIL do IMAGE: Případy použití" %}}
**Konverze emailu na obrázek: Křtiny vizuální storytellingu**

Emaily jsou účinným způsobem pro sdělení informací, ale chybí jim vizuální přitažlivost oproti jiným formátům, jako jsou obrázky. Konverze emailových souborů na obrázkové formáty je nezbytná, aby se uvolnilo plné potenciál vizuální storytellingu a aby se obsah uchoval pro budoucí reference.

Konverze emailových souborů na obrázkové formáty je důležitá pro:

**Užití:**

*   **Uchovaní obsahu**: Konvertovat emaily na obrázky, aby bylo možné uchovávat obsah, jako jsou zápisky schůzí, obchodní smlouvy nebo projektové plány, a mít je k dispozici pro budoucí reference.
*   **Ochrana značky**: Použít konverzi na obrázky, aby se uchovaly vizuální prvky společnosti, jako jsou loga a další označení, a aby bylo zajištěno konzistentnost po všech komunikačních kanálech.
*   **Elektronický archiv**: Konvertovat emaily na obrázky, aby vznikl elektronický archiv historie společnosti, včetně důležitých událostí, milníků a rozhodujících procesů.
*   **Přístupnost a inkluzi**: Konvertovat emaily na obrázky, aby byl obsah přístupnější uživatelům se zrakovými postižením nebo jinými porážkami, a aby bylo možné přidat alternativní popisy pro kontextuální informace.
*   **Bezpečnost a soulhavost**: Použít konverzi na obrázky, aby byla chráněna citlivá data před neautorizovaným přístupem, a aby se splnilé pravidla regulace pro ochranu údajů a konfidenčnost.

Prostřednictvím konverze emailových souborů na obrázkové formáty organizace mohou uvolnit plný potenciál vizuální storytellingu, uchovat obsah a zajišťovat soulhavost se zákonem.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}