---
title: Crea file usando Python 
url: /it/python-net/create/
description: Crea documenti di testo e Microsoft Word senza installare Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crea documenti usando Python" h2="Crea file di testo e Microsoft Word DOCX, DOC all'interno di applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
La memorizzazione dei dati è la base di qualsiasi applicazione software a seconda della natura dell'applicazione. Il percorso di archiviazione può essere il database, XML, JSON, file di testo, report di Excel o documenti di Microsoft Word. File I/O è la parte di qualsiasi lingua e principalmente le lingue, incluso Python, supportano la scrittura di dati su file di testo. Consideriamo il linguaggio Python. Scrivendo file di testo esistenti usando Python, fornisce il metodo di apertura, scrittura e chiusura per queste attività. Innanzitutto apri il file con il percorso del file pertinente e aggiungi o scrivi la funzione come argomenti. Quindi scrivi il testo richiesto nel file e infine chiudi il file usando il metodo close(). 

Per creare documenti Microsoft Word utilizzando Python, utilizziamo il pacchetto API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) che include l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) come parte del suo pacchetto. Questa API fornisce una soluzione completa di automazione dei documenti per fatture, report e articoli tecnici. Procedura di creazione del documento word elencata di seguito.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Come creare file di testo usando Python" %}}

Creare e scrivere su file di testo è semplice. Python fornisce il metodo open() con tre parametri e deve utilizzare uno dei parametri insieme al percorso del file. Tre parametri sono "x", "a" e "w". Fornendo "x", verrà creato un nuovo file ma genera un errore nel caso in cui il file esista già. Fornendo "a", verrà creato un nuovo file di testo se non esiste e, nel caso esista, il contenuto verrà aggiunto alla fine. E infine fornendo "w", il nuovo documento di testo verrà creato e sovrascritto con il nuovo contenuto nel caso in cui esista già.

{{% blocks/products/pf/feature-page-code h3="Python - Crea file di testo" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Crea documenti Microsoft Word" %}}

Total Python Word API ha molteplici funzionalità tra cui la creazione di file Microsoft Word, l'inserimento di immagini e testo all'interno dei documenti, l'aggiunta di tabelle ed elenchi all'interno dei file e la modifica di documenti esistenti con facilità. Per creare un processo di documento di Microsoft Word, creare l'oggetto delle classi [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) e [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). Aggiungi il testo, il paragrafo, gli elenchi e le tabelle richiesti all'interno del documento e infine salvalo.

{{% blocks/products/pf/feature-page-code h3="Python: crea documenti Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}