---
title: Aggiorna il file TSV usando Python
description: Modifica il documento TSV nelle applicazioni Python senza utilizzare Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aggiorna il file TSV tramite Python" h2="Modifica i fogli di calcolo TSV tramite le tue applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore, chi sta cercando di aggiornare i file TSV tramite l'applicazione Python? L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) può aiutare ad automatizzare il processo di aggiornamento. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi i file Microsoft Excel. L'API ASPOSE.CELL che fa parte del pacchetto [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) semplifica questo processo di modifica. Di seguito è riportato il processo di aggiornamento del documento TSV.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come aggiornare il file TSV in Python" %}}

- Crea un nuovo oggetto di classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) con il file TSV di origine come parametro
- Accesso al relativo foglio di lavoro tramite il metodo [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Inserire nuovi dati nella cella a cui si accede utilizzando il metodo [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Salva il file come file .tsv usando il metodo save() passando il file con percorso come parametro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di modifica" %}}

- Per la modifica TSV, fare riferimento alle API all'interno del progetto direttamente da PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Oppure usa il seguente comando pip ```pip install aspose.cells``` 
- Inoltre, Scarica il pacchetto API dalla sezione [Download](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Codice - Aggiorna il file TSV in Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}