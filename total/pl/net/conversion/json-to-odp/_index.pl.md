---
title: Konwertuj format JSON na ODP przez .NET
description: Przetwarzaj JSON do ODP w C# bez użycia Microsoft PowerPoint
url_ignore: /pl/net/conversion/json-to-odp/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODP
otherformats: PPT OTP PPSX POWERPOINT POTM POT PPSM POTX PPTM PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na ODP za pomocą C#" h2="C# API do parsowania JSON do ODP bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Możesz przekonwertować JSON na ODP w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwóch prostych krokach. Po pierwsze, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), możesz przetworzyć JSON na PPTX. Następnie, używając [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), możesz przekonwertować PPTX na ODP. Oba interfejsy API są objęte pakietem [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na ODP za pomocą C#" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/net/aspose.cells/workbook) i odczytaj prawidłowe dane JSON z pliku
2. Zaimportuj plik JSON do arkusza roboczego za pomocą klasy [JsonUtility](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonutility) i [Save](https://reference.aspose.com/ cell/net/aspose.cells.workbook/save/methods/4) to jako PPTX
3. Załaduj dokument PPTX za pomocą klasy [Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Zapisz dokument w formacie ODP za pomocą metody [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i konwertuj format JSON na ODP za pomocą C#" %}}
Podczas analizowania JSON do ODP możesz również ustawić opcje układu dla formatu JSON za pomocą [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Pozwala przetwarzać tablicę jako tabelę, ignorować wartości null, ignorować tytuł tablicy, ignorować tytuł obiektu, konwertować ciąg na liczbę lub datę, ustawić format daty i liczby oraz ustawić styl tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj format JSON na ODP za pomocą znaku wodnego" %}}
Korzystając z API, możesz również przekonwertować JSON na ODP ze znakiem wodnym. Aby dodać znak wodny do dokumentu ODP, możesz najpierw przeanalizować JSON do PPTX i dodać do niego znak wodny. Aby dodać znak wodny, wczytaj nowo utworzony plik PPTX za pomocą klasy [Prezentacja](https://reference.aspose.com/slides/net/aspose.slides/presentation), wybierz prezentację wzorcową, dodaj typ kształtu za pomocą AddAutoShape i dodaj tekst znaku wodnego za pomocą AddTextFrame. Po dodaniu znaku wodnego możesz zapisać dokument w ODP. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}