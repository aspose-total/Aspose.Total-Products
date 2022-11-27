---
title: Werk Excel-bestanden bij met C++ 

description: Bewerk Microsoft Excel XLSX-, XLS-, CSV-documenten zonder Microsoft Office te installeren met op C++ gebaseerde applicaties.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Werk Excel-documenten bij via C++" h2="Wijzig Microsoft Excel XLSX- en XLS-bestanden in op C++ gebaseerde applicaties zonder Microsoft Office<sup>&reg;</sup> te installeren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Het is gebruikelijk dat organisaties hun gegevens, opgeslagen in Excel-bestanden, zoals studentengegevens, patiëntendossiers en magazijnitems, enz. bijwerken via bedrijfssoftware. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API biedt de functionaliteit van het wijzigen van de spreadsheets met behulp van de software. Programmeurs kunnen de software verbeteren met de wijzigingsmogelijkheden door slechts enkele regels API-code te schrijven. De [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API die deel uitmaakt van het [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-pakket maakt dit wijzigingsproces eenvoudig. Hieronder vindt u het proces van het bijwerken van het Excel-document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Werk Excel-documenten bij met C++" %}}

Gebruik de [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API om het brondocument te laden met [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Toegang tot de [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) met behulp van GetIWorksheets()->GetObjectByIndex(0) en de vereiste cel met behulp van GetICells()->GetObjectByIndex. Wijzig de inhoud in de geopende cel door de PutValue-methode te gebruiken. Roep ten slotte de methode save() aan om het document op te slaan.

{{% blocks/products/pf/feature-page-code h3="C++ Code - Excel-documenten bijwerken" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Update">}}