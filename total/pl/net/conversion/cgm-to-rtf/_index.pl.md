---
title: C# API do eksportu CGM do RTF
description: Konwertuj CGM na RTF bez użycia Microsoft Word
url_ignore: /pl/net/conversion/cgm-to-rtf/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: RTF
otherformats: MHTML WORDML OTT PS XAMLFLOW DOT ODT PCL RTF DOTX FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderuj CGM do RTF przez .NET" h2=".NET API do eksportu CGM do RTF w systemach Windows, macOS i Linux bez użycia Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) to zaawansowany interfejs API do dodawania funkcji manipulacji dokumentami i konwersji w Twojej aplikacji .NET. Korzystając z zaawansowanego interfejsu API przetwarzania plików PDF [Aspose.PDF dla .NET](https://products.aspose.com/pdf/net/), możesz przekonwertować format pliku CGM na DOC. Następnie, korzystając z potężnego interfejsu API przetwarzania dokumentów [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz renderować DOC do RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API do konwersji CGM na RTF" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na Doc za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj plik Doc za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document) Aspose.Words
4. Zapisz dokument w formacie RTF za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) i ustaw Rtf jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Odszyfruj plik CGM za pomocą hasła właściciela przez .NET" %}}
Przed konwersją CGM do RTF, jeśli chcesz odszyfrować swój dokument, możesz to zrobić za pomocą interfejsu API. Aby odszyfrować plik PDF, musisz najpierw utworzyć obiekt [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document) i otworzyć CGM przy użyciu hasła właściciela. Następnie musisz wywołać metodę [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) obiektu Document. Na koniec zapisz zaktualizowany plik za pomocą metody Save obiektu Document.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Utwórz plik RTF tylko do odczytu przez .NET" %}}
Aby chronić swój RTF przed edycją i uniemożliwić innym osobom edytowanie poufnych i poufnych informacji w Twoim dokumencie, możesz również ustawić ochronę dokumentu za pomocą interfejsu API. Możesz ograniczyć możliwość edycji dokumentu i zezwolić tylko na określone działania. Można to zrobić za pomocą interfejsu API [Aspose.Words for .NET](https://products.aspose.com/words/net/). Umożliwia kontrolowanie sposobu ograniczania zawartości za pomocą parametru wyliczenia [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype). Możesz ustawić dokument jako tylko do odczytu, używając następujących wierszy kodu. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w RTF programowo: przypadki użycia" %}}
Plik CGM (ang. Computer Graphics Metafile) jest przeznaczone do przechowania informacji o wektorowych grafikach, czyniąc go idealnym dla tworzenia statycznych grafik i ilustracji. Jednak przy dynamice danych takie programy jak Excel stają się niezbędne do wizualizacji i analzy.

Przekonwertowanie plików CGM na format RTF umożliwia wykorzystanie pełnych możliwości funkcji tekstowych. To może być przydatne w następujących przypadkach:

**Przykłady użycia:**

- **Tworzenie dokumentów**: Przekonwertowanie plików CGM na format RTF pozwala tworzyć profesjonalnie sformatowane dokumenty, raporty i prezentacje.
- **Edytowanie tekstu i formacie**: Format RTF może być wykorzystany do edytowania i formatowania tekstu z dokładną kontrolą nad stylem literkowym, wielkością czcionki, kolorem i układem.
- **Szablonów email i listów**: Przekonwertowanie plików CGM na format RTF pozwala tworzyć dostosowane szablony email, listy i inne korespondencje biznesowe.
- **Dessktop publikacji**: Format RTF może być użyty do tworzenia wysokiej jakości dokumentów, ulotek i innych materiałów do publikacji wewnętrznej lub zewnętrznej.
- **Pisanie technologicznego**: Przekonwertowanie plików CGM na format RTF pozwala tworzyć techniczne dokumenty, użytkownicyki rękopisy i przewodniki z dokładną kontrolą nad formacie i układem.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}