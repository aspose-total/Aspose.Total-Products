---
title: Převeďte SXC na POWERPOINT pomocí C++
description: Převeďte SXC na POWERPOINT v aplikacích C++
url: /cs/cpp/conversion/sxc-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: DOCX WORD PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Převést SXC na POWERPOINT přes C++" h2="Export Excel<sup>&reg;</sup> SXC do POWERPOINT v rámci plně funkčních aplikací C++" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Převod SXC na POWERPOINT v C++" %}}
1. Otevřete soubor SXC pomocí členské funkce [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) odkaz na třídu
2. Převeďte SXC na PDF a nastavte SaveFormat na Pdf
3. Načtěte převedený soubor PDF pomocí odkazu třídy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Uložte dokument do formátu POWERPOINT pomocí členské funkce [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) a nastavte Powerpoint jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total.Cpp``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total.Cpp```.

Případně si můžete stáhnout offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the SXC file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.sxc");
// save SXC as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/sxc-to-powerpointx/" name="SXC Na POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/sxc-to-word/" name="SXC Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/sxc-to-pptx/" name="SXC Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/cpp/conversion/sxc-to-powerpoint/" name="SXC Na POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}