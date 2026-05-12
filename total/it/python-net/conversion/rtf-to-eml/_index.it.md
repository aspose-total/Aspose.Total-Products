---
title: Converti RTF in EML in Python
description: Salva RTF in EML all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: RTF
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti RTF in EML usando Python" h2="Conversione da RTF a EML nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da RTF a EML all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file RTF e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire RTF in EML in Python" %}}

- Aprire il file RTF di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file RTF viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il RTF viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da RTF a EML, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva RTF in EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da RTF a EML trasforma i documenti di testo formattato in file di messaggi email standard che possono essere archiviati, condivisi, importati o conservati su sistemi di posta compatibili. Questo è utile quando il contenuto del documento deve diventare un artefatto email portatile con struttura di messaggio.

Per l'automazione, RTF a EML consente la generazione di email basata su documenti, l'archiviazione dei messaggi e flussi di comunicazione ripetibili in cui sono richiesti file email strutturati per lo scambio o la conservazione a lungo termine.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso principali" %}}

* **Creazione di email portabili**  
  Converte il contenuto del documento in file email autonomi per la condivisione o l'importazione.

* **Archiviazione delle comunicazioni**  
  Supporta la conservazione dei messaggi basati su documento in un formato email riconosciuto.

* **Standardizzazione del flusso di lavoro dei messaggi**  
  Aiuta i team a generare output email coerenti a partire da contenuti RTF preparati.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Generazione automatica di file messaggio**  
  I sistemi possono convertire i documenti RTF in file EML come parte dei flussi di comunicazione.

* **Preparazione dell'archivio email**  
  Processi batch possono trasformare il contenuto testuale in file messaggio per flussi di conservazione e conformità.

* **Scambio di messaggi multipiattaforma**  
  La conversione programmatica aiuta a spostare le comunicazioni basate su documento negli ecosistemi email senza ricreazione manuale.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}