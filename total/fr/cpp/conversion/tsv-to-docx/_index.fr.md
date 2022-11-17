---
title: Convertir TSV en DOCX avec C++
description: Convertir TSV en DOCX dans les applications C++

family: total
platformtag: cpp
feature: conversion
informat: TSV
outformat: DOCX
otherformats: WORD POWERPOINT DOC PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir TSV en DOCX via C++" h2="Exporter Excel® TSV vers DOCX dans des applications C++ entièrement fonctionnelles" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversion TSV en DOCX sur C++" %}}
1. Ouvrez le fichier TSV à l'aide de la fonction membre [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) référence de classe
2. Convertissez TSV en PDF et définissez SaveFormat sur Pdf
3. Chargez le fichier PDF converti à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Enregistrez le document au format DOCX à l'aide de la fonction membre [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) et définissez Docx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total.Cpp```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.tsv");
// save TSV as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tsv-to-word/" name="TSV À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tsv-to-powerpoint/" name="TSV À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tsv-to-docx/" name="TSV À DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/cpp/conversion/tsv-to-pptx/" name="TSV À PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}