---
title: Converti il formato JSON in ODT tramite .NET
description: Analizza JSON in ODT in C# senza utilizzare Microsoft Word
url_ignore: /it/net/conversion/json-to-odt/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: ODT
otherformats: DOTX WORD DOT RTF DOC DOCM MOBI OTT WORDML PCL ODT PS FLATOPC EPUB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti il formato JSON in ODT tramite C#" h2="API C# per analizzare JSON in ODT senza utilizzare Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi analizzare JSON in ODT all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passi. Innanzitutto, utilizzando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi esportare JSON in PDF. Successivamente, utilizzando [Aspose.Words for .NET](https://products.aspose.com/words/net/), puoi convertire PDF in ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in ODT tramite C#" %}}
1. Crea un nuovo oggetto [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook) e leggi dati JSON validi dal file
2. Importa il file JSON nel foglio di lavoro utilizzando la classe [JsonUtility](https://apiference.aspose.com/cells/net/aspose.cells.utility/jsonutility) e [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) come PDF
3. Caricare il documento PDF utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document)
4. Salvare il documento in formato ODT utilizzando il metodo [Salva](https://apiference.aspose.com/words/net/aspose.words.document/save/methods/3)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-doc.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta il layout e converti il formato JSON in ODT tramite C#" %}}
Durante l'analisi da JSON a ODT, puoi anche impostare le opzioni di layout per il tuo JSON utilizzando [JsonLayoutOptions](https://apiference.aspose.com/cells/net/aspose.cells.utility/jsonlayouttions). Ti consente di elaborare Array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "set-layout-and-parse-json-to-doc.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il formato JSON in ODT con filigrana" %}}
Utilizzando l'API, puoi anche convertire JSON in ODT con filigrana. Per aggiungere una filigrana al tuo documento ODT, puoi prima analizzare il file JSON in PDF e aggiungervi una filigrana. Per aggiungere una filigrana, caricare il file PDF appena creato utilizzando la classe [Document](https://apiference.aspose.com/words/net/aspose.words/document), creare un'istanza di TextWatermarkOptions e impostarne le proprietà, Chiama il metodo Watermark.SetText e passa il testo e l'oggetto della filigrana di TextWatermarkOptions. Dopo aver aggiunto la filigrana, è possibile salvare il documento in ODT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d9b625f318e1b7a92036a7f5681d43f8" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}