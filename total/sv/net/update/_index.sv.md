---
title: Uppdatera Excel-filer med .NET 

description: Redigera Microsoft Excel XLSX, XLS, CSV-dokument utan att installera Microsoft Office med C# .NET-baserade applikationer.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Uppdatera Excel-dokument via .NET" h2="Ändra Microsoft Excel XLSX, XLS-filer i .NET-baserade applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Det är vanligt att organisationen uppdaterar sina data, lagrade i excel-filer som studentdata, patientjournaler och lagerföremålslista etc via företagets programvara. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API tillhandahåller funktionen för att modifiera kalkylbladen med hjälp av programvaran. Programmerare kan förbättra programvaran med modifieringsmöjligheterna genom att bara skriva några rader API-kod. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API som är en del av [Aspose.Total for .NET](https://products.aspose.com/total/net/)-paketet gör denna modifieringsprocessen enkel. Nedan följer processen för att uppdatera Excel-dokumentet.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Uppdatera Excel-dokument med .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API tillhandahåller Workbook-klass som hanterar laddningen av Excel-kalkylblad. Processen är enkel. Skapa [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/)-objektet genom att tillhandahålla källfilen som parameter. Få tillgång till det relevanta arbetsbladet genom att tillhandahålla dess index med [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/)-metoden. Använd [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/)-metoden för att ändra innehållet i den öppnade cellen och anrop till sist metoden save() för att spara dokumentet.

{{% blocks/products/pf/feature-page-code h3=".NET-kod - Uppdatera Excel-dokument" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Uppdatering">}}