---
title: Konwertuj format JSON na DOC przez .NET
description: Przetwarzaj JSON do DOC w C# bez użycia Microsoft Word
url_ignore: /pl/net/conversion/json-to-doc/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: DOCM RTF EPUB PCL WORD DOT DOC MOBI PS DOTX ODT WORDML FLATOPC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na DOC za pomocą C#" h2="C# API do parsowania JSON do DOC bez użycia Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz analizować JSON do DOC w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwóch prostych kroki. Po pierwsze, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), możesz wyeksportować JSON do formatu PDF. Następnie, używając [Aspose.Words for .NET](https://products.aspose.com/words/net/), możesz przekonwertować PDF na DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DOC za pomocą C#" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/net/aspose.cells/workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zaimportuj plik JSON do arkusza roboczego za pomocą klasy [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) i [Save](https://reference.aspose.com/ cell/net/aspose.cells.workbook/save/methods/4) jako PDF
3. Załaduj dokument PDF za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Zapisz dokument w formacie DOC za pomocą metody [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i przekonwertuj format JSON na DOC za pomocą C#" %}}
Podczas analizowania JSON do DOC możesz również ustawić opcje układu dla swojego JSON za pomocą [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umożliwia przetwarzanie tablicy jako tabeli, ignorowanie wartości null, ignorowanie tytułu tablicy, ignorowanie tytułu obiektu, konwersję ciągu na liczbę lub datę, ustawianie formatu daty i liczby oraz ustawianie stylu tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przetwarzaj format JSON do DOC za pomocą znaku wodnego" %}}
Korzystając z API, możesz również przekonwertować JSON na DOC ze znakiem wodnym. Aby dodać znak wodny do dokumentu DOC, możesz najpierw przeanalizować plik JSON do formatu PDF i dodać do niego znak wodny. Aby dodać znak wodny, załaduj nowo utworzony plik PDF za pomocą klasy [Document](https://reference.aspose.com/words/net/aspose.words/document), utwórz instancję TextWatermarkOptions i ustaw jego właściwości, Wywołaj metodę Watermark.SetText i przekaż tekst znaku wodnego i obiekt TextWatermarkOptions. Po dodaniu znaku wodnego możesz zapisać dokument w DOC. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}