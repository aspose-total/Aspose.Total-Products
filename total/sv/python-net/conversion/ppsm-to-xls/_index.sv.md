---
title: Konvertera PPSM till XLS med Python
description: PPSM till XLS-konvertering i dina Python-applikationer utan att använda Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPSM
outformat: XLS
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera PPSM till XLS via Python" h2="PPSM till XLS-konvertering i dina Python-applikationer utan att installera Microsoft PowerPoint<sup>&reg;</sup> eller Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

För en Python-utvecklare som försöker lägga till en PPSM till XLS-konverteringsfunktion i applikationen. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API kan hjälpa till att automatisera konverteringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format inklusive PPSM- och XLS-filer.

Det är främst i två steg. Använd först [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) API för att konvertera PPSM-fil till HTML. Efter det genom att använda Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), spara den skapade HTML-koden i önskat Microsoft Excel-format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar PPSM till XLS i Python" %}}
- **Steg 1** Använd klassinstansen [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) för att öppna PPSM-källfilen 
- Spara PPSM-fil till HTML genom att använda [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)-metoden genom att ange filnamnet och önskad katalogsökväg
-  **Steg 2** Ladda HTML-fil med en instans av Workbook-klassen
-  Anropa "spara"-metoden medan du anger sökvägen till XLS-filen. Så din PPSM-fil konverteras till XLS på den angivna sökvägen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

- För PPSM till XLS-konvertering krävs Python 3.5 eller senare
- Referera till API:er inom projektet direkt från PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) och [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Eller använd följande pip-kommandon ```pip install aspose.slides``` och ```pip install aspose-cells-python```
-  Dessutom Microsoft Windows- eller Linux-baserade operativsystem (se mer för [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) och [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Spara PPSM till HTML i Python - Steg 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Spara HTML till XLS i Python - Steg 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}