---
title: Converti DOCX in EML in Python
description: Salva DOCX in EML all'interno delle applicazioni Python senza utilizzare Microsoft Word o Outlook

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: EML
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti DOCX in EML usando Python" h2="Conversione da DOCX a EML nelle tue applicazioni Python senza installare Microsoft Word<sup>&reg;</sup> o Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, chi sta cercando di aggiungere una funzione di conversione da DOCX a EML all'interno dell'applicazione? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) può aiutare ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi e-mail, immagini e formati Microsoft Word. Le API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) e [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) che fanno parte del pacchetto [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) semplificano questa conversione utilizzando Python. È un processo in due fasi, in primo luogo caricare il file DOCX e renderlo in HTML tramite [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/). In secondo luogo, carica l'HTML convertito utilizzando [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) e salvalo in formato EML.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire DOCX in EML in Python" %}}

- Aprire il file DOCX di origine utilizzando la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Chiama il metodo `save` mentre specifichi il percorso del file HTML di output e le relative opzioni di salvataggio HTML come parametro. Quindi il tuo file DOCX viene convertito in HTML nel percorso specificato
- Ora carica il file HTML salvato usando MailMessage.load
- Chiama il metodo di salvataggio con il percorso del file pertinente. Quindi alla fine il DOCX viene convertito

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da DOCX a EML, è richiesto Python 3.5 o successivo
- API di riferimento all'interno del progetto direttamente da PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) e [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Oppure usa il seguente comando pip ```pip install aspose.words``` e ```pip install Aspose.Email-for-Python-via-NET``` 
- Inoltre, il sistema operativo basato su Microsoft Windows o Linux (vedi altro per [Words](https://docs.aspose.com/words/python-net/system-requirements/) e [Email](https://docs.aspose.com/email/python-net/system-requirements/)) e per Linux controlla i requisiti aggiuntivi per gcc e libpython e segui passo passo le istruzioni [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Salva DOCX in EML in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

La conversione da DOCX a EML consente la trasformazione del contenuto dei documenti in un formato di file email standard utilizzato da molti client e sistemi di posta elettronica. Questo processo permette di includere testo, formattazione e allegati derivati da file DOCX all'interno di un file di messaggio email.

Con le API Python, la conversione da DOCX a EML può essere automatizzata nei sistemi di distribuzione dei documenti, nei flussi di lavoro di archiviazione e nelle piattaforme di messaggistica. Questo supporta pipeline di comunicazione scalabili in cui i documenti devono essere consegnati o archiviati come messaggi email.

{{% blocks/products/pf/agp/feature-section-col title="Casi d'uso principali" %}}

* **Creazione di messaggi email da documenti**  
  Converte i file DOCX in messaggi EML adatti ai client e ai server di posta elettronica.

* **Archiviazione dei documenti come email**  
  Memorizza il contenuto dei documenti come messaggi email per la conservazione dei registri e la conformità.

* **Sistemi di comunicazione automatizzati**  
  Consente di incorporare direttamente il contenuto dei documenti nei messaggi email.

* **Pipeline di distribuzione dei contenuti**  
  Facilita l'invio di informazioni basate su documenti attraverso i sistemi di posta elettronica.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Scenari di automazione" %}}

* **Generazione automatica di file email**  
  I sistemi possono generare automaticamente file EML da documenti DOCX.

* **Creazione batch di contenuti email**  
  Gli script Python possono elaborare più file DOCX e convertirli nel formato EML.

* **Flussi di lavoro di messaggistica aziendale**  
  Il contenuto dei documenti può essere trasformato in file di messaggi email per pipeline di comunicazione automatizzate.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}