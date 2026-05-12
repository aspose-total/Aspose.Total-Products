---
title: Converti DOC in MBOX in Python
description: Salva DOC in MBOX all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti DOC in MBOX usando Python" h2="Conversione da DOC a MBOX nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da DOC a MBOX all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file DOC e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire DOC in MBOX in Python" %}}

- Aprire il file DOC di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file DOC viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il DOC viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da DOC a MBOX, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva DOC in MBOX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da documento a MBOX trasforma il contenuto di Word in un formato di archivio compatibile con le caselle di posta, consentendo di raggruppare output in stile messaggio per l'archiviazione o la migrazione. È utile quando il contenuto del documento deve essere preservato o consegnato in flussi di lavoro di archiviazione email.

Con le API Python, la conversione da DOC a MBOX può essere automatizzata per operazioni di archiviazione su larga scala, migliorando la ripetibilità e supportando i sistemi che lavorano con contenitori basati su caselle di posta.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso principali" %}}

* **Creazione archivio di posta**
  Converti i messaggi derivati da documenti in MBOX per una memorizzazione raggruppata in stile email.

* **Preparazione della migrazione**
  Usa l'output MBOX quando i documenti devono entrare in flussi di lavoro di archiviazione o trasferimento della posta.

* **Preservazione della comunicazione**
  Archivia il contenuto del documento convertito in un formato consolidato e compatibile con le caselle di posta.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Automazione del confezionamento dell'archivio**
  Genera automaticamente output MBOX dal contenuto DOC per conformità o migrazione.

* **Conversione batch di contenitori di posta**
  Converte più documenti in archivi di posta con il minimo sforzo manuale.

* **Collegamento del flusso di lavoro documento‑a‑mail**
  Prepara programmaticamente contenuti basati su documenti per ecosistemi di archiviazione email.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}