---
title: C# API do eksportu EMLX do IMAGE
description: Konwertuj EMLX na IMAGE bez używania Microsoft Word lub Outlook na .NET
url: /pl/net/conversion/emlx-to-image/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: PNG
otherformats: DOCX EMF MD TEXT DOT DOTM TIFF WORDML PS DOTX XPS PDF SVG FLATOPC JPEG DOCM DOC PCL EPUB OTT IMAGE ODT RTF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj EMLX do IMAGE przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do IMAGE w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji EMLX do IMAGE w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku EMLX na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji EMLX na IMAGE" %}}
1. Otwórz plik EMLX za pomocą klasy [MailMessage](https://apireference.aspose.com/emlx/net/aspose.emlx/mailmessage)
2. Konwertuj EMLX na HTML za pomocą metody [Save](https://apireference.aspose.com/emlx/net/aspose.emlx.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://apireference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie IMAGE za pomocą metody [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Image jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.emlx");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik EMLX przez .NET" %}}
Przed konwersją EMLX na IMAGE, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument EMLX, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://apireference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/emlx /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://apireference.aspose.com/emlx/net/aspose.emlx.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an EMLX file from disk
var outlookMessageFile = MapiMessage.FromFile("message.emlx");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów IMAGE przez .NET" %}}
Podczas zapisywania dokumentu z EMLX do IMAGE może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
```cs

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Png
document.Save("output.png", SaveFormat.Png);  
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