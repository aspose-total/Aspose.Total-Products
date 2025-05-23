---
title: C# API pro export EMLX do EPUB
description: Převeďte EMLX na EPUB bez použití Microsoft Word nebo Outlook na .NET
url_ignore: /cs/net/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: GIF OTT PCL PS EMF RTF DOCM TEXT XPS PNG DOCX DOT EPUB ODT MD FLATOPC DOTM DOTX DOC JPEG WORDML PDF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportujte EMLX do EPUB přes .NET" h2=".NET API pro vykreslení EMLX do EPUB na Windows, macOS a Linux bez použití Wordu nebo Outlooku" >}}

{{% blocks/products/pf/feature-page-summary %}}
Pokud jste vývojář .NET, který chce přidat EMLX do funkcí převodu EPUB ve svých aplikacích, [Aspose.Total for .NET](https://products.aspose.com/total/net/) API pro manipulaci s formátem souborů jsou tím způsobem vpřed. Pomocí [Aspose.Email for .NET](https://products.aspose.com/email/net/) můžete převést formát souboru EMLX do HTML. Poté můžete pomocí [Aspose.Words for .NET](https://products.aspose.com/words/net/) vykreslit HTML do EPUB.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API pro převod EMLX na EPUB" %}}
1. Otevřete soubor EMLX pomocí třídy [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Převeďte EMLX na HTML pomocí metody [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Načtěte HTML pomocí třídy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Uložte dokument do formátu EPUB pomocí metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) a nastavte Epub jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo pomocí konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.epub", SaveFormat.Epub); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analyzujte soubor EMLX přes .NET" %}}
Před převodem EMLX na EPUB, pokud se chcete ujistit, že převádíte správný e-mail, můžete načíst dokument EMLX, analyzovat jej a podívat se na požadovanou vlastnost. Pomocí třídy [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) třídy [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, můžete získat informace o odesílateli a příjemcích. Můžete například zkontrolovat e-mail konkrétního odesílatele pro konverzi pomocí vlastnosti [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Omezit úpravy dokumentů EPUB prostřednictvím .NET" %}}
Při ukládání dokumentu z EMLX do EPUB může být nutné chránit výstupní dokument. Někdy může být nutné omezit možnost upravovat dokument a povolit s ním pouze určité akce. To může být užitečné, abyste zabránili jiným lidem upravovat citlivé a důvěrné informace ve vašem dokumentu. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API vám umožňuje ovládat způsob, jakým omezujete obsah pomocí [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parametr výčtu. Pomocí následujících řádků kódu můžete dokument nastavit tak, aby byl jen pro čtení. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.epub", SaveFormat.Epub);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Programová transformace souboru EMLX do EPUB: Případy použití" %}}
EMLX (Elektronický Майл с X-Based Headers) файлы предназначены для хранения информации о почтовых сообщениях, что делает их идеальным выбором для создания статических писем и архивов сообщений. Однако при работе со динамическими данными форматы ePUB становятся необходимостью для цифровой публикации и распределения онлайн контента.

Преобразование EMLX файлов в форматы ePUB позволяет раскрыть полную функциональность вашей деятельности по цифровой публикации и распределению онлайн контента. Это преобразование позволяет вам:

**Настоявки:**

*   **Цифровая публикация**: Преобразовать EMLX файлы для создания интерактивных цифровых журналов, газет и книг, доступных на различных устройствах.
*   **Распределение контента для обучения онлайн**: Использовать формат ePUB для публикации онлайн курсов, учебников и материалов для обучения, улучшая опыт учения для студентов и профессионалов.
*   **Публикация онлайн статей**: Преобразовать EMLX файлы для создания привлекательных статей, историй и постов в блогах, увеличивая онлайн вовлеченность и удовлетворенность читателей.
*   **Цифровые комиксы и романы**: Использовать формат ePUB для сохранения и распределения цифровых комиксов, романов и других форм интерактивного повествования, предлагая уникальный опыт чтения пользователям.
*   **Синхронизация контента на веб-страницах**: Преобразовать EMLX файлы для создания динамических содержимых веб-сайтов, таких как статьи, описания продуктов и отзывы клиентов, что улучшает пользовательскую вовлеченность и коэффициент преобразования на сайте.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}