---
title: C# API do eksportu OFT do FLATOPC
description: Konwertuj OFT na FLATOPC bez używania Microsoft Word lub Outlook na .NET
url: /pl/net/conversion/oft-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: FLATOPC
otherformats: JPEG MD DOCX RTF PCL TIFF DOT PS PNG EMF DOTM OTT GIF PDF TEXT DOCM FLATOPC WORDML DOTX EPUB ODT DOC XPS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj OFT do FLATOPC przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do FLATOPC w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji OFT do FLATOPC w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Oft for .NET](https://products.aspose.com/oft/net/), możesz przekonwertować format pliku OFT na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do FLATOPC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji OFT na FLATOPC" %}}
1. Otwórz plik OFT za pomocą klasy [MailMessage](https://apireference.aspose.com/oft/net/aspose.oft/mailmessage)
2. Konwertuj OFT na HTML za pomocą metody [Save](https://apireference.aspose.com/oft/net/aspose.oft.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie FLATOPC za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Flatopc jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.oft");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.FlatOpc
document.Save("output.flatopc", SaveFormat.FlatOpc); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik OFT przez .NET" %}}
Przed konwersją OFT na FLATOPC, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument OFT, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage) [Aspose.Oft for .NET](https://products.aspose.com/oft /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an OFT file from disk
var outlookMessageFile = MapiMessage.FromFile("message.oft");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów FLATOPC przez .NET" %}}
Podczas zapisywania dokumentu z OFT do FLATOPC może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.FlatOpc
document.Save("output.flatopc", SaveFormat.FlatOpc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-pcl/" name="MSG DO PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-pdf/" name="MSG DO PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-dot/" name="WIADOMOŚĆ DO KROPKI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-flatopc/" name="MSG DO FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-jpeg/" name="MSG DO JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-png/" name="WIADOMOŚĆ DO PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-rtf/" name="MSG DO RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-tiff/" name="WIADOMOŚĆ DO TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-docm/" name="WIADOMOŚĆ DO DOKUMENTU" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-ps/" name="WIADOMOŚĆ DO PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-gif/" name="WIADOMOŚĆ NA GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-xps/" name="MSG DO XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-odt/" name="MSG DO ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-docx/" name="MSG DO DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-doc/" name="WIADOMOŚĆ DO DOKUMENTU" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-wordml/" name="MSG DO WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-svg/" name="MSG DO SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-epub/" name="WIADOMOŚĆ DO EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-md/" name="MSG DO MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-emf/" name="MSG DO EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-dotm/" name="MSG DO DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-ott/" name="WIADOMOŚĆ DO OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-dotx/" name="MSG DO DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/msg-to-text/" name="WIADOMOŚĆ DO TEKSTU" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}