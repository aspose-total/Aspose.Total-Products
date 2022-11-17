---
title: Convertir XLT en WORD avec C++
description: Convertir XLT en WORD dans les applications C++

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOC
otherformats: POWERPOINT DOCX PPTX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir XLT en WORD via C++" h2="Exporter Excel® XLT vers WORD dans des applications C++ entièrement fonctionnelles" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversion XLT en WORD sur C++" %}}
1. Ouvrez le fichier XLT à l'aide de la fonction membre [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) référence de classe
2. Convertissez XLT en PDF et définissez SaveFormat sur Pdf
3. Chargez le fichier PDF converti à l'aide de la référence de classe [Wordument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument)
4. Enregistrez le wordument au format WORD à l'aide de la fonction membre [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.wordument#a6383c010776212483f51cc41235924db) et définissez Word comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Wordument class reference
auto word = MakeObject<Wordument>(u"pdfOutput.pdf");
// save wordument in WORD format
word->Save(u"convertedFile.word", SaveFormat::Word);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xlt-to-powerpoint/" name="XLT À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xlt-to-wordx/" name="XLT À WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xlt-to-pptx/" name="XLT À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/xlt-to-word/" name="XLT À WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}