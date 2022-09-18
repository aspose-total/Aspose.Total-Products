---
title: Converti POTM in RTF in Python
description: Conversione da POTM a RTF nelle tue applicazioni Python senza utilizzare Microsoft Word o PowerPoint 
url: /it/python-net/conversion/potm-to-rtf/
family: total
platformtag: Python
feature: conversion
informat: POTM
outformat: RTF
otherformats: Word DOC DOT DOCX DOCM DOTX DOTM RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti POTM in RTF usando Python" h2="Conversione da POTM a RTF nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da POTM a RTF all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi. Così **Come convertire POTM in RTF in Python?**

È principalmente in due passaggi. Innanzitutto usa l'API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) per convertire il file POTM in PDF. Successivamente, utilizzando l'API Python di Microsoft Word [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), salva il PDF creato in Microsoft Word come formato RTF. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti POTM in RTF in Python" %}}
-  **Passo 1** Carica il file PDF con un'istanza della classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat.PDF come parametri. Quindi il tuo file POTM viene convertito in PDF nel percorso specificato.
- **Passo 2** Apri il file PDF utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Salva il file PDF in un file RTF utilizzando il metodo [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) fornendo il nome del file e il percorso della directory desiderata.
- Ecco un altro frammento di codice per la presentazione di PowerPoint in Word (Microsoft Powerpoint to Word)[https://products.aspose.com/total/python-net/conversion/] Conversion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da POTM a RTF, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) e [Aspose.Words](https://pypi.org/project/aspose-words/)) o
- Utilizzare i seguenti comandi pip ```pip install aspose.slides``` e ```pip install aspose.words```. Inoltre,
- Sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) e [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva POTM in PDF in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-slides-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva PDF in RTF in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-files-to-microsoft-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}