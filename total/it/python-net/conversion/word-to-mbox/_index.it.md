---
title: Converti WORD in MBOX in Python
description: Salva WORD in MBOX all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti WORD in MBOX usando Python" h2="Conversione da WORD a MBOX nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da WORD a MBOX all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file WORD e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire WORD in MBOX in Python" %}}

- Aprire il file WORD di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file WORD viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il WORD viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da WORD a MBOX, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva WORD in MBOX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da Word a MBOX tramite le API Python converte il contenuto dei documenti in un formato di archivio mailbox utilizzato per memorizzare collezioni di messaggi email. Questo è utile quando i record di comunicazione basati su documenti o contenuti simili a messaggi devono essere confezionati per scenari di archiviazione, migrazione o gestione di posta in massa.

Da una prospettiva di automazione, questa conversione supporta flussi di lavoro di archiviazione e comunicazione scalabili trasformando i contenuti redatti in Word in risorse compatibili con mailbox che si adattano a processi di archiviazione, esportazione e trasferimento.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso principali" %}}

* **Preparazione archivio mailbox**
  Confeziona il contenuto dei messaggi derivato dai documenti in un formato adatto ai sistemi di archiviazione email.

* **Archiviazione di comunicazioni in massa**
  Supporta la conservazione di più messaggi generati in un file mailbox consolidato.

* **Supporto al flusso di lavoro di migrazione**
  Aiuta a preparare i contenuti per ambienti che utilizzano metodi di importazione o trasferimento basati su mailbox.

* **Preservazione dei record**
  Memorizza contenuti orientati alla comunicazione in un formato progettato per la gestione di messaggi raggruppati.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Pipeline di generazione archivio**
  Converte lotti di avvisi basati su Word in file MBOX per la conservazione a lungo termine.

* **Imballaggio di messaggi in massa**
  Automatizza la creazione di archivi mailbox da documenti di comunicazione standardizzati.

* **Flussi di lavoro di preparazione alla migrazione**
  Produce output MBOX per il trasferimento in sistemi di archiviazione o revisione della posta.

* **Automazione dell'archiviazione per conformità**
  Utilizza i file mailbox come contenitori strutturati per i record di comunicazione derivati da documenti.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}