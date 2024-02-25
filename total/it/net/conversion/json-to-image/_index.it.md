---
title: Converti il formato JSON in IMAGE tramite .NET
description: Analizza JSON in IMAGE in C# senza utilizzare dipendenze di terze parti
url_ignore: /it/net/conversion/json-to-image/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: JPEG2000
otherformats: WMZ TGA PSD IMAGE DICOM SVGZ EMZ JPEG2000 WMF DXF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converti il formato JSON in IMAGE tramite C#" h2="API C# per analizzare JSON in IMAGE senza utilizzare dipendenze di terze parti" >}}

{{% blocks/products/pf/feature-page-summary %}}
Utilizzando [Aspose.Total for .NET](https://products.aspose.com/total/net/) puoi analizzare JSON in IMAGE all'interno di qualsiasi applicazione .NET, C#, ASP.NET e VB.NET in due semplici passi. Innanzitutto, utilizzando [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), puoi esportare JSON in JPEG. Successivamente, utilizzando [Aspose.Imaging for .NET](https://products.aspose.com/imaging/net/), puoi convertire JPEG in IMAGE.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converti il formato JSON in IMAGE tramite C#" %}}
1. Crea un nuovo oggetto [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook) e leggi i dati JSON dal file
2. Converti JSON in JPEG utilizzando il metodo [Salva](https://apiference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4)
3. Caricare il documento JPEG utilizzando la classe [Image](https://apiference.aspose.com/imaging/net/aspose.imaging/image)
4. Salvare il documento in formato IMAGE utilizzando il metodo [Salva](https://apiference.aspose.com/imaging/net/aspose.imaging.image/save/methods/4)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "parse-json-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Imposta il layout e converti il formato JSON in IMAGE tramite C#" %}}
Durante l'analisi da JSON a IMAGE, puoi anche impostare le opzioni di layout per il tuo JSON utilizzando [JsonLayoutOptions](https://apiference.aspose.com/cells/net/aspose.cells.utility/jsonlayouttions). Ti consente di elaborare Array come una tabella, ignorare i valori null, ignorare il titolo dell'array, ignorare il titolo dell'oggetto, convertire la stringa in numero o data, impostare il formato della data e del numero e impostare lo stile del titolo. Tutte queste opzioni ti consentono di presentare i tuoi dati secondo le tue esigenze. Il frammento di codice seguente mostra come impostare le opzioni di layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "set-layout-and-parse-json-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Analizza il formato JSON in IMAGE con filigrana" %}}
Utilizzando l'API, puoi anche convertire JSON in IMAGE con filigrana nel tuo documento IMAGE. Per aggiungere una filigrana, puoi prima eseguire il rendering del tuo documento JSON in JPEG e aggiungervi una filigrana. Per dimostrare l'operazione, puoi caricare l'immagine JPEG convertita, aggiungere trasformazioni utilizzando un oggetto della classe Matrix e disegnare una stringa come filigrana sulla superficie dell'immagine utilizzando [Graphics](https://apiference.aspose.com/imaging/ net/aspose.imaging/graphics) class' [DrawString](https://apiference.aspose.com/imaging/net/aspose.imaging/graphics/methods/drawstring). Dopo aver aggiunto la filigrana, puoi salvare il JPEG come formato IMAGE. Di seguito è riportato un esempio di codice che mostra come aggiungere una filigrana diagonale al documento. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e13709e61f0cef7c2df582ae7b9beee9" "convert-json-to-image-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}