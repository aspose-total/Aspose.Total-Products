---
title: Uppdatera CSV-fil med C++
description: Ändra CSV-dokument i C++-program utan att använda Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Uppdatera CSV-fil via C++" h2="Ändra CSV-kalkylblad via dina C++-baserade applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

För en programmerare som försöker uppdatera CSV-filer i C++-applikationen, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API kan hjälpa till att automatisera uppdateringsprocessen. Det är ett komplett paket med olika C++-bibliotek som hanterar flera format inklusive Microsoft Excel-dokument. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API som är en del av [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-paketet gör denna modifieringsprocessen enkel. Processen att uppdatera CSV-dokumentet är enkel genom att först komma åt arket och sedan uppdatera cellvärdet i excel med C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man uppdaterar CSV-fil i C++" %}}

- Ladda CSV-filen med [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Tillgång till relevant [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) med GetIWorksheets()->GetObjectByIndex(0) och relevant cell med GetICells()->GetObjectByIndex
- Infoga nya data i den öppnade cellen med PutValue-metoden
- Spara filen som .csv-fil med hjälp av metoden Spara genom att skicka filen med sökvägen som parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Ändringskrav" %}}

- För CSV-modifiering, följ [Systemkrav](https://docs.aspose.com/cells/cpp/system-requirements/) för Windows- och Linux-system 
- Installera från kommandoraden som ```nuget install Aspose.Total.Cpp```
- Eller via Package Manager-konsolen i Visual Studio med ```Install-Package Aspose.Total.Cpp```
- Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [Nedladdningar](https://downloads.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Kod - Uppdatera CSV-fil i C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andra modifieringsalternativ" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xls/" name="Uppdatering XLS Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xlsx/" name="Uppdatering XLSX Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/csv/" name="Uppdatering CSV Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xlsb/" name="Uppdatering XLSB Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xlsm/" name="Ändra XLSM Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xlt/" name="Uppdatering XLT Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xltx/" name="Uppdatering XLTX Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/xltm/" name="Uppdatering XLTM Fil" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/sv/cpp/update/tsv/" name="Uppdatering TSV Fil" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}