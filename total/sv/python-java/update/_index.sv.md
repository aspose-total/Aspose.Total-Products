---
title: Uppdatera Excel-filer med Python 

description: Redigera Microsoft Excel XLSX, XLS, CSV-dokument utan att installera Microsoft Office i Python-applikationer
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Uppdatera Excel-dokument via Python" h2="Ändra Microsoft Excel XLSX, XLS-filer i Python-applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Det är vanligt att organisationen uppdaterar sin data, lagrad i excel-filer som studentdata, patientjournaler och lagerföremålslista etc. via företagets programvara. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API tillhandahåller funktionen att modifiera kalkylbladen via programvaran. Programmerare kan förbättra programvaran med modifieringsmöjligheterna genom att integrera API:t och skriva några rader kod. [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API som är en del av [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-paketet gör denna modifieringsprocessen enkel. Nedan följer processen för att uppdatera Excel-dokumentet.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Uppdatera Excel-dokument med Python" %}}

[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API tillhandahåller Workbook-klass som hanterar laddningen av Excel-kalkylblad. Processen är enkel. Skapa klassobjektet [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) genom att tillhandahålla källfilen som parameter. Använd [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)-metoden för att komma åt det relevanta arbetsbladet genom att tillhandahålla dess index. anropa [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)-metoden för att ändra innehållet i den öppnade cellen och slutligen anropa metoden save() för att spara dokumentet.

{{% blocks/products/pf/feature-page-code h3="Python - Uppdatera Excel-dokument" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Uppdatering">}}