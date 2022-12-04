---
title: Konvertera DOC till XLS med Python
description: DOC till XLS-konvertering i dina Python-applikationer utan att använda Microsoft Word eller Excel 

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: XLS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera DOC till XLS via Python" h2="DOC till XLS-konvertering i dina Python-applikationer utan att installera Microsoft Word<sup>&reg;</sup> eller Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

För en Python-utvecklare som försöker lägga till en DOC till XLS-konverteringsfunktion i applikationen. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API kan hjälpa till att automatisera konverteringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format.

Det är främst i två steg. Använd först [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API för att konvertera DOC-fil till HTML. Efter det, genom att använda Excel Python API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), spara den skapade HTML-koden i önskat Microsoft Excel-format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar DOC till XLS i Python" %}}
- **Steg 1** Öppna DOC-källfilen med [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)-klassen
- Spara DOC-fil till HTML genom att använda [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/)-metoden genom att ange filnamnet och önskad katalogsökväg
-  **Steg 2** Ladda HTML-fil med en instans av Workbook-klassen med fil och LoadOptions som parametrar
-  Anropa "spara"-metoden medan du anger sökvägen till XLS-filen. Så din DOC-fil konverteras till XLS på den angivna sökvägen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

- För DOC till XLS-konvertering krävs Python 3.5 eller senare
- Referera API:er inom projektet direkt från PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) och [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Eller använd följande pip-kommandon ```pip install aspose.words``` och ```pip install aspose-cells-python``` 
-  Dessutom, Microsoft Windows eller Linux-baserade operativsystem (se mer för [Words](https://docs.aspose.com/words/python-net/system-requirements/) och [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) och för Linux kontrollera ytterligare krav för gcc och libpython och följ [steg för steg instruktioner](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Spara DOC till HTML i Python - Steg 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Spara HTML till XLS i Python - Steg 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}