---
title: Converteer XSLFO naar FODS via C# API
description: C# API om XSLFO-bestand naar FODS te converteren zonder Microsoft Excel of Adobe Reader te gebruiken
url_ignore: /nl/net/conversion/xslfo-to-fods/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: FODS
otherformats: XLAM XLTM DIF XLT ODS SXC EXCEL MD XLTX TXT TSV FODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="C# API om XSLFO naar FODS te renderen" h2="Exporteer XSLFO-bestand naar FODS via C# zonder Microsoft<sup>&reg;</sup> Excel of Adobe<sup>&reg;</sup> Acrobat Reader te gebruiken" >}}

{{% blocks/products/pf/feature-page-summary %}}
Met [Aspose.Total for .NET](https://products.aspose.com/total/net/) kunt u eenvoudig XSLFO-bestanden converteren naar FODS binnen alle .NET-, C#-, ASP.NET- en VB.NET-toepassingen. Ten eerste, door [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) te gebruiken, kunt u XSLFO naar XLSX exporteren. Daarna kunt u met behulp van [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) Spreadsheet Programming API, XLSX naar FODS converteren.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API om XSLFO naar FODS te converteren" %}}
1. Open het XSLFO-bestand met de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converteer XSLFO naar XLSX met behulp van de methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Laad het XLSX-document met behulp van de [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) class
4. Sla het document op in FODS-indeling met de methode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) en stel `Fods` in als SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer vanaf de opdrachtregel als ```nuget install Aspose.Total``` of via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Converteer beveiligde XSLFO naar FODS via C#" %}}
Als uw XSLFO-document met een wachtwoord is beveiligd, kunt u het niet converteren naar FODS zonder het wachtwoord. Met behulp van de API kunt u eerst het beveiligde document openen met een geldig wachtwoord en het daarna converteren. Om het versleutelde bestand te openen, kunt u een nieuwe instantie van de klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) initialiseren en de bestandsnaam en het wachtwoord als argumenten doorgeven.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer XSLFO-bestand naar FODS met watermerk via C#" %}}
Tijdens het converteren van het XSLFO-bestand naar FODS, kunt u ook een watermerk toevoegen aan uw uitvoer-FODS-bestandsformaat. Om een watermerk toe te voegen, kunt u een nieuw werkmapobject maken en het geconverteerde XLSX-document openen, Werkblad selecteren via de index, een vorm maken en de functie AddTextEffect gebruiken. Daarna kunt u uw XLSX-document opslaan als FODS met Watermark. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}