---
title: Konwertuj format JSON na DICOM przez .NET
description: Przetwarzaj JSON do DICOM w C# bez korzystania z zależności stron trzecich
url_ignore: /pl/net/conversion/json-to-dicom/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DICOM
otherformats: DICOM IMAGE SVGZ TGA WMZ WMF PSD EMZ DXF JPEG2000
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Konwertuj format JSON na DICOM za pomocą C#" h2="C# API do parsowania JSON do DICOM bez korzystania z zależności stron trzecich" >}}

{{% blocks/products/pf/feature-page-summary %}}
Używając [Aspose.Total for .NET](https://products.aspose.com/total/net/) możesz parsować JSON do DICOM w dowolnej aplikacji .NET, C#, ASP.NET i VB.NET w dwóch prostych kroki. Po pierwsze, używając [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), możesz wyeksportować JSON do JPEG. Następnie, używając [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), możesz przekonwertować JPEG na DICOM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konwertuj format JSON na DICOM za pomocą C#" %}}
1. Utwórz nowy obiekt [Skoroszyt](https://reference.aspose.com/cells/net/aspose.cells/workbook) i odczytaj dane JSON z pliku
2. Konwertuj JSON na JPEG za pomocą metody [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Załaduj dokument JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image)
4. Zapisz dokument w formacie DICOM metodą [Save](https://reference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total```.

Możesz też pobrać instalator offline MSI lub biblioteki DLL w pliku ZIP ze strony [downloads](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ustaw układ i przekonwertuj format JSON na DICOM za pomocą C#" %}}
Podczas analizowania JSON do DICOM możesz także ustawić opcje układu dla swojego JSON za pomocą [JsonLayoutOptions](https://reference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutoptions). Umożliwia przetwarzanie tablicy jako tabeli, ignorowanie wartości null, ignorowanie tytułu tablicy, ignorowanie tytułu obiektu, konwersję ciągu na liczbę lub datę, ustawianie formatu daty i liczby oraz ustawianie stylu tytułu. Wszystkie te opcje umożliwiają prezentację danych zgodnie z własnymi potrzebami. Poniższy fragment kodu pokazuje, jak ustawić opcje układu.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Przetwarzaj format JSON do DICOM za pomocą znaku wodnego" %}}
Korzystając z API, możesz również przekonwertować JSON na DICOM ze znakiem wodnym w swoim dokumencie DICOM. Aby dodać znak wodny, możesz najpierw wyrenderować dokument JSON do formatu JPEG i dodać do niego znak wodny. Aby zademonstrować operację, możesz załadować przekonwertowany obraz JPEG, dodać przekształcenia za pomocą obiektu klasy Matrix i narysować ciąg znaków jako znak wodny na powierzchni obrazu za pomocą [Grafika](https://reference.aspose.com/imaging/ net/aspose.imaging/graphics) metoda [DrawString](https://reference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Po dodaniu do niego znaku wodnego możesz zapisać plik JPEG jako format DICOM. Poniżej znajduje się przykład kodu, który pokazuje, jak dodać ukośny znak wodny do dokumentu. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}