---
title: XLS-bestand bijwerken met C++
description: Wijzig het XLS-document in C++-toepassingen zonder Microsoft Excel te gebruiken.
family: total
platformtag: C++
feature: update
informat: XLS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XLS-bestand bijwerken via C++" h2="Wijzig XLS-spreadsheets via uw op C++ gebaseerde applicaties zonder Microsoft Office te installeren<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Voor een programmeur die XLS-bestanden binnen de C++-toepassing probeert bij te werken, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API kan helpen om het updateproces te automatiseren. Het is een volledig pakket van verschillende C++-bibliotheken die meerdere formaten aankunnen, waaronder Microsoft Excel-documenten. De [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API die deel uitmaakt van het [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-pakket maakt dit wijzigingsproces eenvoudig. Het bijwerken van het XLS-document is eenvoudig door eerst het blad te openen en vervolgens de celwaarde in Excel bij te werken met C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hoe XLS-bestand in C++ te updaten" %}}

- Laad het XLS-bestand met behulp van [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Toegang tot relevante [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) met behulp van GetIWorksheets()->GetObjectByIndex(0) en relevante cel met behulp van GetICells()->GetObjectByIndex
- Voeg nieuwe gegevens in de geopende cel in met behulp van de PutValue-methode
- Sla het bestand op als .xls-bestand met behulp van de methode Opslaan door het bestand met het pad als parameter door te geven

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wijzigingsvereisten" %}}

- Voor XLS-modificatie, volgens [systeem vereisten](https://docs.aspose.com/cells/cpp/system-requirements/) voor Windows- en Linux-systemen 
- Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total.Cpp```
- Of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```
- U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand van [Downloaden](https://releases.aspose.com/cells/cpp) downloaden

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - XLS-bestand bijwerken in C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}