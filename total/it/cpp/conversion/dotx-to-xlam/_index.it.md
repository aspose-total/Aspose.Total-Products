---
title: Converti DOTX in XLAM in C++
description: API C++ per convertire DOTX in XLAM senza utilizzare Microsoft Word o Microsoft Excel
url: /it/cpp/conversion/dotx-to-xlam/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: XLAM
otherformats: XLSB XLTM XLTX DIF XLSX EXCEL SXC XLS TSV XLT ODS FODS XLSM CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire DOTX in XLAM" h2="Esporta DOTX in XLAM tramite C++ senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi includere facilmente la funzione di conversione da DOTX a XLAM nelle tue applicazioni C++. Utilizzando l'API di conversione e manipolazione dei dotxumenti ricca di funzionalità, potente e facile da usare [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare DOTX in HTML. Successivamente, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi convertire HTML in XLAM. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire DOTX in XLAM" %}}
1. Aprire il file DOTX utilizzando [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument) riferimento alla classe
2. Converti DOTX in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string_saveformat)
3. Caricare il dotxumento HTML utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salvare il dotxumento in formato XLAM utilizzando la funzione membro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accedi alle proprietà del dotxumento DOTX tramite C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente inoltre di accedere alle proprietà del dotxumento del file DOTX e di prendere una decisione informata prima del processo di conversione. Per accedere alle proprietà del dotxumento è possibile utilizzare [BuiltInDotxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_dotxument_properties) per ottenere proprietà integrate e [CustomDotxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_dotxument_properties) per ottenere proprietà personalizzate. Nell'esempio di codice seguente viene illustrato come enumerare tutte le proprietà predefinite e personalizzate in un dotxumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-dotxument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file XLAM in streaming tramite C++" %}}
Dopo aver convertito DOTX in XLAM, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) consente di salvare il dotxumento per lo streaming. Per salvare i file in un flusso, creare un oggetto MemoryStream o FileStream e salvare il file in tale oggetto flusso chiamando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) dell'oggetto. Specificare il formato file desiderato utilizzando l'enumerazione [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) quando si chiama [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xlsb/" name="DOTX Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xltm/" name="DOTX Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xltx/" name="DOTX Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-dif/" name="DOTX Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xlsx/" name="DOTX Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-excel/" name="DOTX Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-sxc/" name="DOTX Per SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xls/" name="DOTX Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-tsv/" name="DOTX Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xlt/" name="DOTX Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-ods/" name="DOTX Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-fods/" name="DOTX Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xlsm/" name="DOTX Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/dotx-to-xlam/" name="DOTX Per XLAM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}