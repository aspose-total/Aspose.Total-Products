---
title: API C++ per convertire PCL in XLAM
description: Converti PCL in XLAM tramite API C++ senza utilizzare Microsoft Excel o Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: XLAM
otherformats: ODS XLTX XLSM XLTM XLSB EXCEL SXC TXT DIF TSV XLT CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendering da PCL a XLAM nelle applicazioni C++" h2="Converti PCL in XLAM in applicazioni C++ native senza richiedere Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
La conversione di PCL in XLAM in C++ tramite [Aspose.Total for C++](https://products.aspose.com/total/cpp/) librerie di automazione dei formati di file è un semplice processo in due fasi. Nel primo passaggio, puoi esportare PCL in XLSX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), quindi usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API di programmazione per fogli di calcolo, puoi convertire XLSX in XLAM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire PCL in XLAM" %}}
1. Aprire il file PCL utilizzando il riferimento alla classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converti PCL in XLSX utilizzando la funzione membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Caricare il documento XLSX utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salvare il documento in formato XLAM utilizzando la funzione membro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ottieni o imposta le informazioni sul file PCL tramite C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) consente inoltre di ottenere informazioni sul documento PCL e di prendere decisioni informate prima del processo di conversione. Per ottenere informazioni specifiche sul file di un file PCL, devi prima chiamare il metodo [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) di Classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document). Una volta recuperato l'oggetto DocumentInfo, è possibile ottenere i valori delle singole proprietà. Inoltre, puoi anche impostare le proprietà usando i rispettivi metodi della classe DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva il formato file XLAM in streaming tramite C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) consente di salvare il formato di file XLAM per lo streaming. Per salvare i file in un flusso, creare un oggetto MemoryStream o FileStream e salvare il file in tale oggetto flusso chiamando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) dell'oggetto. Specificare il formato file desiderato utilizzando l'enumerazione [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) quando si chiama il metodo Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-xlam-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-ods/" name="PCL Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xltx/" name="PCL Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xlsm/" name="PCL Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xltm/" name="PCL Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xlsb/" name="PCL Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-excel/" name="PCL Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-sxc/" name="PCL Per SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-txt/" name="PCL Per TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-dif/" name="PCL Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-tsv/" name="PCL Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xlt/" name="PCL Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/pcl-to-xlam/" name="PCL Per XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}