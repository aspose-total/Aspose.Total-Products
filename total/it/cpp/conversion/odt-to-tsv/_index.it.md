---
title: Converti ODT in TSV in C++
description: API C++ per convertire ODT in TSV senza utilizzare Microsoft Word o Microsoft Excel
url: /it/cpp/conversion/odt-to-tsv/
family: total
platformtag: cpp
feature: conversion
informat: ODT
outformat: TSV
otherformats: XLSX XLS ODS DIF XLAM XLTX XLSB EXCEL XLT XLSM CSV XLTM FODS SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire ODT in TSV" h2="Esporta ODT in TSV tramite C++ senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi includere facilmente la funzione di conversione da ODT a TSV nelle tue applicazioni C++. Utilizzando l'API di conversione e manipolazione dei odtumenti ricca di funzionalità, potente e facile da usare [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puoi esportare ODT in HTML. Successivamente, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi convertire HTML in TSV. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire ODT in TSV" %}}
1. Aprire il file ODT utilizzando [Odtument](https://reference.aspose.com/words/cpp/class/aspose.words.odtument) riferimento alla classe
2. Converti ODT in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string_saveformat)
3. Caricare il odtumento HTML utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salvare il odtumento in formato TSV utilizzando la funzione membro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accedi alle proprietà del odtumento ODT tramite C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente inoltre di accedere alle proprietà del odtumento del file ODT e di prendere una decisione informata prima del processo di conversione. Per accedere alle proprietà del odtumento è possibile utilizzare [BuiltInOdtumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_odtument_properties) per ottenere proprietà integrate e [CustomOdtumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_odtument_properties) per ottenere proprietà personalizzate. Nell'esempio di codice seguente viene illustrato come enumerare tutte le proprietà predefinite e personalizzate in un odtumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-odtument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file TSV in streaming tramite C++" %}}
Dopo aver convertito ODT in TSV, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) consente di salvare il odtumento per lo streaming. Per salvare i file in un flusso, creare un oggetto MemoryStream o FileStream e salvare il file in tale oggetto flusso chiamando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) dell'oggetto. Specificare il formato file desiderato utilizzando l'enumerazione [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) quando si chiama [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xlsx/" name="ODT Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xls/" name="ODT Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-ods/" name="ODT Per ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-dif/" name="ODT Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xlam/" name="ODT Per XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xltx/" name="ODT Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xlsb/" name="ODT Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-excel/" name="ODT Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xlt/" name="ODT Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xlsm/" name="ODT Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-tsv/" name="ODT Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-xltm/" name="ODT Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-fods/" name="ODT Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/odt-to-sxc/" name="ODT Per SXC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}