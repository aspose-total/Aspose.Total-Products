---
title: Převeďte XLSM na WORD pomocí C++
description: Převeďte XLSM na WORD v aplikacích C++
url: /cs/cpp/conversion/xlsm-to-word/
family: total
platformtag: cpp
feature: conversion
informat: XLSM
outformat: DOC
otherformats: POWERPOINT PPTX DOC DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XLSM na WORD přes C++" h2="Export Excel<sup>&reg;</sup> XLSM do WORD v rámci plně funkčních aplikací C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převod XLSM na WORD v C++" %}}
1. Otevřete soubor XLSM pomocí členské funkce [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) odkaz na třídu
2. Převeďte XLSM na PDF a nastavte SaveFormat na Pdf
3. Načtěte převedený soubor PDF pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Uložte dokument do formátu WORD pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) a nastavte Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsm");
// save XLSM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xlsm-to-powerpoint/" name="XLSM Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xlsm-to-pptx/" name="XLSM Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xlsm-to-word/" name="XLSM Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xlsm-to-wordx/" name="XLSM Na WORDX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}