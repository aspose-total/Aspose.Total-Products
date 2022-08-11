---
title: Converti DOCX in ODS in C++
description: API C++ per convertire DOCX in ODS senza utilizzare Microsoft Word o Microsoft Excel
url: /it/cpp/conversion/docx-to-ods/
family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: ODS
otherformats: XLSX XLTX XLAM DIF XLSM XLT XLSB FODS SXC EXCEL XLS XLTM TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ per convertire DOCX in ODS" h2="Esporta DOCX in ODS tramite C++ senza utilizzare Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi includere facilmente la funzione di conversione da DOCX a ODS nelle tue applicazioni C++. Utilizzando l'API di conversione e manipolazione dei docxumenti ricca di funzionalità, potente e facile da usare [Aspose.Words per C++](https://products.aspose.com/words/cpp/), puoi esportare DOCX in HTML. Successivamente, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi convertire HTML in ODS. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ per convertire DOCX in ODS" %}}
1. Aprire il file DOCX utilizzando [Docxument](https://reference.aspose.com/words/cpp/class/aspose.words.docxument) riferimento alla classe
2. Converti DOCX in HTML utilizzando la funzione membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.docxument#save_string_saveformat)
3. Caricare il docxumento HTML utilizzando il riferimento alla classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Salvare il docxumento in formato ODS utilizzando la funzione membro [Salva](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total.Cpp``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Accedi alle proprietà del docxumento DOCX tramite C++" %}}
[Aspose.Words for C++](https://products.aspose.com/words/cpp/) consente inoltre di accedere alle proprietà del docxumento del file DOCX e di prendere una decisione informata prima del processo di conversione. Per accedere alle proprietà del docxumento è possibile utilizzare [BuiltInDocxumentProperties](https://reference.aspose.com/words/cpp/class/aspose.words.properties.built_in_docxument_properties) per ottenere proprietà integrate e [CustomDocxumentProperties](https:// reference.aspose.com/words/cpp/class/aspose.words.properties.custom_docxument_properties) per ottenere proprietà personalizzate. Nell'esempio di codice seguente viene illustrato come enumerare tutte le proprietà predefinite e personalizzate in un docxumento.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "get-word-docxument-properties.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Salva file ODS in streaming tramite C++" %}}
Dopo aver convertito DOCX in ODS, [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) consente di salvare il docxumento per lo streaming. Per salvare i file in un flusso, creare un oggetto MemoryStream o FileStream e salvare il file in tale oggetto flusso chiamando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) metodo [Salva](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) dell'oggetto. Specificare il formato file desiderato utilizzando l'enumerazione [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) quando si chiama [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349).
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "save-excel-to-stream.cpp" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xlsx/" name="DOCX Per XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xltx/" name="DOCX Per XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xlam/" name="DOCX Per XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-dif/" name="DOCX Per DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xlsm/" name="DOCX Per XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xlt/" name="DOCX Per XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xlsb/" name="DOCX Per XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-fods/" name="DOCX Per FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-sxc/" name="DOCX Per SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-excel/" name="DOCX Per EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xls/" name="DOCX Per XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-xltm/" name="DOCX Per XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-tsv/" name="DOCX Per TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/it/cpp/conversion/docx-to-ods/" name="DOCX Per ODS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}