---
title: Werk Excel-bestanden bij met Python 

description: Bewerk Microsoft Excel XLSX-, XLS-, CSV-documenten zonder Microsoft Office te installeren binnen Python-toepassingen
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Werk Excel-documenten bij via Python" h2="Wijzig Microsoft Excel XLSX-, XLS-bestanden binnen Python Applications zonder Microsoft Office<sup>&reg;</sup> te installeren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Het is gebruikelijk dat organisaties hun gegevens bijwerken, opgeslagen in Excel-bestanden, zoals studentengegevens, patiëntendossiers en magazijnitems, enz. via bedrijfssoftware. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API biedt de functionaliteit van het wijzigen van de spreadsheets via de software. Programmeurs kunnen de software verbeteren met de wijzigingsmogelijkheden door de API te integreren en een paar regels code te schrijven. De [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API die deel uitmaakt van het [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-pakket maakt dit wijzigingsproces eenvoudig. Hieronder vindt u het proces van het bijwerken van het Excel-document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Werk Excel-documenten bij met Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API biedt Workbook-klasse die het laden van Excel-spreadsheets afhandelt. Proces is eenvoudig. Maak het klasseobject [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) door het bronbestand als parameter op te geven. Gebruik de [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)-methode om toegang te krijgen tot het relevante werkblad door de index op te geven. roep de [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)-methode aan om de inhoud in de geopende cel te wijzigen en roep tenslotte de save()-methode aan om het document op te slaan.

{{% blocks/products/pf/feature-page-code h3="Python - Update Excel-documenten" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Update">}}