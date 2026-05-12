---
title: Converti PDF in MBOX in Python
description: Salva PDF in MBOX all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: PDF
outformat: MBOX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti PDF in MBOX usando Python" h2="Conversione da PDF a MBOX nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da PDF a MBOX all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file PDF e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato MBOX.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire PDF in MBOX in Python" %}}

- Aprire il file PDF di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file PDF viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il PDF viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da PDF a MBOX, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva PDF in MBOX in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da PDF a MBOX usando le API Python consente di trasformare il contenuto PDF in un formato di archivio mailbox utilizzato per memorizzare collezioni di messaggi email. Questo è utile quando le informazioni dei documenti devono essere incorporate nei flussi di lavoro di archiviazione email o preservate in repository di messaggi di massa.

L'automazione di questa conversione supporta operazioni di archiviazione scalabili, processi di migrazione e archiviazione strutturata delle comunicazioni. Riduce lo sforzo manuale consentendo ai documenti PDF di essere preparati programmaticamente per sistemi che si basano su formati di dati mailbox consolidati.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso chiave" %}}

* **Creazione di archivio mailbox**  
  Converti il contenuto PDF in record compatibili MBOX per scopi di archiviazione e conservazione.

* **Imballaggio di comunicazioni di massa**  
  Organizza i messaggi derivati da documenti in collezioni mailbox per la portabilità del sistema.

* **Integrazione di archivi email**  
  Utilizza gli output convertiti in ambienti che gestiscono dati tramite contenitori MBOX.

* **Preservazione dei record**  
  Preserva le informazioni basate su PDF all'interno dei flussi di lavoro di archiviazione dei messaggi.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Generazione di archivi batch**  
  I flussi di lavoro Python possono elaborare molti PDF in output compatibili MBOX automaticamente.

* **Pipeline di conservazione per conformità**  
  Il contenuto convertito può essere inserito nei repository di archiviazione per la conservazione a lungo termine.

* **Preparazione alla migrazione**  
  I sistemi possono impacchettare il contenuto derivato da PDF per il trasferimento su piattaforme basate su mailbox.

* **Aggiornamenti automatizzati del repository**  
  I documenti PDF in ingresso possono essere continuamente convertiti e aggiunti ai flussi di lavoro di archiviazione.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}