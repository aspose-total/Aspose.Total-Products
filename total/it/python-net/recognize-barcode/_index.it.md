---
title: Riconoscere codici a barre di diverse simbologie utilizzando Python 

description: Scansiona immagini di codici a barre 1D, 2D e postali di varie simbologie tra cui 128 e QR in Python utilizzando poche righe di codice 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Riconosci il codice a barre tramite Python" h2="Leggi codici a barre 1D, 2D e postali inclusi Code 128, UPC-A, ISBN, EAN-8, EAN-13, EAN-14 e altro all'interno delle applicazioni Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

I barocdi sono la necessità di varie aziende così come i software che gestiscono tali attività. L'API [Aspose.BarCode for Python via .NET](https://products.aspose.com/barcode/python-net/) che fa parte del pacchetto API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/), fornisce diverse funzionalità per soddisfare tali esigenze aziendali. L'API è in grado di leggere codici a barre da immagini di qualsiasi qualità e da qualsiasi angolazione. Inoltre, può decodificare caratteri non inglesi nei tipi 2D. La procedura di lettura del codice a barre è semplice ed è elencata di seguito.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Come riconoscere il codice a barre usando Python" %}}

Per la lettura e la scansione di codici a barre di qualsiasi simbologia, l'API fornisce la classe BarCodeReader che accetta i tipi di decodifica come parametro o utilizza il generico DecodeType.AllSupportedTypes che gestisce tutti i tipi. Chiama il metodo read_bar_codes() per leggere tutto il testo del codice a barre. Passa in rassegna tutti i caratteri del codice scansionato. Infine esegui qualsiasi processo pertinente come stamparlo per ottenere il codice o abbinarlo ai codici memorizzati all'interno del database.

{{% blocks/products/pf/feature-page-code h3="Python: riconosce il codice a barre" %}}

{{< gist "aspose-com-gists" "aa209a7128678a76c7b3de938b8613aa" "recognize-barcode-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Riconoscere">}}