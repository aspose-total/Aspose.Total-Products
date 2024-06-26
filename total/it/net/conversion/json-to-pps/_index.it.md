---
title: Converti il formato JSON in PPS tramite .NET
description: Analizza JSON in PPS in C# senza utilizzare Microsoft PowerPoint
url_ignore: /it/net/conversion/json-to-pps/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPS
otherformats: PPS PPSX POWERPOINT POTM OTP PPTM PPSM PPT POT POTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti il formato JSON in PPS tramite C#" h2="API C# per analizzare JSON in PPS senza utilizzare Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puoi convertire JSON in PPS all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passaggi. Innanzitutto, utilizzando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi analizzare JSON in PPTX. Successivamente, utilizzando [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), puoi convertire PPTX in PPS. Entrambe le API rientrano nel pacchetto [Aspose.Total for .NET](https://products.aspose.com/total/net/).
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in PPS tramite C#" %}}
1. Crea un nuovo oggetto [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook) e leggi dati JSON validi dal file
2. Importa il file JSON nel foglio di lavoro utilizzando la classe [JsonUtility](https://apiference.aspose.com/cells/net/aspose.cells.utility/jsonutility) e [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) come PPTX
3. Caricare il documento PPTX utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/net/aspose.slides/presentation)
4. Salvare il documento in formato PPS utilizzando il metodo [Salva](https://apiference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta il layout e converti il formato JSON in PPS tramite C#" %}}
Durante l'analisi da JSON a PPS, puoi anche impostare le opzioni di layout per il tuo formato JSON utilizzando [JsonLayoutOptions](https://apiference.aspose.com/cells/net/aspose.cells.utility/jsonlayoutions). Ti consente di elaborare l'array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "set-layout-and-parse-json-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converti il formato JSON in PPS con filigrana" %}}
Utilizzando l'API, puoi anche convertire JSON in PPS con filigrana. Per aggiungere una filigrana al documento PPS, puoi prima analizzare JSON in PPTX e aggiungervi una filigrana. Per aggiungere una filigrana, carica il file PPTX appena creato utilizzando la classe [Presentazione](https://apiference.aspose.com/slides/net/aspose.slides/presentation), seleziona la presentazione principale, aggiungi il tipo di forma utilizzando AddAutoShape e aggiungi il testo della filigrana usando AddTextFrame. Dopo aver aggiunto la filigrana, è possibile salvare il documento su PPS. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d2acf3c76ac41a26ab99bf5a5bbff5c7" "parse-json-to-powerpoint-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}