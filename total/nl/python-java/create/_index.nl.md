---
title: Microsoft Excel-bestanden maken en bijwerken met Python 
url: /nl/python-java/create/
description: Maak Microsoft Excel-werkbladrapporten zonder Microsoft Office te installeren 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Excel-rapporten maken met Python" h2="Creëer en update Microsoft Excel SpreadSheets XLS-, XLSX-documenten binnen Python-toepassingen zonder Microsoft Office<sup>&reg;</sup> te installeren." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) is een Python-API voor het maken, lezen en schrijven van documenten in Microsoft Excel-indelingen, waaronder XLS en XLSX. Deze API maakt deel uit van het [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-pakket. Bovendien kan Develpors eenvoudig code schrijven voor het invoegen van gegevens, afbeeldingen, grafieken, draaitabellen in werkbladen en vele andere functionaliteiten. Python API ondersteunt ook functies zoals het instellen van verschillende [formules](https://docs.aspose.com/cells/python-java/supported-formula-functions/), tekst converteren naar kolommen, slimme markeringen en dynamische formule-opties. Hieronder staan enkele voorbeeldcodes om spreadsheets te maken en aan te passen.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Excel-bestanden maken met Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API biedt Workbook-klasse die het maken van bestanden afhandelt. Proces is eenvoudig. Maak het klasseobject Werkmap en open het relevante werkblad door de index op te geven. Gebruik de methode putValue om de inhoud in de geopende cel toe te voegen en roep ten slotte de methode save() op om het document met een specifieke naam op te slaan.

{{% blocks/products/pf/feature-page-code h3="Code 1 - Eenvoudig Excel-bestand maken" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Code 2 - Afbeeldingen invoegen in Microsoft Excel-documenten" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Excel-bestanden bijwerken met Python" %}}

Het proces van het maken en bijwerken van het Excel-bestand is bijna hetzelfde, behalve het enige verschil. Het verschil is dat tijdens het aanmaakproces een leeg werkmap-object wordt gemaakt, terwijl er tijdens het updateproces een bestaand Excel-bestand nodig is. Geef het bestaande bestand dus als parameter door aan de Workbook-klasse. Rust de procedure is hetzelfde

{{% blocks/products/pf/feature-page-code h3="Code 3 - Update Microsoft Excel-documenten" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}