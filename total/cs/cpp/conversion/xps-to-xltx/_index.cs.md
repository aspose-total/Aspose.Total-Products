---
title: C++ API pro převod XPS do XLTX
description: Převeďte XPS na XLTX přes C++ API bez použití Microsoft Excel nebo Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: XLTX
otherformats: DIF ODS EXCEL SXC TXT XLSB MD FODS XLTM TSV CSV XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Vykreslování XPS do XLTX v aplikacích C++" h2="Převeďte XPS na XLTX v nativních aplikacích C++ bez nutnosti Microsoft<sup>&reg;</sup> Excel nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Převod XPS na XLTX v C++ prostřednictvím [Aspose.Total for C++](https://products.aspose.com/total/cpp/) knihoven pro automatizaci souborů je jednoduchý dvoukrokový proces. V prvním kroku můžete exportovat XPS do XLSX pomocí [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), poté pomocí [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) Spreadsheet Programming API, můžete převést XLSX na XLTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API pro převod XPS do XLTX" %}}
1. Otevřete soubor XPS pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Převeďte XPS na XLSX pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Načtěte dokument XLSX pomocí odkazu třídy [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Uložte dokument do formátu XLTX pomocí členské funkce [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo přes konzolu Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Získejte nebo nastavte informace o souboru XPS prostřednictvím C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) vám také umožňuje získat informace o vašem dokumentu XPS a umožňuje vám přijímat informovaná rozhodnutí před procesem převodu. Chcete-li získat konkrétní informace o souboru XPS, musíte nejprve zavolat metodu [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document). Jakmile je objekt DocumentInfo načten, můžete získat hodnoty jednotlivých vlastností. Kromě toho můžete také nastavit vlastnosti pomocí příslušných metod třídy DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Uložit formát souboru XLTX pro streamování přes C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) umožňuje uložit formát souboru XLTX pro streamování. Chcete-li uložit soubory do streamu, vytvořte objekt MemoryStream nebo FileStream a uložte soubor do tohoto objektu streamu voláním [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodu objektu [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349). Při volání metody Save zadejte požadovaný formát souboru pomocí výčtu [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xltx-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-dif/" name="XPS Na DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-ods/" name="XPS Na ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-excel/" name="XPS Na EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-sxc/" name="XPS Na SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-txt/" name="XPS Na TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xlsb/" name="XPS Na XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-md/" name="XPS Na MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-fods/" name="XPS Na FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xltm/" name="XPS Na XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-tsv/" name="XPS Na TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xltx/" name="XPS Na XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xps-to-xlsm/" name="XPS Na XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}