---
title: Konvertera CSV till bild med Python
description: CSV till bild TIFF BMP PNG JPEG GIF EMF SVG-konvertering i dina Python-applikationer utan att använda Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: CSV
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera CSV till bild via Python" h2="CSV till JPG, TIFF, BMP, PNG, GIF-bildkonvertering i dina Python-applikationer utan att installera Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

För en Python-utvecklare som försöker lägga till en CSV-till PNG-, BMP-, TIFF-, JPEG- och GIF-bildkonverteringsfunktion i applikationen. Som ibland krävs det att bädda in Excel-kalkylblad i webb- eller skrivbordsapplikationer. I sådana fall är export av kalkylblad till bilder den enda lösningen. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API kan hjälpa till att exportera Excel-filer till bilder samt att automatisera konverteringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format inklusive Microsoft Excel-format via dess underordnade [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) API. För närvarande stöder Python Excel till Image Converter API konvertering av Excel-filer till EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM och Office-kompatibla EMF eller kontrollera [Format](https://docs.aspose.com/cells/python-java/supported-file-formats/) som stöds. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar CSV till bilder i Python" %}}

- Skapa [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook)-klassobjekt för att ladda CSV-fil
- Använd [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions)-klassen och ange de alternativ som är relevanta för utdatabilden
- Få tillgång till kalkylbladet för konvertering med [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))-metoden
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Spara alla sidor i kalkylbladet som en bild med [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String))-metoden. Nu konverteras CSV-filen till bilder på den angivna sökvägen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

- För konvertering av CSV till bilder (JPG, PNG, GIF, BMP, TIFF), referera till API:er inom projektet direkt från PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Eller använd följande pip-kommando ```pip install aspose.cells``` 
- Dessutom ladda ner API-paketet från [Nedladdningar](https://releases.aspose.comcells/python-java)-sektionen 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="CSV till bildkonvertering via Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}