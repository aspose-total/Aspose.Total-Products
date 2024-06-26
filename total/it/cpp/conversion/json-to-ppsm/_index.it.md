---
title: Converti il formato JSON in PPSM tramite C++
description: Analizza JSON in PPSM in C++ senza utilizzare Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: PPSM
otherformats: POT PPS PPTM OTP POTX PPT PPSX POWERPOINT POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converti il formato JSON in PPSM tramite C++" h2="API C++ per analizzare JSON in PPSM senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire JSON in PPSM all'interno di qualsiasi applicazione C++ in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puoi analizzare JSON in PPTX. Successivamente, utilizzando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), puoi convertire PPTX in PPSM. Entrambe le API rientrano nel pacchetto [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in PPSM tramite C++" %}}
1. Crea un nuovo oggetto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) e leggi dati JSON validi dal file
2. Salva JSON come PPTX utilizzando il metodo [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Salvare il documento in formato PPSM utilizzando il metodo [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total.Cpp```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta il layout e converti il formato JSON in PPSM tramite C++" %}}
Durante l'analisi da JSON a PPSM, puoi anche impostare la dimensione di righe e colonne caricando JSON con la classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Se è necessario impostare la stessa altezza di riga per tutte le righe del foglio di lavoro, è possibile farlo utilizzando [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) metodo della raccolta [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). Allo stesso modo, per impostare la stessa larghezza di colonna per tutte le colonne del foglio di lavoro, utilizzare il metodo [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) della raccolta ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato JSON in PPSM con Watermark in C++" %}}
Utilizzando l'API, puoi anche convertire JSON in PPSM con filigrana. Per aggiungere una filigrana al documento PPSM, puoi prima analizzare JSON in PPTX e aggiungervi una filigrana. Per aggiungere una filigrana, carica il file PPTX appena creato utilizzando la classe [Presentazione](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), ottieni la prima diapositiva, Aggiungi un AutoShape di tipo Rectangle, aggiungi TextFrame al Rectangle, crea l'oggetto Paragraph per una cornice di testo, crea un oggetto Porzione per il paragrafo, aggiungi filigrana usando set_Text() e puoi salvare il documento in PPSM.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}