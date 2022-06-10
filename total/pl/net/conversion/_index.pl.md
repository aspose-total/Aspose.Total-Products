---
title: Konwersja formatu pliku za pomocą C# 
url: /pl/net/conversion/
description: Konwertuj Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, obrazy 3D, diagramy, formaty wideo i wiele innych popularnych plików za pomocą zaledwie kilku linijek kodu C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja formatu pliku za pomocą C# .NET" h2="Konwertuj pliki Microsoft<sup>&reg;</sup> Office, PDF, obrazy, HTML i inne formaty bez użycia innego oprogramowania." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Całkowita biblioteka .NET](https://products.aspose.com/total/net/) przyspiesza tworzenie od podstaw rozwiązań do zarządzania dokumentami lub ulepsza istniejące aplikacje, aby z łatwością radziły sobie z manipulacją dokumentami. API nie tylko zarządza dokumentami Microsoft Office, ale także obsługuje pliki PDF, HTML, obrazy TIFF, JPG, PNG, BMP i SVG, pliki e-mail, formaty wideo, formaty danych GIS i wiele innych. Jest to kompletny zestaw interfejsów API rozwiązań do zarządzania i manipulacji dokumentami bez żadnych zależności programowych. Programiści mogą łatwo tworzyć, aktualizować, renderować, drukować i konwertować między najpopularniejszymi formatami w dowolnych aplikacjach opartych na .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj Word na PDF" %}}
Total API obsługuje nie tylko konwersję między formatami Microsoft Word, ale także konwersję Worda do formatu PDF, HTML, obrazów, EPUB, Markdown i XPS. Proces konwersji jest prosty. Załaduj Document przez klasę Document i po prostu wywołaj metodę Save z formatem docelowym. To takie proste. Deweloperzy mogą sprawdzić [wynik konwersji](https://products.aspose.com/words/net/conversion/word-to-pdf/) przed integracją kodu **Word do PDF**


{{% blocks/products/pf/feature-page-code h3="C# - Konwersja Word do PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Konwertuj PDF na obrazy" %}}
API obsługuje konwersję plików PDF na obrazy, PowerPoint, Excel i inne formaty. W przypadku konwersji PDF na obraz rozważmy obraz JPG jako plik docelowy. Proces polega na załadowaniu pliku PDF przy użyciu klasy Document i zainicjowaniu obiektu [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) i wyrenderowaniu pliku PDF do JPEG za pomocą [Process](https ://apireference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
Załaduj plik JPEG przy użyciu klasy [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) i na koniec wywołaj metodę Save.

{{% blocks/products/pf/feature-page-code h3="C# - Konwersja PDF na obraz" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj Excel na Word i PowerPoint" %}}

Do konwersji formatów Microsoft Excel na różne pliki, w tym Word i PowerPoint, odpowiednie podrzędne interfejsy API związane z głównym interfejsem Aspose.Total dla .NET API. Proces konwersji plików Excela do dokumentu Word, załaduj plik EXCEL za pomocą klasy [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) i najpierw przekonwertuj EXCEL do PDF i ustaw SaveFormat na Auto. Następnie załaduj przekonwertowany plik PDF za pomocą klasy Document i wywołaj metodę Save i ustaw Doc, Docx jako SaveFormat. Kod jest również wymieniony dla konwersji Microsoft **Excel do Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - Konwersja JSON do Excela" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# - Konwersja Excel do JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}