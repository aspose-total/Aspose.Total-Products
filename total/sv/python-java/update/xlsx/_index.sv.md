---
title: Uppdatera XLSX-fil med Python
description: Ändra XLSX-dokument i Python-applikationer utan att använda Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Uppdatera XLSX-fil via Python" h2="Ändra XLSX-kalkylblad via dina Python-applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

För en utvecklare, vem försöker uppdatera XLSX-filer via Python-applikationen? [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API kan hjälpa till att automatisera uppdateringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format inklusive Microsoft Excel-filer. ASPOSE.CELL API som är en del av [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-paketet gör denna modifieringsprocessen enkel. Nedan följer processen för att uppdatera XLSX-dokumentet.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man uppdaterar XLSX-fil i Python" %}}

- Skapa nytt [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook)-klassobjekt med käll-XLSX-filen som parameter
- Tillgång till relevant arbetsblad med [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)-metoden
- Infoga nya data i den öppnade cellen med [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)-metoden
- Spara filen som .xlsx-fil med metoden save() genom att skicka filen med sökvägen som parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ändringskrav" %}}

- För XLSX-modifiering, referera API:er inom projektet direkt från PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Eller använd följande pip-kommando ```pip install aspose.cells``` 
- Dessutom ladda ner API-paketet från [Nedladdningar](https://releases.aspose.comcells/python-java)-sektionen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - Uppdatera XLSX-fil i Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}