---
title: Converti RTF in POWERPOINT in Python
description: Conversione da RTF a POWERPOINT nelle tue applicazioni Python senza utilizzare Microsoft Word o PowerPoint 
url: /it/python-net/conversion/rtf-to-powerpoint/
family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: POWERPOINT
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti RTF in POWERPOINT usando Python" h2="Conversione da RTF a POWERPOINT nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da RTF a POWERPOINT all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi. Così **Come convertire RTF in POWERPOINT in Python?**

È principalmente in due passaggi. Per prima cosa usa l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) per convertire il file RTF in PDF. Successivamente, utilizzando l'API Python di PowerPoint [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), salva il PDF creato in Presentazione come formato POWERPOINT. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti RTF in POWERPOINT in Python" %}}
- **Passo 1** Aprire il file RTF di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Salva il file RTF in PDF utilizzando il metodo [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) fornendo il nome del file e il percorso della directory desiderata.
-  **Passo 2** Carica il file PDF con un'istanza della classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.POWERPOINT come parametri. Quindi il tuo file RTF viene convertito in POWERPOINT nel percorso specificato.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da RTF a POWERPOINT, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) e [Aspose.Words](https://pypi.org/project/aspose-words/)) o
- Utilizzare i seguenti comandi pip ```pip install aspose.slides``` e ```pip install aspose.words```. Inoltre,
- Sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) e [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva RTF in PDF in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva PDF in POWERPOINT in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}