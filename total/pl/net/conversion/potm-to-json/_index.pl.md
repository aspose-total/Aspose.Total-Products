---
title: Konwertuj POTM na format JSON przez .NET
description: Konwertuj POTM na JSON w C# bez użycia Microsoft Excel lub Powerpoint
url_ignore: /pl/net/conversion/potm-to-json/
family: total
platformtag: net
feature: conversion
informat: POTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj POTM na format JSON za pomocą C#" h2="Eksportuj POTM do JSON za pomocą C# bez użycia Microsoft<sup>&reg;</sup> Excel lub PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz przekonwertować POTM na format JSON w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwóch proste kroki. Po pierwsze, używając [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz wyeksportować POTM do HTML. Następnie, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, możesz przekonwertować HTML na JSON.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj POTM na format JSON za pomocą C#" %}}
1. Otwórz plik POTM za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
2. Konwertuj POTM na HTML za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
3. Załaduj dokument HTML za pomocą klasy [Książka](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Zapisz dokument w formacie JSON za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj chroniony POTM na format JSON za pomocą C#" %}}
Korzystając z interfejsu API, możesz również otworzyć dokument chroniony hasłem. Jeśli wejściowy dokument POTM jest chroniony hasłem, nie można go przekonwertować na format JSON bez użycia hasła. API umożliwia otwarcie zaszyfrowanego dokumentu poprzez podanie prawidłowego hasła w obiekcie LoadOptions. Poniższy przykład kodu pokazuje, jak otworzyć zaszyfrowany dokument za pomocą hasła.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-protected-powerpoint-to-json.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj POTM na JSON w zakresie za pomocą C#" %}}
Podczas konwertowania POTM na JSON możesz również ustawić zakres na wyjściowy format JSON. Aby ustawić zakres, możesz otworzyć przekonwertowany kod HTML za pomocą klasy Workbook, pobrać CellsCollection arkusza roboczego zawierającego dane, utworzyć zakres z CellsCollection, określając indeksy wierszy i kolumn, a następnie wywołać metodę ExportRangeToJson z odwołaniami do obiektów Range i ExportRangeToJsonOptions. Na koniec możesz zapisać dane JSON do pliku za pomocą metody File.WriteAllText. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "da55916905648dbb8430fcb52dc2e47f" "convert-powerpoint-to-json-range.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Inne opcje konwersji" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-doc/" name="POTM W celu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-docm/" name="POTM W celu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-docx/" name="POTM W celu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dot/" name="POTM W celu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dotm/" name="POTM W celu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-dotx/" name="POTM W celu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-odt/" name="POTM W celu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-ott/" name="POTM W celu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-rtf/" name="POTM W celu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-text/" name="POTM W celu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-word/" name="POTM W celu WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/net/conversion/potm-to-wordml/" name="POTM W celu WORDML" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}