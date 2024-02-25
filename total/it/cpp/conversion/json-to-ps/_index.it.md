---
title: Converti il formato JSON in PS tramite C++
description: API C++ t0 Analizza JSON in PS senza utilizzare Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PS
otherformats: FLATOPC DOTX WORD OTT DOT ODT CHM DOCM DOC EPUB WORDML RTF PCL MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti il formato JSON in PS tramite C++" h2="Analizza da JSON a PS all'interno di applicazioni C++ senza utilizzare Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for C++](https://products.aspose.com/total/cpp/) puoi analizzare JSON in PS all'interno delle tue applicazioni C++ in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi esportare JSON in PDF. Successivamente, utilizzando [Aspose.Words for C++](https://products.aspose.com/words/cppp/), puoi convertire PDF in PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in PS in C++" %}}
1. Crea un nuovo oggetto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e leggi dati JSON validi dal file
2. Salva JSON come PDF utilizzando il metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Caricare il documento PDF utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salvare il documento in formato PS utilizzando il metodo [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta layout e converti formato JSON in PS in C++" %}}
Durante l'analisi da JSON a PS, puoi anche impostare la dimensione di righe e colonne caricando JSON con la classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Se è necessario impostare la stessa altezza di riga per tutte le righe del foglio di lavoro, è possibile farlo utilizzando [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metodo della raccolta [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Allo stesso modo, per impostare la stessa larghezza di colonna per tutte le colonne del foglio di lavoro, utilizzare il metodo [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) della raccolta ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato JSON in PS con Watermark in C++" %}}
Utilizzando l'API, puoi anche analizzare JSON in PS con filigrana. Per aggiungere una filigrana al tuo documento PS, puoi prima convertire JSON in PDF e aggiungervi una filigrana. Per aggiungere una filigrana, caricare il file PDF appena creato utilizzando la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), impostare proprietà diverse per la filigrana di testo,
chiama il metodo SetText e passa il testo e l'oggetto della filigrana di TextWatermarkOptions. Dopo aver aggiunto la filigrana, è possibile salvare il documento in PS.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}