---
title: Converteer JSON-indeling naar ODP via C++
description: JSON ontleden naar ODP in C++ zonder Microsoft PowerPoint te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODP
otherformats: POT PPTM PPSM PPSX POWERPOINT PPS POTX POTM PPT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer JSON-indeling naar ODP via C++" h2="C++ API om JSON naar ODP te parseren zonder Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
U kunt JSON in twee eenvoudige stappen in elke C++-toepassing naar ODP converteren. Ten eerste, door [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) te gebruiken, kunt u JSON ontleden naar PPTX. Daarna kunt u met [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) PPTX naar ODP converteren. Beide API's vallen onder het pakket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-indeling naar ODP via C++" %}}
1. Maak een nieuw [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object en lees geldige JSON-gegevens uit het bestand
2. Sla JSON op als PPTX met de methode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Laad PPTX-document met behulp van [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation) class
4. Sla het document op in ODP-indeling met de methode [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Lay-out instellen en JSON-indeling converteren naar ODP via C++" %}}
Tijdens het ontleden van JSON naar ODP, kunt u ook de grootte van rijen en kolommen instellen door JSON te laden met de klasse [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Als u voor alle rijen in het werkblad dezelfde rijhoogte moet instellen, kunt u dit doen met de [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) methode van de [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) verzameling. Om dezelfde kolombreedte voor alle kolommen in het werkblad in te stellen, gebruikt u de methode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) van de ICells-collectie.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JSON-formaat naar ODP met watermerk in C++" %}}
Met behulp van de API kunt u JSON ook converteren naar ODP met watermerk. Om een watermerk aan uw ODP-document toe te voegen, kunt u eerst JSON ontleden naar PPTX en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PPTX-bestand met behulp van de klasse [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), krijgt u de eerste dia, voegt u een AutoVorm van het type Rechthoek, voeg TextFrame toe aan de rechthoek, maak het alinea-object voor een tekstkader, maak een gedeelte-object voor de alinea, voeg een watermerk toe met set_Text() en sla het document op in ODP.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}