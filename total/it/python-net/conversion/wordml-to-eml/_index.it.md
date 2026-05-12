---
title: Converti WORDML in EML in Python
description: Salva WORDML in EML all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: WORDML
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti WORDML in EML usando Python" h2="Conversione da WORDML a EML nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da WORDML a EML all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file WORDML e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire WORDML in EML in Python" %}}

- Aprire il file WORDML di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file WORDML viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il WORDML viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da WORDML a EML, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva WORDML in EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da WordML a EML converte il contenuto del documento in un formato di file di messaggio email standard che può essere archiviato, trasferito o aperto in client di posta compatibili. Questo è utile per l'archiviazione, la generazione di email e l'automazione dei flussi di lavoro basati sui messaggi.

Le API Python supportano la conversione da WordML a EML mappando programmaticamente il testo del documento in strutture email, consentendo una trasformazione scalabile dei contenuti per sistemi di archiviazione e messaggistica.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso principali" %}}

* **Generazione di file email**
  Converte il contenuto del documento in file EML portatili per l'archiviazione e lo scambio di messaggi.

* **Flussi di lavoro di archiviazione**
  Preserva le comunicazioni derivanti dal documento in un formato di file email standard.

* **Compatibilità del client**
  Supporta i flussi di lavoro email che dipendono da standard di file di messaggio ampiamente riconosciuti.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Creazione automatizzata di file messaggio**
  Genera output EML da documenti WordML in processi di conversione batch.

* **Archiviazione per conformità**
  Memorizza le comunicazioni derivanti dal documento come file EML per flussi di lavoro di conservazione e audit.

* **Pipeline di distribuzione dei contenuti**
  Alimenta i file email convertiti nei sistemi di gestione, archiviazione o revisione della posta.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}