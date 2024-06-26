---
title: Crea TSV in Python
description: Genera file TSV utilizzando applicazioni Python senza utilizzare Microsoft Office. 

family: total
platformtag: Python
feature: create
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Crea TSV usando Python" h2="Genera TSV tramite le tue applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore, chi sta cercando di creare file TSV tramite l'applicazione Python? L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) può aiutare ad automatizzare il processo di creazione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi file e immagini di Microsoft Office. L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) che fa parte del pacchetto [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) semplifica questo processo di generazione. Di seguito è riportato il processo di creazione. Inoltre, gli sviluppatori possono facilmente migliorare l'applicazione per la modifica del file TSV. Per aggiornare il file TSV utilizzando il processo Python è lo stesso, tranne per il fatto che richiede un file esistente come parametro durante la creazione dell'oggetto cartella di lavoro.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come creare file TSV in Python" %}}

- Crea un nuovo oggetto di classe [Workbook](https://reference.aspose.com/cells/python/asposecells.api/Workbook) con FileFormatType come parametro
- Ottieni l'accesso al [Worksheet](https://reference.aspose.com/cells/python/asposecells.api/Worksheet) richiesto utilizzando il metodo [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Inserire i dati nella cella a cui si accede utilizzando il metodo [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Salvare il documento come file .tsv utilizzando [save()](https://reference.aspose.com/cells/python/asposecells.api/workbook#save(java.lang.String)) passando il file con percorso come parametro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di creazione" %}}

- Per la generazione di TSV, fare riferimento alle API all'interno del progetto direttamente da PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Oppure usa il seguente comando pip ```pip install aspose.cells``` 
- Inoltre, Scarica il pacchetto API dalla sezione [downloads](https://releases.aspose.com/cells/python-java) 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Crea TSV in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}