---
title: Konvertera ODT till PPSM i Python
description: ODT till PPSM-konvertering i dina Python-applikationer utan att använda Microsoft Word eller PowerPoint 
url: /sv/python-net/conversion/odt-to-ppsm/
family: total
platformtag: Python
feature: conversion
informat: ODT
outformat: PPSM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertera ODT till PPSM med Python" h2="ODT till PPSM-konvertering i dina Python-applikationer utan att installera Microsoft Word<sup>&reg;</sup> eller PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

För en Python-utvecklare, vem försöker lägga till en ODT till PPSM-konverteringsfunktion i applikationen? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API kan hjälpa till att automatisera konverteringsprocessen. Det är ett komplett paket med olika API:er som hanterar olika format. Så **Hur konverterar man ODT till PPSM i Python?**

Det är främst i två steg. Använd först [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API för att konvertera ODT-fil till PDF. Efter det genom att använda PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), spara den skapade PDF-filen i Presentation som ett PPSM-format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Konvertera ODT till PPSM i Python" %}}
- **Steg 1** Öppna käll-ODT-filen med [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)-klassen
- Spara ODT-fil till PDF genom att använda metoden [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) genom att ange filnamnet och önskad katalogsökväg.
-  **Steg 2** Ladda PDF-fil med en instans av klassen [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Anropa 'spara'-metoden samtidigt som du anger sökvägen för utdatafilen & SaveFormat.PPSM som parametrar. Så din ODT-fil konverteras till PPSM på den angivna sökvägen.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}

- För ODT till PPSM-konvertering krävs Python 3.5 eller senare
- Referera API:er inom projektet direkt från PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) och [Aspose.Words](https://pypi.org/project/aspose-words/)) eller
- Använd följande pip-kommandon ```pip install aspose.slides``` och ```pip install aspose.words```. Dessutom,
- Microsoft Windows eller Linux-baserade operativsystem (se mer för [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) och [Words](https://docs.aspose.com/words/python-net/system-requirements/)) och för Linux kontrollera ytterligare krav för gcc och libpython och följ steg-för-steg-instruktionerna [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Spara ODT till PDF i Python - Steg 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Spara PDF till PPSM i Python - Steg 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}