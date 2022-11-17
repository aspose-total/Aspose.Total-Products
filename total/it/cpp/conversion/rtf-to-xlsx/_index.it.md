---
title: Converti RTF in XLSX in C++
description: API C++ per convertire RTF in XLSX senza utilizzare Microsoft Word o Microsoft Excel

family: total
platformtag: cpp
feature: conversion
informat: RTF
outformat: XLSX
otherformats: TSV XLTX EXCEL SXC XLS ODS CSV XLTM XLT XLSB DIF XLSM FODS XLAM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire RTF in XLSX" h2="Esporta RTF in XLSX tramite C++ senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi includere facilmente la funzione di conversione da RTF a XLSX nelle tue applicazioni C++. Utilizzando l'API di conversione e manipolazione dei rtfumenti ricca di funzionalità, potente e facile da usare [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare RTF in HTML. Successivamente, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi convertire HTML in XLSX. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire RTF in XLSX" %}}
1. Aprire il file RTF utilizzando [Rtfument](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument) riferimento alla classe
2. Converti RTF in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.rtfument#save_string_saveformat)
3. Caricare il rtfumento HTML utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salvare il rtfumento in formato XLSX utilizzando la funzione membro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accedi alle proprietà del rtfumento RTF tramite C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente inoltre di accedere alle proprietà del rtfumento del file RTF e di prendere una decisione informata prima del processo di conversione. Per accedere alle proprietà del rtfumento è possibile utilizzare [BuiltInRtfumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_rtfument_properties) per ottenere proprietà integrate e [CustomRtfumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_rtfument_properties) per ottenere proprietà personalizzate. Nell'esempio di codice seguente viene illustrato come enumerare tutte le proprietà predefinite e personalizzate in un rtfumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-rtfument-properties.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file XLSX in streaming tramite C++" %}}
Dopo aver convertito RTF in XLSX, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) consente di salvare il rtfumento per lo streaming. Per salvare i file in un flusso, creare un oggetto MemoryStream o FileStream e salvare il file in tale oggetto flusso chiamando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) dell'oggetto. Specificare il formato file desiderato utilizzando l'enumerazione [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) quando si chiama [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-tsv/" name="RTF Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xltx/" name="RTF Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-excel/" name="RTF Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-sxc/" name="RTF Per SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xls/" name="RTF Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-ods/" name="RTF Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xlsx/" name="RTF Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xltm/" name="RTF Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xlt/" name="RTF Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xlsb/" name="RTF Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-dif/" name="RTF Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xlsm/" name="RTF Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-fods/" name="RTF Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/rtf-to-xlam/" name="RTF Per XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}