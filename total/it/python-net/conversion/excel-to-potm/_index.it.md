---
title: Converti EXCEL in POTM usando Python
description: Conversione da EXCEL a POTM nelle tue applicazioni Python senza utilizzare Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti EXCEL in POTM tramite Python" h2="Conversione da EXCEL a POTM nelle tue applicazioni Python senza installare Microsoft Excel<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzionalità di conversione da EXCEL a POTM all'interno dell'applicazione, L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono diversi formati, inclusi file EXCEL e POTM.

È principalmente in due fasi. Innanzitutto usa l'API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) per convertire il file EXCEL in PDF. Successivamente, utilizzando l'API Python di PowerPoint [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), salva il PDF creato nel formato Microsoft PowerPoint desiderato. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire EXCEL in POTM in Python" %}}
- **Passo 1** Utilizzare l'istanza della classe Workbook per aprire il file EXCEL di origine 
- Salva il file EXCEL in PDF utilizzando il metodo save fornendo il nome del file e il percorso della directory desiderato
-  **Passo 2** Carica il file PDF utilizzando la classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Chiama il metodo [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) mentre specifichi il percorso del file POTM di output. Quindi il tuo file EXCEL viene convertito in POTM nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da EXCEL a POTM, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) e [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Oppure usa i seguenti comandi pip ```pip install aspose-cells-python``` e ```pip install aspose.slides```
-  Inoltre, SO basato su Microsoft Windows o Linux (vedi di più per [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva EXCEL in PDF in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva PDF in POTM in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}