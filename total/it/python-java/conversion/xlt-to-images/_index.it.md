---
title: Converti XLT in Immagine usando Python
description: Conversione da XLT a TIFF immagine BMP PNG JPEG GIF EMF SVG nelle applicazioni Python senza utilizzare Microsoft Excel 

family: total
platformtag: Python
feature: conversion
informat: XLT
outformat: Image
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti XLT in immagine tramite Python" h2="Conversione di immagini da XLT a JPG, TIFF, BMP, PNG, GIF nelle tue applicazioni Python senza installare Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Per uno sviluppatore Python, che sta cercando di aggiungere una funzione di conversione di immagini XLT a PNG, BMP, TIFF, JPEG e GIF all'interno dell'applicazione. Come a volte è necessario incorporare fogli di calcolo Excel nelle applicazioni Web o desktop. In questi casi l'esportazione di fogli di calcolo in immagini è l'unica anima. L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) può aiutare a esportare file Excel in immagini e ad automatizzare il processo di conversione. È un pacchetto completo di varie API che gestiscono formati diversi, inclusi i formati Microsoft Excel tramite l'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) figlia. Attualmente Python Excel to Image Converter API supporta la conversione di file Excel in EMF, WMF, JPEG, PNG, BMP, GIF, TIFF, SVG, GLTF, PICT, SVM ed EMF compatibile con Office o controlla il [Formati](https://docs.aspose.com/cells/python-java/supported-file-formats/) supportato. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Come convertire XLT in immagini in Python" %}}

- Crea un oggetto classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) per caricare il file XLT
- Utilizzare la classe [ImageOrPrintOptions](https://reference.aspose.com/cells/python-java/asposecells.api/ImageOrPrintOptions) e specificare le opzioni relative all'immagine di output
- Ottieni l'accesso al foglio di lavoro per la conversione utilizzando il metodo [Workbook.getWorksheets().get(index)](https://reference.aspose.com//cells/python-java/asposecells.api/worksheetcollection#Item%20(int))
- Create the instance of [SheetRender](https://reference.aspose.com/cells/python/asposecells.api/SheetRender) class object and initialize it with Worksheet and ImageOrPrintOptions objects
- Salva tutte le pagine del foglio di lavoro come immagine utilizzando il metodo [SheetRender.toImage(pageIndex, fileName)](https://reference.aspose.com//cells/python-java/asposecells.api/sheetrender#toImage(int,%20java.lang.String)). Ora il file XLT viene convertito in Immagini nel percorso specificato

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}

- Per la conversione da XLT a immagini (JPG, PNG, GIF, BMP, TIFF), fare riferimento alle API all'interno del progetto direttamente da PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Oppure usa il seguente comando pip ```pip install aspose.cells``` 
- Inoltre, Scarica il pacchetto API dalla sezione [Download](https://releases.aspose.com/cells/python-java) 
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Conversione da XLT a immagini tramite Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "5d33fa768a61d24704a7350432266781" "convert-excel-to-image.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}