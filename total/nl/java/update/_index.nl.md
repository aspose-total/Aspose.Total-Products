---
title: Werk Excel-bestanden bij met Java 

description: Bewerk Microsoft Excel XLSX-, XLS-, CSV-documenten zonder Microsoft Office te installeren binnen op Java gebaseerde applicaties.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update Excel-documenten via Java" h2="Wijzig Microsoft Excel XLSX- en XLS-bestanden binnen op Java gebaseerde applicaties zonder Microsoft Office<sup>&reg;</sup> te installeren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Het is gebruikelijk dat organisaties hun gegevens, opgeslagen in Excel-bestanden, zoals studentengegevens, patiëntendossiers en magazijnitems, enz. bijwerken via bedrijfssoftware. [Aspose.Total for Java](https://products.aspose.com/total/java/) API biedt de functionaliteit om de spreadsheets aan te passen met behulp van hun eigen software. Programmeurs kunnen de software verbeteren met de wijzigingsmogelijkheden door slechts enkele regels API-code te schrijven. De [Aspose.Cells for Java](https://products.aspose.com/cells/java/) API die deel uitmaakt van het [Aspose.Total for Java](https://products.aspose.com/total/java/)-pakket maakt dit wijzigingsproces eenvoudig. Hieronder vindt u het proces van het bijwerken van het Excel-document.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel-documenten bijwerken met Java" %}}

[Aspose.Cells for Java](https://products.aspose.com/cells/java/) API biedt [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)-klasse die het laden van Excel-spreadsheets afhandelt. Proces is eenvoudig. Maak het klasseobject Workbook door het bronbestand als parameter op te geven. Toegang tot het relevante werkblad en de relevante cel met behulp van de [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int))-methode. Gebruik de [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)-methode om de inhoud in de geopende cel te wijzigen en roep ten slotte de save()-methode aan om het document op te slaan.

{{% blocks/products/pf/feature-page-code h3="Java-code - Excel-documenten bijwerken" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Update">}}