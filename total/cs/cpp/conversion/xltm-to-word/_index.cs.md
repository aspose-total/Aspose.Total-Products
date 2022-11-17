---
title: Převeďte XLTM na WORD pomocí C++
description: Převeďte XLTM na WORD v aplikacích C++

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOC
otherformats: PPTX POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést XLTM na WORD přes C++" h2="Export Excel<sup>&reg;</sup> XLTM do WORD v rámci plně funkčních aplikací C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převod XLTM na WORD v C++" %}}
1. Otevřete soubor XLTM pomocí členské funkce [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) odkaz na třídu
2. Převeďte XLTM na PDF a nastavte SaveFormat na Pdf
3. Načtěte převedený soubor PDF pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Uložte dokument do formátu WORD pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) a nastavte Word jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xltm-to-pptx/" name="XLTM Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xltm-to-powerpoint/" name="XLTM Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xltm-to-wordx/" name="XLTM Na WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/xltm-to-word/" name="XLTM Na WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}