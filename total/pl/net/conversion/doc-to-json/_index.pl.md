---
title: Konwertuj DOC na format JSON przez .NET
description: Konwertuj DOC na JSON w C# bez użycia Microsoft Excel lub Adobe Reader
url_ignore: /pl/net/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: CSV XLAM SXC TSV XLT EXCEL DIF XLSM XLTM XLSX XLSB FODS ODS XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj DOC na format JSON za pomocą C#" h2="Przetwarzaj DOC do JSON za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Word lub Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz przekonwertować DOC na format JSON w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwóch proste kroki. Po pierwsze, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz wyeksportować DOC do HTML. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować HTML na JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj DOC na format JSON za pomocą C#" %}}
1. Otwórz plik DOC za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
2. Konwertuj DOC na HTML za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4)
3. Załaduj dokument HTML za pomocą klasy [Książka](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie JSON za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony DOC na format JSON za pomocą C#" %}}
Korzystając z interfejsu API, możesz również otworzyć dokument chroniony hasłem. Jeśli wejściowy dokument DOC jest chroniony hasłem, nie można go przekonwertować na format JSON bez użycia hasła. API umożliwia otwarcie zaszyfrowanego dokumentu poprzez podanie prawidłowego hasła w obiekcie LoadOptions. Poniższy przykład kodu pokazuje, jak spróbować otworzyć zaszyfrowany dokument za pomocą hasła:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-protected-word-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj DOC na JSON w zakresie za pomocą C#" %}}
Podczas konwertowania DOC na JSON możesz również ustawić zakres na wyjściowy format JSON. Aby ustawić zakres, możesz otworzyć przekonwertowany kod HTML za pomocą klasy Workbook, pobrać CellsCollection arkusza roboczego zawierającego dane, utworzyć zakres z CellsCollection, określając indeksy wierszy i kolumn, a następnie wywołać metodę ExportRangeToJson z odwołaniami do obiektów Range i ExportRangeToJsonOptions. Na koniec możesz zapisać dane JSON do pliku za pomocą metody File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "3320154ab7b06def2475ce90c7703f13" "convert-word-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}