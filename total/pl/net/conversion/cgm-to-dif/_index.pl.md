---
title: Konwertuj CGM na DIF za pomocą C# API
description: C# API do konwersji pliku CGM na DIF bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/cgm-to-dif/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DIF
otherformats: FODS EXCEL ODS XLT TSV MD XLTX XLSB TXT DIF XLTM SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API do renderowania CGM do DIF" h2="Eksportuj plik CGM do DIF za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz łatwo przekonwertować plik CGM na DIF w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET. Po pierwsze, używając [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), możesz wyeksportować CGM do XLSX. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować XLSX na DIF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API do konwersji CGM na DIF" %}}
1. Otwórz plik CGM za pomocą klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Konwertuj CGM na XLSX za pomocą metody [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Załaduj dokument XLSX za pomocą klasy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie DIF za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) i ustaw `Dif` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony plik CGM na DIF za pomocą C#" %}}
Jeśli dokument CGM jest chroniony hasłem, nie można go przekonwertować na DIF bez hasła. Korzystając z interfejsu API, możesz najpierw otworzyć chroniony dokument przy użyciu prawidłowego hasła, a następnie przekonwertować go. Aby otworzyć zaszyfrowany plik, możesz zainicjować nowe wystąpienie klasy [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) i przekazać nazwę pliku i hasło jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj plik CGM na DIF za pomocą znaku wodnego za pomocą C#" %}}
Konwertując plik CGM na DIF, możesz także dodać znak wodny do wyjściowego formatu pliku DIF. Aby dodać znak wodny, możesz utworzyć nowy obiekt Workbook i otworzyć przekonwertowany dokument XLSX, wybrać Arkusz roboczy poprzez jego indeks, utworzyć Kształt i użyć jego funkcji AddTextEffect. Następnie możesz zapisać dokument XLSX jako DIF ze znakiem wodnym. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przekształcanie pliku CGM w DIF programowo: przypadki użycia" %}}
Przekształcenie plików CGM na formaty DIF jest niezbędne do wykorzystania pełnej możliwości Twoich umiejętności w zakresie tworzenia i edycji wektorowych grafik. Ten przekształcenie pozwala Ci:

**Użycia:**

*   **Edycja wektorowych grafik**: Przekształć pliki CGM, aby móc editować i manipulować wektorowymi grafikami, tworząc dokładne kształty i przerywania.  
*   **Projektowanie ilustracji**: Wykorzystać formaty DIF do tworzenia profesjonalnych ilustracji z kontrolą nad szerokością linii, stylem i kolorem.  
*   **Wizualizacja architektoniczna**: Przekształć pliki CGM do wizualizacji projektów architektonicznych, tworzenia 2D i 3D modeli oraz skutecznego przekazywania intencji projektu.  
*   **Projektowanie graficzne i drukowanie**: Wykorzystać formaty DIF do przygotowania wektorowych grafik do druku z wysokiej jakością wydruku i dokładnością w linii.  
*   **Automatyzacja CAD**: Przekształć pliki CGM, aby poprawić przepły w systemach CAD, takie jak automatyczne przekształcenia danych i zarządzanie plikami.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}