---
title: Converti WORD in MHTML in Python
description: Formato di archivio Web da WORD a mhtml e conversione di file HtmlFixed nelle tue applicazioni Python senza utilizzare Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti WORD in MHTML usando Python" h2="Conversione da WORD a MHTML, HtmlFixed e HTML nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzione di conversione da WORD a MHTML (formato archivio Web) o HtmlFixed significa voler salvare il documento in formato HTML utilizzando elementi posizionati in modo assoluto all'interno dell'applicazione. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi. 

Utilizziamo l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) che fa parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) per aggiungere la funzione di conversione da WORD a MHTML. Nel caso in cui il file WORD sia semplice, sono solo due righe di codice. Carica il file WORD e chiama il metodo di salvataggio con il percorso del file appropriato insieme all'enumerazione SaveFormat come MHTML o HTML_FIXED. Ma nel caso in cui sia necessario ripristinare il modello del documento il più vicino a quello originale, è necessario salvare alcune informazioni aggiuntive all'interno del documento risultante chiamate informazioni di andata e ritorno.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come Converti WORD in MHTML in Python" %}}
- Carica il file WORD di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Crea l'istanza di [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Imposta export_roundtrip_information su True
- Specificare [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) come MHTML
- Chiama il metodo `save` mentre specifichi il percorso del file di output e SaveFormat come parametri. Quindi il tuo file WORD viene convertito in MHTML nel percorso specificato.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione del formato da WORD a MHTML o HtmlFixed, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Oppure usa i seguenti comandi pip ```pip install aspose.words```
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva WORD in MHTML in Python - Semplice" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Conversione da WORD a MHTML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}