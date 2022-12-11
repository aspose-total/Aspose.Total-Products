---
title: Converti XLSX in MOBI usando Python
description: Conversione da XLSX a MOBI nelle tue applicazioni Python senza utilizzare Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: XLSX
outformat: MOBI
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti XLSX in MOBI tramite Python" h2="Conversione da XLSX a MOBI nelle tue applicazioni Python senza installare Microsoft Excel<sup>&reg;</sup> o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzionalità di conversione da XLSX a MOBI all'interno dell'applicazione. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono diversi formati, inclusi file XLSX e MOBI.

È principalmente in due fasi. Innanzitutto usa l'API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) per convertire il file XLSX in HTML. Successivamente, utilizzando l'API Python di Word [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), salva l'HTML creato nel formato Microsoft Word desiderato. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire XLSX in MOBI in Python" %}}
- **Passo 1** Apri il file XLSX di origine utilizzando la classe Workbook
- Salva il file XLSX in HTML utilizzando il metodo save(file, SaveFormat.HTML) fornendo il nome del file e il percorso della directory desiderato
-  **Passo 2** Carica il file HTML con un'istanza della classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Chiama il metodo `save` mentre specifichi il percorso del file MOBI di output. Quindi il tuo file XLSX viene convertito in MOBI nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da XLSX a MOBI, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) e [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Oppure usa i seguenti comandi pip ```pip install aspose-cells-python``` e ```pip install aspose.words```
-  Inoltre, i sistemi operativi basati su Microsoft Windows o Linux (vedere di più per [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) e [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e per Linux controllano i requisiti aggiuntivi per gcc e libpython e seguono [istruzioni passo passo](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva XLSX in HTML in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva HTML in MOBI in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}