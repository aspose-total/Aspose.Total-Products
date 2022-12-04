---
title: Converti DOC in XLAM usando Python
description: Conversione da DOC a XLAM nelle tue applicazioni Python senza utilizzare Microsoft Word o Excel 

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: XLAM
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti DOC in XLAM tramite Python" h2="Conversione da DOC a XLAM nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzionalità di conversione da DOC a XLAM all'interno dell'applicazione. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che trattano diversi formati.

È principalmente in due fasi. Innanzitutto usa l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) per convertire il file DOC in HTML. Successivamente, utilizzando l'API Python di Excel [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), salva l'HTML creato nel formato Microsoft Excel desiderato. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire DOC in XLAM in Python" %}}
- **Passaggio 1** Apri il file DOC di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Salva il file DOC in HTML utilizzando il metodo [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) fornendo il nome del file e il percorso della directory desiderato
-  **Passaggio 2** Carica il file HTML con un'istanza della classe Workbook con file e LoadOptions come parametri
-  Chiama il metodo `save` mentre specifichi il percorso del file XLAM di output. Quindi il tuo file DOC viene convertito in XLAM nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da DOC a XLAM, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Oppure usa i seguenti comandi pip ```pip install aspose.words``` e ```pip install aspose-cells-python``` 
-  Inoltre, i sistemi operativi basati su Microsoft Windows o Linux (vedere di più per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) e per Linux controllano i requisiti aggiuntivi per gcc e libpython e seguono [istruzioni passo passo](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva DOC in HTML in Python - Passaggio 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Salva HTML in XLAM in Python - Passaggio 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}