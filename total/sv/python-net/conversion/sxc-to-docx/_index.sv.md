---
title: Konvertera SXC till DOCX med Python
description: SXC till DOCX-konvertering i dina Python-applikationer utan att använda Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: SXC
outformat: DOCX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera SXC till DOCX via Python" h2="SXC till DOCX-konvertering i dina Python-applikationer utan att installera Microsoft Excel<sup>&reg;</sup> eller Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

För en Python-utvecklare som försöker lägga till en SXC till DOCX-konverteringsfunktion i applikationen. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API kan hjälpa till att automatisera konverteringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format inklusive SXC- och DOCX-filer.

Det är främst i två steg. Använd först [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) API för att konvertera SXC-fil till HTML. Efter det genom att använda Word Python API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), spara den skapade HTML-koden i önskat Microsoft Word-format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Hur man konverterar SXC till DOCX i Python" %}}
- **Steg 1** Öppna käll-SXC-filen med Workbook-klassen
- Spara SXC-fil till HTML genom att använda save(file, SaveFormat.HTML)-metoden genom att ange filnamnet och önskad katalogsökväg
-  **Steg 2** Ladda HTML-fil med en instans av [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)-klassen
-  Anropa "spara"-metoden medan du anger sökvägen till DOCX-filen. Så din SXC-fil konverteras till DOCX på den angivna sökvägen

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

- För SXC till DOCX-konvertering krävs Python 3.5 eller senare
- Referera till API:er inom projektet direkt från PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) och [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Eller använd följande pip-kommandon ```pip install aspose-cells-python``` och ```pip install aspose.words```
-  Dessutom, Microsoft Windows eller Linux-baserade operativsystem (se mer för [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) och [Words](https://docs.aspose.com/words/python-net/system-requirements/)) och för Linux kontrollera ytterligare krav för gcc och libpython och följ [steg för steg instruktioner](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Spara SXC till HTML i Python - Steg 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Spara HTML till DOCX i Python - Steg 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}