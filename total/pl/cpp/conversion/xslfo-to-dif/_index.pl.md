---
title: C++ API do konwersji XSLFO na DIF
description: Konwertuj XSLFO na DIF za pomocą C++ API bez użycia Microsoft Excel lub Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: XSLFO
outformat: DIF
otherformats: XLT MD XLTM ODS EXCEL XLSM XLTX SXC TXT TSV XLAM XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj XSLFO do DIF w aplikacjach C++" h2="Konwertuj XSLFO na DIF w natywnych aplikacjach C++ bez konieczności używania programu Microsoft<sup>&reg;</sup> Excel lub Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Konwertowanie XSLFO na DIF w C++ za pomocą bibliotek automatyzacji formatu plików [Aspose.Total for C++](https://products.aspose.com/total/cpp/) to prosty, dwuetapowy proces. W pierwszym kroku możesz wyeksportować XSLFO do XLSX za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), a następnie za pomocą [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API do programowania arkuszy kalkulacyjnych, możesz przekonwertować XLSX na DIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do konwersji XSLFO na DIF" %}}
1. Otwórz plik XSLFO, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj XSLFO na XLSX za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Załaduj dokument XLSX, używając odwołania do klasy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Zapisz dokument w formacie DIF za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Pobierz lub ustaw informacje o pliku XSLFO za pomocą C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) umożliwia również uzyskanie informacji o dokumencie XSLFO i podejmowanie świadomych decyzji przed procesem konwersji. Aby uzyskać informacje o pliku XSLFO, musisz najpierw wywołać metodę [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) Klasa [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document). Po pobraniu obiektu DocumentInfo można uzyskać wartości poszczególnych właściwości. Ponadto możesz również ustawić właściwości za pomocą odpowiednich metod klasy DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Zapisz format pliku DIF w strumieniu za pomocą C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) umożliwia zapisywanie formatu pliku DIF do przesyłania strumieniowego. Aby zapisać pliki w strumieniu, utwórz obiekt MemoryStream lub FileStream i zapisz plik w tym obiekcie strumienia, wywołując [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metoda obiektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Określ żądany format pliku przy użyciu wyliczenia [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) podczas wywoływania metody Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-dif-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}