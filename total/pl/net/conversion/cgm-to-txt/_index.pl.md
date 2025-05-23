---
title: Konwertuj CGM na TXT za pomocą C# API
description: C# API do konwersji pliku CGM na TXT bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do renderowania CGM do TXT" h2="Eksportuj plik CGM do TXT za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo przekonwertować plik CGM na TXT w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do XLSX. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować XLSX na TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na TXT" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na XLSX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie TXT za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `Txt` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik CGM na TXT za pomocą C#" %}}
Jeśli dokument CGM jest chroniony hasłem, nie można go przekonwertować na TXT bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i przekazać nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na TXT za pomocą znaku wodnego za pomocą C#" %}}
Konwertując plik CGM na TXT, możesz także dodać znak wodny do wyjściowego formatu pliku TXT. Aby dodać znak wodny, możesz utworzyć nowy obiekt Workbook i otworzyć przekonwertowany dokument XLSX, wybrać Arkusz roboczy poprzez jego indeks, utworzyć Kształt i użyć jego funkcji AddTextEffect. Następnie możesz zapisać dokument XLSX jako TXT ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w TXT programowo: przypadki użycia" %}}
Pliky CGM (Computer Graphics Metafile) są używane do przechowania informacji o układach graficznych wektorowych, czyniąc je idealnymi dla tworzenia statycznych grafik i ilustracji. Jednak podczas pracy z danymi dynamicznymi edytory tekstu takie jak Notepad stają się niezbędne do podstawowych operacji na tekst oraz do tworzenia dokumentacji.

Przekonwertowanie plików CGM na formaty tekstowe jest konieczne, aby wykorzystać pełną funkcjonalność możliwości edytowania tekstu. Ta konwersja pozwala na:

**Użycia:**

*   **Dokumentacja danych**: Przekonwertować plik CGM na czytelny dla człowieka dokument, co ułatwia jego zrozumienie i udostępnianie informacji o układach graficznych.  
*   **Manipulacja tekstem**: Wykorzystać Notepad do edytowania i manipulacji prostego tekstu wyjętego z plików CGM, czyniąc go przydatnym dla podstawowych zadań edytorskich.  
*   **Tworzenie sztucznej sztuki ASCII**: Przekonwertować plik CGM na sztuk ASCII, tworząc prostą, tekstową reprezentację grafiki dla celów artystycznych lub dekoratywnych.  
*   **Import danych do innych narzędzi**: Wykorzystać format tekstowy do importu danych graficznych do innych edytorů tekstu lub programów do pisania słów, rozszerzając możliwości manipulacji tekstem.  
*   **Podstawowa raportowanie i debugowanie**: Przekonwertować plik CGM na podstawowe raporty i logi błędów, pomagające w identyfikacji błędów podczas procesu tworzenia.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}