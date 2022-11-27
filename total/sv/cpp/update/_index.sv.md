---
title: Uppdatera Excel-filer med C++ 

description: Redigera Microsoft Excel XLSX, XLS, CSV-dokument utan att installera Microsoft Office med C++-baserade applikationer.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Uppdatera Excel-dokument via C++" h2="Ändra Microsoft Excel XLSX, XLS-filer i C++-baserade applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Det är vanligt att organisationen uppdaterar sina data, lagrade i excel-filer som studentdata, patientjournaler och lagerföremålslista etc via företagets programvara. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API tillhandahåller funktionen för att modifiera kalkylbladen med hjälp av programvaran. Programmerare kan förbättra programvaran med modifieringsmöjligheterna genom att bara skriva några rader API-kod. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API som är en del av [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-paketet gör denna modifieringsprocessen enkel. Nedan följer processen för att uppdatera Excel-dokumentet.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Uppdatera Excel-dokument med C++" %}}

Använd [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API, ladda källdokumentet med [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Få åtkomst till [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) med GetIWorksheets()->GetObjectByIndex(0) och önskad cell med GetICells()->GetObjectByIndex. Genom att använda PutValue-metoden, ändra innehållet i den öppnade cellen. Anropa slutligen metoden save() för att spara dokumentet.

{{% blocks/products/pf/feature-page-code h3="C++-kod - Uppdatera Excel-dokument" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Uppdatering">}}