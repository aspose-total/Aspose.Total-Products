---
title: Konwertuj CGM na ODS za pomocą C# API
description: C# API do konwersji pliku CGM na ODS bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/cgm-to-ods/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: ODS
otherformats: SXC XLT XLAM XLTM XLSB EXCEL ODS TXT XLSM TSV FODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do renderowania CGM do ODS" h2="Eksportuj plik CGM do ODS za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo przekonwertować plik CGM na ODS w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do XLSX. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować XLSX na ODS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na ODS" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na XLSX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie ODS za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `Ods` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik CGM na ODS za pomocą C#" %}}
Jeśli dokument CGM jest chroniony hasłem, nie można go przekonwertować na ODS bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i przekazać nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na ODS za pomocą znaku wodnego za pomocą C#" %}}
Konwertując plik CGM na ODS, możesz także dodać znak wodny do wyjściowego formatu pliku ODS. Aby dodać znak wodny, możesz utworzyć nowy obiekt Workbook i otworzyć przekonwertowany dokument XLSX, wybrać Arkusz roboczy poprzez jego indeks, utworzyć Kształt i użyć jego funkcji AddTextEffect. Następnie możesz zapisać dokument XLSX jako ODS ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w ODS programowo: przypadki użycia" %}}
Przekształcenie plików CGM (Computer Graphics Metafile) na formaty ODS (OpenDocument Spreadsheet) jest niezbędne, aby rozwiązać pełną potęgę swoich umiejętności wizualizacji i analizy danych. To przekształcenie pozwala Ci:

**Użycia przypadków:**

* **Analiza inteligencji biznesowej**: Przekształcenie plików CGM do analizu wykładu biznesowego, śledzenia kluczowych metryk i identyfikacji trendów w danych.
* ** Kontrola jakości danych**: Wykorzystanie formatu ODS do sprawdzania integralności danych, wykrywania błędów i zapewnienia spójności między różnymi zestandarzami danych.
* **Analiza badania rynku**: Przekształcenie plików CGM do analizu trendów rynkowych, zachowania klientów oraz działalności konkurencji.
* **Optymizacja wydajności operacyjnej**: Wykorzystanie formatu ODS do optymalizacji procesów biznesowych, identyfikacji obszarów poprawki i pomiaru skutków zmian.
* **Planowanie finansowe i raportowanie**: Przekształcenie plików CGM do tworzenia modeli finansowych, prognozowania przychodków i śledzenia kosztów.

Przekształcenie plików CGM na formaty ODS pozwala również wykorzystać silne funkcje tego formatu, takie jak:

* Formatowanie warunkowe
* Tablice końcowe
* Walidacja danych
* Narzędzia współpracy

Przekształniając swoje pliki CGM na formaty ODS, możesz wyzwolić się z szerokiej gamy benefitów, w tym wzrost świadomości danych, poprawę współpracy i lepsze przepowiedni biznesowe.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}