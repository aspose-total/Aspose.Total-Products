---
title: Converti PPTM in CSV usando Python
description: Conversione da PPTM a CSV nelle tue applicazioni Python senza utilizzare Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPTM
outformat: CSV
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti PPTM in CSV tramite Python" h2="Conversione da PPTM a CSV nelle tue applicazioni Python senza installare Microsoft PowerPoint<sup>&reg;</sup> o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzionalità di conversione da PPTM a CSV all'interno dell'applicazione. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono diversi formati, inclusi file PPTM e CSV.

È principalmente in due fasi. Innanzitutto usa l'API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) per convertire il file PPTM in HTML. Successivamente, utilizzando l'API Python di Excel [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), salva l'HTML creato nel formato Microsoft Excel desiderato. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire PPTM in CSV in Python" %}}
- **Passo 1** Utilizzare l'istanza della classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) per aprire il file PPTM di origine 
- Salva il file PPTM in HTML utilizzando il metodo [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) fornendo il nome del file e il percorso della directory desiderato
-  **Passo 2** Carica il file HTML con un'istanza della classe Workbook
-  Chiama il metodo `save` mentre specifichi il percorso del file CSV di output. Quindi il tuo file PPTM viene convertito in CSV nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da PPTM a CSV, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) e [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Oppure usa i seguenti comandi pip ```pip install aspose.slides``` e ```pip install aspose-cells-python```
-  Inoltre, SO basato su Microsoft Windows o Linux (vedi di più per [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva PPTM in HTML in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva HTML in CSV in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}