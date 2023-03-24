---
title: Converteer JSON-formaat naar ODT via C++
description: C++ API om JSON naar ODT te ontleden zonder Microsoft Word te gebruiken

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: ODT
otherformats: MOBI DOCM FLATOPC CHM WORD DOTX WORDML PCL EPUB OTT PS RTF DOC DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Converteer JSON-formaat naar ODT via C++" h2="Parseer JSON naar ODT binnen C++-toepassingen zonder Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Door [Aspose.Total for C++](https://products.aspose.com/total/cpp/) te gebruiken, kunt u in twee eenvoudige stappen JSON naar ODT ontleden binnen uw C++-toepassingen. Ten eerste, door [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) te gebruiken, kunt u JSON naar PDF exporteren. Daarna kunt u met [Aspose.Words for C++](https://products.aspose.com/words/cppp/) PDF naar ODT converteren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converteer JSON-formaat naar ODT in C++" %}}
1. Maak een nieuw [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) object en lees geldige JSON-gegevens uit het bestand
2. Sla JSON op als PDF met de methode [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Laad het PDF-document met behulp van de [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) class
4. Sla het document op in ODT-formaat met de methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Conversievereisten" %}}
Installeer via Package Manager Console van Visual Studio met ```Install-Package Aspose.Total.Cpp```.

U kunt ook het offline MSI-installatieprogramma of DLL's in een ZIP-bestand downloaden van [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Stel lay-out in en converteer JSON-indeling naar ODT in C++" %}}
Tijdens het ontleden van JSON naar ODT, kunt u ook de grootte van rijen en kolommen instellen door JSON te laden met de klasse [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Als u voor alle rijen in het werkblad dezelfde rijhoogte moet instellen, kunt u dit doen met de [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) methode van de [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell) verzameling. Om dezelfde kolombreedte voor alle kolommen in het werkblad in te stellen, gebruikt u de methode [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) van de ICells-collectie.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Converteer JSON-formaat naar ODT met watermerk in C++" %}}
Met behulp van de API kunt u JSON ook ontleden naar ODT met watermerk. Om een watermerk aan uw ODT-document toe te voegen, kunt u eerst JSON naar PDF converteren en er een watermerk aan toevoegen. Om een watermerk toe te voegen, laadt u het nieuw gemaakte PDF-bestand met behulp van de [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) klasse, stelt u verschillende eigenschappen in voor tekstwatermerk,
roep de SetText-methode aan en geef de watermerktekst en het object van TextWatermarkOptions door. Nadat u het watermerk hebt toegevoegd, kunt u het document opslaan in ODT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}