---
title: C++ API pro převod EPUB do XLTM
description: Převeďte EPUB na XLTM přes C++ API bez použití Microsoft Excel nebo Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: XLTM
otherformats: CSV SXC MD FODS XLAM DIF TSV XLT XLTX TXT ODS XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslování EPUB do XLTM v aplikacích C++" h2="Převeďte EPUB na XLTM v nativních aplikacích C++ bez nutnosti Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Převod EPUB na XLTM v C++ prostřednictvím [Aspose.Total for C++](https://products.aspose.com/total/cpp/) knihoven pro automatizaci souborů je jednoduchý dvoukrokový proces. V prvním kroku můžete exportovat EPUB do XLSX pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), poté pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) Spreadsheet Programming API, můžete převést XLSX na XLTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod EPUB do XLTM" %}}
1. Otevřete soubor EPUB pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte EPUB na XLSX pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Načtěte dokument XLSX pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu XLTM pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte nebo nastavte informace o souboru EPUB prostřednictvím C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) vám také umožňuje získat informace o vašem dokumentu EPUB a umožňuje vám přijímat informovaná rozhodnutí před procesem převodu. Chcete-li získat konkrétní informace o souboru EPUB, musíte nejprve zavolat metodu [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document). Jakmile je objekt DocumentInfo načten, můžete získat hodnoty jednotlivých vlastností. Kromě toho můžete také nastavit vlastnosti pomocí příslušných metod třídy DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit formát souboru XLTM pro streamování přes C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) umožňuje uložit formát souboru XLTM pro streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Při volání metody Save zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltm-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}