---
title: C# API do eksportu MSG do TEXT
description: Konwertuj MSG na TEXT bez używania Microsoft Word lub Outlook na .NET
url_ignore: /pl/net/conversion/msg-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: DOCX RTF MD TIFF PS ODT DOC FLATOPC JPEG DOCM DOTX GIF EMF TEXT EPUB DOT PNG PDF SVG DOTM WORDML OTT XPS PCL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Eksportuj MSG do TEXT przez .NET" h2="Interfejs API .NET do renderowania poczty e-mail do TEXT w systemach Windows, macOS i Linux bez korzystania z programu Word lub Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Jeśli jesteś programistą .NET i chcesz dodać funkcje konwersji MSG do TEXT w swoich aplikacjach, najlepszym rozwiązaniem są interfejsy API [Aspose.Total for .NET](https://products.aspose.com/total/net/) Naprzód. Używając [Aspose.Email for .NET](https://products.aspose.com/email/net/), możesz przekonwertować format pliku MSG na HTML. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować HTML do TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji MSG na TEXT" %}}
1. Otwórz plik MSG za pomocą klasy [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Konwertuj MSG na HTML za pomocą metody [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Załaduj HTML za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie TEXT za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Text jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.text", SaveFormat.Text); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Przeanalizuj plik MSG przez .NET" %}}
Przed konwersją MSG na TEXT, jeśli chcesz się upewnić, że konwertujesz poprawny e-mail, możesz załadować dokument MSG, przeanalizować go i spojrzeć na żądaną właściwość. Korzystając z klasy [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, możesz uzyskać informacje o nadawcy i odbiorcy. Na przykład możesz sprawdzić konkretny adres e-mail nadawcy dla konwersji za pomocą właściwości [NazwaNadawcy](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
.aspose.com
{{% blocks/products/pf/feature-page-section  h2="Ogranicz edycję dokumentów TEXT przez .NET" %}}
Podczas zapisywania dokumentu z MSG do TEXT może być konieczne zabezpieczenie dokumentu wyjściowego. Czasami może zajść potrzeba ograniczenia możliwości edycji dokumentu i zezwolenia tylko na określone czynności. Może to być przydatne, aby uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie. Interfejs API [Aspose.Words for .NET](https://products.aspose.com/words/net/) umożliwia kontrolowanie sposobu ograniczania treści za pomocą [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) parametr wyliczenia. Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}